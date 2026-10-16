# RAG Assignment: Baseline vs. Re-Ranking

Compares two retrieval pipelines over the same chunked corpus (FIDE Laws of Chess):

- **Pipeline 1 (Baseline):** bi-encoder `all-MiniLM-L6-v2` + FAISS cosine search → top-10 → top-3 to the LLM.
- **Pipeline 2 (Re-Ranking):** same top-10 → `cross-encoder/ms-marco-MiniLM-L-6-v2` → re-sorted top-3 to the LLM.

LLM: `Qwen/Qwen2.5-3B-Instruct` (local, greedy decoding). Set `GEMINI_API_KEY` to use Gemini instead.

## Files
| Path | What |
|---|---|
| `RAG_Baseline_vs_ReRanking.ipynb` | All code, with outputs (single notebook) |
| `data/FIDE_Laws_of_Chess.pdf` | Source document (FIDE Handbook E.I.01) |
| `results/` | CSV/Markdown tables produced by the notebook (rank shifts, answers, metrics, latency, scaling) |

## Run
```bash
python -m venv .venv
.venv/Scripts/activate            # Windows  (Linux/Mac: source .venv/bin/activate)
pip install torch --index-url https://download.pytorch.org/whl/cu124
pip install -r requirements.txt
jupyter notebook RAG_Baseline_vs_ReRanking.ipynb
```
A CUDA GPU with at least 8 GB is recommended for the local 3B LLM. On CPU it works, but it's slow.
