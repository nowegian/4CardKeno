# 4-Card Keno

A single-page 4-Card Keno game. Open `index.html` in any browser — no build step or dependencies.

## How it plays
- Four cards (A–D), each with its own 1–10 spots, played against **one shared draw of 20 numbers** from 1–80.
- **Bet:** choose a denomination (1¢, 5¢, 25¢, $1) and 1x–4x credits per card. All four cards are always played at the same bet: **total bet = card bet × 4**.
- Each card is paid independently from the pay table × its bet.
- Quick Pick, auto play (5–100 games), draw speeds, sound, and session stats.

## Master Wheel strategy
Mark any numbers you like on all four cards — B, C and D don't have to be clustered with Card A. The game reads your four cards as a wheel:

- **Covered numbers** = every number on at least one card.
- Numbers are lettered from each card's drops in order (Card A's left-out numbers are A, B…, then Card B's, C's, D's), with **anchors** (on every card) last.
- It checks whether the cards form a standard wheel:

| Variant | Each card | Covers | Each card leaves out | Anchors |
|---|---|---|---|---|
| 3-Spot | 3 | 4 | 1 (A / B / C / D) | — |
| 5-Spot | 5 | 6 | 1 (A / B / C / D) | 2 |
| 7-Spot | 7 | 9 | 2 (A+B / C+D / E+F / G+H) | 1 |
| 9-Spot | 9 | 11 | 2 (A+B / C+D / E+F / G+H) | 3 |

Example 7-spot wheel: A `53 54 62 63 71 73 74`, B `44 52 53 54 71 73 74`, C `44 52 53 54 62 63 71`, D `44 52 54 62 63 73 74` → covers 9, anchor 54.

There's also a helper that fills B–D from Card A by adding the cover numbers, which you can then edit.

The game shows an exact guarantee table (computed over every way each master catch can happen), a per-round breakdown, and a JSON export of the setup.

For entertainment only — no real money.
