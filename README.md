# Mini Chesster

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/suinah908-spec/mini-chesster/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/suinah908-spec/mini-chesster/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty.
Alpha-beta with iterative deepening (PVS + LMR + null-move), transposition
table, killers, history ordering, quiescence, and tapered piece-square
tables — all in one file (`main.py`, 4,096 bytes max). Deterministic:
fixed 200k-node budget per move, no clock, no unseeded randomness.

Practice trials (6 games): trial 0 4W 1D 1L Elo 1,545 spare 376;
trial 1 4W 2L Elo 1,451 spare 467; trial 2 3W 3L Elo 1,279 spare 268.
