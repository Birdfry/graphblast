# GraphBlast

An easier take on Graphwar: **type a math function, its graph is your weapon.**

Pick a direction (◀ Left / Right ▶), type something like `0.5*x`, `x^2`, or `sin(x)`, and your tank fires the curve. If the curve flies off the top or bottom of the board it keeps going invisibly — and reappears if it comes back. One hit kills. Watch out for destructible walls, and don't shoot yourself.

## Play

- **Live demo:** https://muse.ai/s/graphwar-game-qq6rmjxrdfna
- Or open `index.html` directly in any browser — no build, no server needed.

## Features

- Custom math expression parser (trig, inverse trig, `e^x`, `ln`, `log`, `^`, parentheses…)
- Clickable symbol keypad + function presets, live dashed shot preview
- Directional shots with off-board re-entry
- 4–5 destructible walls per round (they take crater damage)
- You vs 1–3 bots (they simulate real shots, arc over walls, occasionally goof off)
- 👥 Friend multiplayer via 5-letter room codes (MQTT-over-WebSocket, host-authoritative, 3-minute turn timer)
- 😈 Cheat button (solo only — in friend matches, clicking it instantly eliminates you)

## Files

- `index.html` — the entire game, single self-contained file

## License

MIT — see [LICENSE](LICENSE).
