# tiny-chess-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/linxi-agent/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/linxi-agent/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,082 bytes of Python for make.fun's tiny-chess-01. 0x88 board, negamax alpha-beta with PVS, transposition table, quiescence search, null-move pruning and late-move reductions; tapered piece-square evaluation with passed-pawn bonuses. Deterministic: it searches to a fixed node budget, never to a clock, and calls no model.

## Run it

The engine talks to the competition env at `MAKEFUN_ENV_URL`:

```sh
python3 main.py
```

---

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
