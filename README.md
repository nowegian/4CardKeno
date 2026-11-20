# 4-Card Keno

A single-page 4-Card Keno game. Open `index.html` in any browser — no build step or dependencies.

## How it plays
- Four cards (A–D), each with its own 1–10 spots, played against **one shared draw of 20 numbers** from 1–80.
- **Bet:** choose a denomination (1¢, 5¢, 10¢, 25¢, $1, $5) and 1x–4x credits per card. When you pick your own numbers, every card with numbers on it is played and charged; empty cards are skipped. A Smart Chart always plays all 4 cards. Every played card uses the same bet: **total bet = card bet × cards played**. Quick Pick and Clear work on the card tab you're on.
- Each card is paid independently from the pay table × its bet.
- Quick Pick, auto play (runs until you stop it), draw speeds, sound, and session stats.

## Smart Charts strategy
Built from the *Mystic Keno Smart Charts™ – Four Card Keno Edition* (TheMysticGambler.com). Pick a chart, enter your base numbers (any numbers, in order #1, #2, …) by clicking the **Master** tab, and Cards A–D fill automatically, skipping each chart's blacked-out boxes.

| Chart | Base numbers | Blacked out on A / B / C / D |
|---|---|---|
| 3 Spot | 5 | 2,3 / 4,5 / 1,4 / 3,5 |
| 4 Spot | 6 | 2,3 / 5,6 / 1,4 / 3,5 |
| 5 Spot | 7 | 2,3 / 6,7 / 1,4 / 3,5 |
| 6 Spot | 8 | 2,3 / 6,7 / 1,4 / 5,8 |
| 7 Spot | 9 | 1,2 / 5,6 / 8,9 / 3,7 |
| 8 Spot | 10 | 1,2 / 5,6 / 8,9 / 3,7 |
| 9 Spot | 11 | 2,11 / 5,6 / 8,9 / 3,10 |
| 10 Spot | 12 | 4,11 / 5,12 / 8,9 / 1,10 |
| Condensed 3 Spot | 4 | 2 / 3 / 1 / 4 |
| Condensed 4 Spot | 5 | 2 / 3 / 1 / 5 |
| Condensed 5 Spot | 6 | 2 / 6 / 1 / 5 |
| Condensed 6 Spot | 7 | 2 / 6 / 1 / 5 |
| Condensed 7 Spot | 8 | 2 / 6 / 1 / 7 |
| Condensed 8 Spot | 9 | 1 / 5 / 7 / 9 |
| Condensed 9 Spot | 10 | 3 / 1 / 7 / 9 |
| Condensed 10 Spot | 11 | 3 / 1 / 7 / 11 |
| 5 Spots over 4 Spots | 6 | 5 / 2 / 1,3 / 4,6 |
| 7 Spots over 6 Spots | 8 | 6 / 2 / 1,3 / 5,7 |

Quick Pick base can scatter numbers in a zone, build **triplets** (groups of 3 touching numbers, from the booklet's tips) or a tight cluster. You can also choose "None" and mark the four cards yourself.

The **Master** tab shows all four cards combined: a number shared by 2 or more cards shows a gold `*`, a number on only one card shows that card's letter in its color (A red, B green, C blue, D yellow), and base numbers show their position (#1…).

The game shows an exact guarantee table (computed over every way each master catch can happen), a per-round breakdown, and a JSON export of the setup.

For entertainment only — no real money.
