# Stride — Fitness Tracker

An interactive fitness app prototype for runners and gym-goers. Built as a single HTML file with no dependencies to install.

## Features

- **Dashboard** — weekly stats, mileage chart, activity feed, streak tracker
- **Run tracking** — route visualization, pace charts, split analysis
- **Workout logger** — live set/rep entry with checkoff, editable weights
- **Training plan** — weekly calendar, planned vs actual volume
- **Progress** — PR tracking, 5K trend, volume over time

## Getting Started

Just open `index.html` in any browser — no build step, no install needed.

```bash
git clone https://github.com/YOUR_USERNAME/stride-fitness.git
cd stride-fitness
open index.html   # macOS
# or double-click index.html on Windows/Linux
```

## Tech stack

- Vanilla HTML, CSS, JavaScript
- [Chart.js](https://www.chartjs.org/) via CDN for charts
- Dark mode supported via `prefers-color-scheme`

## Roadmap

- [ ] LocalStorage persistence for workouts and runs
- [ ] GPS run tracking via Geolocation API
- [ ] AI-powered training plan generation
- [ ] Export to CSV / Strava sync
- [ ] Mobile PWA support

## License

MIT
