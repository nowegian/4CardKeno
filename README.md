# 4-Card Keno

A single-page 4-Card Keno game. Open `index.html` in any browser — no build step or dependencies.

## How it plays
- Four cards (A–D), each with its own 1–10 spots, played against **one shared draw of 20 numbers** from 1–80.
- **Bet:** choose a denomination (1¢, 5¢, 25¢, $1) and 1x–4x credits per card. All four cards are always played at the same bet: **total bet = card bet × 4**.
- Each card is paid independently from the pay table × its bet.
- Quick Pick, auto play (5–100 games), draw speeds, sound, and session stats.

## Master Wheel strategy
Pick a master block of numbers; each card drops specific elements of it:

| Variant | Master | Card drops | Anchors (on all cards) |
|---|---|---|---|
| 3-Spot | 4 numbers | A / B / C / D | — |
| 5-Spot | 6 numbers | A / B / C / D | E, F |
| 7-Spot | 9 numbers | A+B / C+D / E+F / G+H | I |
| 9-Spot | 11 numbers | A+B / C+D / E+F / G+H | I, J, K |

The game shows an exact guarantee table (computed over every way each master catch can happen), a per-round breakdown, and a JSON export of the setup.

For entertainment only — no real money.
