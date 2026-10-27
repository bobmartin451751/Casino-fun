# Casino Fun

A single-file browser casino: five Vegas-style tables, one shared bankroll, and six regulars who remember every coin.

Open `index.html` in any modern browser — no build step, no dependencies, no network requests.

## Tables

| Table | Game | Notes |
| --- | --- | --- |
| 1 | Texas Hold'em | No-limit, blinds 5/10, four bot regulars, side pots, real equity maths |
| 2 | Omaha | Four hole cards, exactly two must play |
| 3 | Blackjack | Six decks, dealer stands soft 17, 3:2 blackjack, split / double / insurance |
| 4 | Roulette | European single-zero, straight 35:1, splits, streets, corners, lines, outside bets |
| 5 | Baccarat | Punto banco, eight decks, commission and automatic third-card rules |

## Features

- 1,000 starting coins shared across all five tables; bust and the house shows you the door with a career summary.
- Six bot players with persistent chip stacks, win/loss records and a lobby leaderboard.
- Hand-built "Classic Vegas" art: walnut, green felt, gold trim, SVG court cards, damask card backs, 5/25/100/500 chips.
- Progress is saved to `localStorage`, so the bankroll and the regulars survive a refresh.
- Fast-forward toggle for quicker sessions, plus a sound toggle.

## Run

```
start index.html
```

Or just double-click the file. Everything is inline in `index.html`.
