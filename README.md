# qiqibabyy/makefun-tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/qiqibabyy/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/qiqibabyy/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in 3,919 bytes of Python: iterative deepening with alpha-beta/PVS, a transposition table, quiescence search, null-move pruning and a tapered evaluation, all under a fixed 40,000-node budget. It plays through the make.fun environment API (MAKEFUN_ENV_URL) and scored 1,545 Elo in local practice against the house gauntlet.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=34ergn4s&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
