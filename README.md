# WinBitApps

Website for [WinBitApps](https://winbitapps.com) — a small indie studio building simple, privacy-focused apps. No subscriptions, no data harvesting — just honest software.

## Apps

| App | Description | Platform | Status |
|-----|-------------|----------|--------|
| **FlipIt** | Memory card matching game | Android / iOS | Available |
| **DailyBrick** | Offline-first habit tracker | iOS | Coming Soon |
| **TripXplorer** | AI-powered trip planner | Web | Coming Soon |

## Tech Stack

- HTML & CSS (no build step)
- [Tailwind CSS](https://tailwindcss.com) via CDN (privacy page)
- Google Fonts — DM Sans, DM Serif Display

## Project Structure

```
WinBitApps/
├── images/
│   ├── flipit/         # FlipIt app screenshots
│   └── dailybrick/     # DailyBrick app screenshots
├── index.html          # Main portfolio page
├── privacy.html        # Privacy policy
├── vercel.json         # Vercel deployment config
└── README.md
```

## Deployment

Hosted on [Vercel](https://vercel.com). The site is static HTML so no build step is needed — `vercel.json` is configured to skip the build.

```bash
npx vercel --prod
```

## License

MIT
