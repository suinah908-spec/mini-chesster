# Mini Chesster

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/suinah908-spec/mini-chesster/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/suinah908-spec/mini-chesster/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty.
Alpha-beta with iterative deepening, transposition table, killers,
history ordering, quiescence, and piece-square tables — all in one
file (`main.py`, 4,096 bytes max). Deterministic: fixed node budget
per move, no clock, no unseeded randomness.
