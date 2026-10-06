# TON Minter + Tasks module

Fork of [ton-blockchain/minter](https://github.com/ton-blockchain/minter) with an added **Tasks** module.

## Tasks module
- page `/tasks` (route + link in the header)
- create / complete / delete tasks, filters All/Active/Completed, counters
- a task can be bound to a Jetton master address and/or the connected wallet
- state persisted in `localStorage` (`quasar:tasks`) via `recoil-persist`

Verified: `npx tsc --noEmit` clean, `react-app-rewired build` OK.
