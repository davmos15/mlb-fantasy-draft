# MLB Draft Ops — War Room

A standalone, real-time MLB Fantasy Auction Draft assistant built as a single HTML file. Designed for H2H Points leagues (12-team, $260 budget).

## Features

- **Smart Recommendations** — Rules engine scores all available players by positional need, budget, and market inflation
- **Real-time Firebase Sync** — Two devices can co-draft from the same room with instant state sync
- **Gut Override** — Type any player name and get an instant argument *for* drafting them
- **Nomination Queue** — Plan your upcoming nominations with auto-suggest
- **Draft Log** — Track every pick with steal/overpay analysis
- **Budget Danger Alerts** — Pulsing warning bar when funds are critically low
- **Player Ticker** — Scrolling bottom bar of top available players

## Quick Start

Open `index.html` in any browser. The app auto-connects to Firebase on load — no setup required.

### Live URL

Deployed via GitHub Pages: **https://davmos15.github.io/mlb-fantasy-draft/**

### Change Draft Room

Click the **ROOM** button in the top bar to switch between different draft rooms (e.g., `nadav2025`, `test-draft`, `league-finals`).

## Tech Stack

- Pure HTML / CSS / JavaScript — no build tools or frameworks
- Firebase Realtime Database (loaded via CDN)
- Google Fonts (Barlow Condensed, Share Tech Mono)

## Scoring Reference

| Category | Points |
|----------|--------|
| HR       | 8      |
| SV       | 16     |
| W        | 14     |
| QS       | 6      |
| K        | -1     |

## License

MIT
