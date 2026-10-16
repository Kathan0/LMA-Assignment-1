# Answer 1 vs Answer 2  (LLM: Qwen/Qwen2.5-3B-Instruct)

## [Keyword trap / synonym] What score does a player receive for a tie?

* Gold: Art. 11.1 (chunk [82, 83]), rank #7 -> #2
* Gold text: c. If the arbiter has rejected the claim, the opponent shall be awarded two extra minutes time. d. The decision of the arbiter shall be final relating to (a), (b) and (c). Article 11: Points 11.1 Unless announced otherwise in advance, a player who wins his game , or wins by forfeit, scores one point (1), a player who loses his game , or forfeits scores no points (0) and a player who draws his game scores a half point (½). Article 12:

**Answer 1 (baseline, chunks [61, 62, 86]):** A player receives a score of a draw if the opponent cannot win the game by any series of legal moves. This is indicated in the passage where it states "if the opponent cannot win the game by any series of legal moves, his score shall be a draw."

**Answer 2 (re-ranked, chunks [86, 82, 63]):** A player receives a half point (½) for drawing their game according to Article 11 of the FIDE Laws of Chess.

---

## [Keyword trap / synonym] Can the arbiter tell me my opponent forgot to press his clock?

* Gold: Art. 13.6 (chunk [93]), rank #10 -> #1
* Gold text: the number of moves made, except in applying Article 8.5, when at least one flag has fallen . The arbiter shall refrain from informing a player that his opponent has completed a move or that the player has not pressed his clock. 13.7 a. Spectators and players in other games are not to speak about or otherwise interfere in a game. If necessary, the arbiter may expel offenders from the playing venue. If someone observes an irregularity, he may inform only the arbiter.

**Answer 1 (baseline, chunks [44, 49, 41]):** Yes, the arbiter can observe if your opponent has forgotten to press their clock and can make the appropriate decision based on the FIDE Laws of Chess regarding time control and game progression.

**Answer 2 (re-ranked, chunks [93, 41, 49]):** No, the arbiter should refrain from informing a player that their opponent has completed a move or that they have not pressed their clock, unless specifically required by Article 8.5 when at least one flag has fallen.

---

## [Exception / corner case] Do I need to write down my moves in a 30 minute game?

* Gold: Art. App. A.2 (vs. 8.1) (chunk [95]), rank #5 -> #2
* Gold text: APPENDICES A. Rapidplay A.1 A 'Rapidplay' game is one where either all the moves must be made in a fixed time of at least 15 minutes but less than 60 minutes for each player; or the time allotted + 60 times any increment is at least 15 minutes, but less than 60 minutes for each player. A.2 Players do not need to record the moves. A.3 Where there is adequate supervision of play, (for example one arbiter for at most three games) the Competition Rules shall apply.

**Answer 1 (baseline, chunks [60, 66, 67]):** In a 30-minute game, you do not need to write down your moves in advance unless you are claiming a draw according to Article 9.2, 9.3, or adjourning the game according to the Guidelines of Adjourned Games point 1.a. Otherwise, you can reply to your opponent's move before recording it, but you must record your previous move before making another.

**Answer 2 (re-ranked, chunks [142, 95, 60]):** No, you do not need to write down your moves in a 30-minute game as specified in the Rapidplay guidelines. In a Rapidplay game, players do not need to record the moves if adequate supervision is available, which allows for adherence to the Competition Rules rather than the detailed scoring requirements.

---

## [Exception / corner case] Can I correct an illegal move in blitz after my opponent has already moved?

* Gold: Art. App. B.3.c (chunk [102, 103]), rank #5 -> #2
* Gold text: opponent cannot checkmate the player's king by any possible series of legal moves, then the claimant is entitled to claim a draw before he has made his own move. Once the opponent has made his own move, an illegal move cannot be corrected unless mutually agreed without intervention of an arbiter. C.

**Answer 1 (baseline, chunks [101, 56, 57]):** No, you cannot correct an illegal move in blitz after your opponent has already moved. According to the laws, an illegal move is completed once the opponent's clock has been started, and the opponent is entitled to claim a win before making their own move.

**Answer 2 (re-ranked, chunks [101, 102, 56]):** No, according to the laws provided, an illegal move cannot be corrected unless mutually agreed upon without the intervention of an arbiter. Once the opponent has made their move, the illegal move cannot be rectified.

---

## [Exception / corner case] In a rapid game, what if the king and queen were placed on the wrong squares at the start?

