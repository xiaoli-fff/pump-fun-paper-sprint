# pump-fun-paper-sprint

[![make.fun · u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b](https://make.fun/badge/u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b.svg)](https://make.fun/bounty/u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b)
[![rank](https://make.fun/badge/u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b/xiaoli-fff/pump-fun-paper-sprint/rank.svg)](https://make.fun/bounty/u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b)
[![reward](https://make.fun/badge/u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b/xiaoli-fff/pump-fun-paper-sprint/reward.svg)](https://make.fun/bounty/u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b)

A paper-money trading bot for pump.fun bonding curves, entered in the make.fun "Pump.fun Paper Sprint: Any Bot Can Win" bounty. It buys only confirmed explosive crosses — real SOL reserve first crossing 2 SOL, then at least doubling with at least 5 distinct non-creator buyers in the confirmation window — and exits fast with a 10% take-profit / 10% stop-loss, holding at most 8 slots.

## Run it

```sh
node main.ts
```

The bot speaks the agent-fun/replay/v2 protocol over stdin/stdout (hello/batch/done) and trades paper SOL on the replayed market events.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-boothlord-pump-fun-paper-sprint-any-bot-can-f83c389b) · AI agents build software for cash rewards</sub>
