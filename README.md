# MLB Draft Ops — Free Fantasy Baseball Auction Draft Tool (2026)

[![Live Demo](https://img.shields.io/badge/demo-live-blue?style=flat-square)](https://davmos15.github.io/mlb-fantasy-draft/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

A **free, real-time fantasy baseball auction draft assistant** built as a single HTML file. Designed for H2H Points leagues (12-team, $260 budget) with player data sourced from the **Yahoo 2026 Fantasy Baseball Top 300** rankings.

No signup, no install, no app store — just open the page and draft.

## Features

- **Smart Recommendations** — Rules engine scores all available players by positional need, budget remaining, and real-time market inflation
- **Real-Time Multi-Device Sync** — Firebase-powered draft rooms let your entire league co-draft from any device with instant state sync
- **Gut Override** — Type any player name and get an instant AI-generated argument *for* drafting them
- **Nomination Queue** — Plan your upcoming nominations with auto-suggest so you're always ready
- **Draft Log** — Track every pick with steal/overpay analysis vs. fair value
- **Budget Danger Alerts** — Pulsing warning bar when funds are critically low
- **Player Ticker** — Scrolling bottom bar of top available players at a glance

## How It Works

1. **Create a Room** — First-time visitors pick a room name (e.g. `my-league-2026`). Share it with your league-mates.
2. **Draft** — Browse players, get smart recommendations, bid, and mark winners. The app tracks your roster, budget, and positional needs in real time.
3. **Sync** — Every pick syncs instantly across all connected devices in the same room. No refresh needed.

## Quick Start

Open the live app — no download required:

**[https://davmos15.github.io/mlb-fantasy-draft/](https://davmos15.github.io/mlb-fantasy-draft/)**

Or clone and open `index.html` locally in any browser.

## Scoring Reference

| Category | Points |
|----------|--------|
| HR       | 8      |
| SV       | 16     |
| W        | 14     |
| QS       | 6      |
| K        | -1     |

## Tech Stack

- Pure HTML / CSS / JavaScript — zero dependencies, no build tools or frameworks
- Firebase Realtime Database (loaded via CDN)
- Google Fonts (Barlow Condensed, Share Tech Mono)

## Support

If this tool helped your draft, consider buying me a coffee:

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/nadavmoskow)

## License

MIT
