# Grand Highlander Deal Board

A phone-first negotiation board for buying a **2026 Toyota Grand Highlander XLE AWD** (cash, Iowa City, IA). Built for three people shopping together — Michael runs the numbers, Ana & Marta do the talking. Styled after Zara: black on white, Didone serif, wide-tracked type, lots of whitespace.

## Live page
Once GitHub Pages is enabled, the board is at:
**https://michael480th.github.io/procurementagent_automotive/**

- **`index.html`** — the live board (open on all three phones). An instant out-the-door calculator, the targets, scripts, signals, dealer tricks, and a running offer log.
- **`cheatsheet.html`** — printable double-sided cheat sheet (Ana & Marta front, Michael back). Paper backup for when dealership signal is bad.
- **`data/facts.md`** — the reference numbers behind the board.

## How we use it live
1. Ana & Marta ask for the dealer's best **out-the-door** price.
2. Michael types the vehicle price into the calculator → instant OTD + green / amber / red call.
3. Michael also feeds each round to Claude in chat; Claude updates the **offer log** here (give it ~1–2 min, then refresh).
4. Michael signals the others: **green = close, amber = keep going, red = hold / walk.**

The page auto-refreshes when idle, so everyone sees the latest without fiddling.

## The one number that matters
**Ceiling out-the-door = $50,500.** At full sticker ($48,700) the OTD is ~$51,850 — over budget. The price has to move, the config has to get cheaper, or we cross-shop.

*Estimates only — verify against the actual window sticker. Not affiliated with Toyota or any dealer.*