* Gold: Art. App. A.4.a (chunk [96, 97]), rank #3 -> #1
* Gold text: of play, (for example one arbiter for at most three games) the Competition Rules shall apply. A.4 Where supervision is inadequate the Competition Rules shall apply, except where they are overridden by the following Laws of Rapidplay: a. Once each player has completed three moves, no claim can be made regarding incorrect piece placement, orientation of the chessboard or clock setting. In case of reverse king and queen placement castling with this king is not allowed. b.

**Answer 1 (baseline, chunks [20, 18, 96]):** In a rapid game, if the king and queen were placed on the wrong squares at the start, according to the passage, once each player has completed three moves, no claim can be made regarding incorrect piece placement, orientation of the chessboard or clock setting. Therefore, in this scenario, the incorrect placement of the king and queen would not be corrected.

**Answer 2 (re-ranked, chunks [96, 97, 20]):** In a rapid game, if the king and queen were placed on the wrong squares at the start, the arbiter shall make a ruling according to Article 4 (The act of moving the pieces), only if requested to do so by one or both players. No claim can be made regarding incorrect piece placement, orientation of the chessboard or clock setting until after the players have completed their first three moves.

---

## [Negation / constraint] Can a player appeal the arbiter's ruling on a draw claim in the quickplay finish?

* Gold: Art. 12.10 (chunk [88, 89]), rank #6 -> #2
* Gold text: 12.7 Infraction of any part of Articles 12.1 to 12. 6 shall lead to penalties in accordance with Article 13.4. 12.8 Persistent refusal by a player to comply with the Laws of Chess shall be penalised by loss of the game. The arbiter shall decide the score of the opponent. 12.9 If both players are found guilty according to Article 12.8, the game shall be declared lost by both players. 12.10 In the case of Article 10.2.d or Appendix D a player may not appeal against the decision of the arbiter.

**Answer 1 (baseline, chunks [80, 77, 82]):** No, the passage does not mention any process for a player to appeal an arbiter's ruling on a draw claim during the quickplay finish. Therefore, based on the given context, there is no provision for such an appeal.

**Answer 2 (re-ranked, chunks [117, 89, 80]):** No, according to the passage, a player cannot appeal against the decision of the arbiter regarding a draw claim in the quickplay finish unless the rules of the competition specify otherwise. The passage states that in such cases, a player may only claim a draw based on certain conditions and the arbiter's decision is final without further appeal.

---

## [Negation / constraint] Is the player who has the move allowed to go to the restroom?

* Gold: Art. 12.2 (chunk [84]), rank #3 -> #1
* Gold text: rooms, refreshment area, area set aside for smoking and other places as designated by the arbiter. The player having the move is not allowed to leave the playing area without permission of the arbiter. 12.3 a. During play the pla yers are forbidden to make use of any notes, sources of information or advice, or analyse on another chessboard. b.

**Answer 1 (baseline, chunks [31, 41, 84]):** No, the player who has the move is not allowed to leave the playing area without permission of the arbiter according to the passage.

**Answer 2 (re-ranked, chunks [84, 31, 41]):** No, the player having the move is not allowed to leave the playing area without permission of the arbiter according to the FIDE Laws of Chess.

---

## [Negation / constraint] Can a draw offer be taken back?

* Gold: Art. 9.1.b(1) (chunk [70]), rank #3 -> #1
* Gold text: is still valid but Article 12.6 must be considered. No conditions can be attached to the offer. In both cases the offer cannot be withdrawn and remains valid until the opponent accepts it, rejects it orally, rejects it by touching a piec e with the intention of moving or capturing it, or the game is concluded in some other way.

**Answer 1 (baseline, chunks [69, 71, 70]):** No, a draw offer cannot be withdrawn once made according to the FIDE Laws of Chess. It remains valid until accepted, rejected, or the game concludes in another manner.

**Answer 2 (re-ranked, chunks [70, 69, 71]):** No, a draw offer cannot be withdrawn once made according to the FIDE Laws of Chess. It must remain valid until accepted, rejected, or the game concluded in another way.

---

## [Buried at rank 4-10] Is it illegal to leave a pawn on the last rank without replacing it?

* Gold: Art. 7.4.a (chunk [54]), rank #5 -> #2
* Gold text: for the arbiter's assistance. The arbiter may penalise the player who displaced the pieces. 7.4 a. If during a game it is found that an illegal move, including failing to meet the requirements of the promotion of a pawn or capturing th e opponent's king, has been completed, the position immediately before the irregularity shall be reinstated.

**Answer 1 (baseline, chunks [31, 30, 74]):** No, it is not illegal to leave a pawn on the last rank without replacing it immediately. According to the context, if a pawn reaches the last rank and is not captured, the player still has the right to move it to another square until they choose not to. This means the move is considered legal until the player decides otherwise.

