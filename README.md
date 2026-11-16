# VOIDSWARM — Neon Arena Survival

[![make.fun](https://make.fun/badge/best-game-01.svg)](https://make.fun/bounty/best-game-01)
[![rank](https://make.fun/badge/best-game-01/Kroco365/best-game-01/rank.svg)](https://make.fun/bounty/best-game-01)
[![reward](https://make.fun/badge/best-game-01/Kroco365/best-game-01/reward.svg)](https://make.fun/bounty/best-game-01)

A complete, original arcade survival game for the [make.fun best-game-01 bounty](https://make.fun/bounty/best-game-01): survive escalating waves of the swarm, chain kills for a combo multiplier, dash through enemies, grab pickups, and beat your high score. Single self-contained `game/index.html` (canvas, no libraries, no network), with WebAudio sound generated in code.

## How to play

- **WASD / arrows** — move
- **Mouse** — aim
- **Hold click / Space** — fire
- **Shift** — dash (brief invulnerability, 2.2s cooldown)
- **P** — pause, **M** — mute

3 lives, +1 life every 3 waves. Pickups: Shield, Rapid fire, Spread shot. Combo builds to x5.

## Run it

Serve `game/` with any static server, e.g. `node serve.ts`, then open http://localhost:8080.

## Entry

`main.ts` (Node 22, stdlib only) hands the game in: it copies `game/` and `screenshots/` to `/output` and writes `/output/dossier.json` with the vendored make.fun library (`vendor/makefun-game.ts`).

## License

MIT — see [LICENSE](LICENSE).
