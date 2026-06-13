# 🏏 CricScore

A feature-rich, ball-by-ball cricket scoring web app. Built for real match scoring — tracks runs, wickets, extras, player stats, and special rules like free hits, all with undo support and admin PIN protection.

**Live demo → [cricscore-eta.vercel.app](https://cricscore-eta.vercel.app/)**

---

## Features

- **Ball-by-ball scoring** — log every delivery with full detail
- **Player career stats** — batting and bowling stats tracked across matches
- **Free hit logic** — automatically flags and enforces free hit rules after no-balls
- **Undo support** — step back through deliveries without corrupting the scorecard
- **Joker player role** — custom player role with special in-game logic
- **Admin PIN protection** — lock scoring controls behind a PIN to prevent accidental edits
- **Extras tracking** — wides, no-balls, byes, leg-byes all handled correctly
- **Persistent storage** — match data saved to localStorage, survives page refresh
- Fully responsive — works on phones at the ground

---

## How to Use

1. Open the app and set up your match (teams, overs, players)
2. Enter the admin PIN to unlock scoring
3. Score ball by ball — tap the result after each delivery
4. Player stats update automatically
5. Use undo if you make a mistake
6. Match summary available at the end of each innings

---

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- localStorage (for match persistence — no backend needed)

---

## Getting Started

```bash
git clone https://github.com/your-username/cricscore
cd cricscore
open index.html
```

Or visit the live deployment at [cricscore-eta.vercel.app](https://cricscore-eta.vercel.app/)

---

## Deployment

Deployed on **Vercel** as a static site — no server or database required.

1. Fork this repo
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import the repo → Deploy

---

## Roadmap

- [ ] Multi-match history
- [ ] Export scorecards as PDF
- [ ] Partnership tracking
- [ ] Over-by-over run rate graph
- [ ] PWA support (installable on Android)

---

## About

Built by **Vishwak Vemuru**.  
CricScore was built to solve a real problem — scoring local cricket matches accurately on a phone without needing an internet connection or a complicated app.