**Answer 2 (re-ranked, chunks [30, 54, 17]):** No, it is not illegal to leave a pawn on the last rank without replacing it. However, the pawn must be promoted according to the FIDE Laws of Chess, which means it must be replaced with a new piece (queen, rook, bishop, or knight) on the same square.

---

## [Buried at rank 4-10] Can I ask the arbiter how many moves have been played?

* Gold: Art. 13.6 (chunk [92]), rank #4 -> #3
* Gold text: in the game by the opponent to the maximum available for that game g. expulsion from the event. 13.5 The arbiter may award either or both players additional time in the event of external disturbance of the game. 13.6 The arbiter must not intervene in a game except in cases described by the Laws of Chess. He shall not indicate the number of moves made, except in applying Article 8.5, when at least one flag has fallen .

**Answer 1 (baseline, chunks [93, 75, 66]):** No, according to Article 13.7a, spectators and players are not to speak about or interfere with a game, and the arbiter shall refrain from informing a player that their opponent has completed a move.

**Answer 2 (re-ranked, chunks [75, 93, 92]):** No, you cannot ask the arbiter how many moves have been played. According to the laws of chess, the arbiter shall refrain from informing a player that their opponent has completed a move or that they have not pressed their clock, unless specifically required by Article 8.5 when at least one flag has fallen.

---

## [Recall ceiling (gold not in top-10)] What should a player do if the piece he wants to promote to is not available?

* Gold: Art. 6.12.b (chunk [48]), rank >10 -> >10
* Gold text: if it happens in the period of a game, in which all remaining moves must be completed. 6.12 a. If the game needs to be interrupted, the arbiter shall stop the clocks. b. A player may stop the clocks only in order to seek the arbiter's assistance, for example when promotion has taken place and the piece required is not available. c. The arbiter shall decide when the game is to be restarted in either case. d.

**Answer 1 (baseline, chunks [27, 30, 121]):** If the player wants to promote a pawn but the piece he desires (such as a queen) is not available, he must choose the next best available piece that can be promoted to, such as a rook, bishop, or knight. The player must then announce which piece they have chosen for the promotion.

**Answer 2 (re-ranked, chunks [27, 30, 121]):** If the player wants to promote a pawn but the piece he desires (such as a queen) is not available, he must choose the next best available piece that can be promoted to, such as a rook, bishop, or knight. The player must then announce which piece they have chosen for the promotion.

---

## [Re-ranker demotes gold] Can a player castle when his king is currently in check?

* Gold: Art. 3.8.b(2) (chunk [21]), rank #5 -> #8
* Gold text: b. (1) The right to castle has been lost: [a] if the king has already moved, or [b] with a rook that has already moved. (2) Castling is prevented temporarily: [a] if the square on which the king stands, or the square which it must cross, or the square which it is to occupy, is attacked by one or more of the opponent's pieces, or [b] if there is any piece between the king and the rook with which castling is to be effected.

**Answer 1 (baseline, chunks [6, 22, 26]):** No, a player cannot castle when their king is currently in check as per Article 4.3.a of the FIDE Laws of Chess, which states that if a player touches both the king and the rook intended for castling, and castling is illegal due to the king being in check, the player must make another legal move with their king, including castling on the other side if possible.

**Answer 2 (re-ranked, chunks [102, 26, 6]):** No, a player cannot castle when their king is currently in check because castle requires moving the king two squares towards a rook, which would put the king in check. According to the laws, if the king is in check, the player must take some form of action to remove the threat, such as moving the king out of check or capturing the piece threatening the king.

---

## [Still outside top-3] What if I accidentally knock pieces off their squares?

* Gold: Art. 7.3 (chunk [53]), rank #8 -> #7
* Gold text: a game h as begun with colours reversed then it shall continue, unless the arbiter rules otherwise. 7.3 If a player displaces one or more pieces, he shall re -establish the correct position on his own time. If necessary, either the player or his opponent shall stop the clocks and ask for the arbiter's assistance. The arbiter may penalise the player who displaced the pieces. 7.4 a.

**Answer 1 (baseline, chunks [11, 12, 28]):** If you accidentally knock pieces off their squares, these pieces are considered to be removed from the chessboard as part of the same move according to Article 3.1 of the FIDE Laws of Chess. This means they are no longer on the board and cannot be moved back into position.

**Answer 2 (re-ranked, chunks [57, 12, 11]):** If during a game it is found that pieces have been displaced from their squares, the position before the irregularity shall be re-instated according to Article 7.5 of the FIDE Laws of Chess.

---

