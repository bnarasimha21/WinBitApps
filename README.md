# Portfolio Website

Personal portfolio showcasing my indie apps and development philosophy.

## Live Site

**URL:** [narsi.dev](https://narsi.dev) (or your domain)

## Apps Featured

- **FlipIt** - Memory matching game (Android/iOS)
- **Streakly** - Habit tracker with no subscriptions (iOS)
- **TripXplorer** - AI-powered trip planner
- **Silly Debates** - Daily debate game (Web)

## Tech Stack

- Pure HTML/CSS/JS (no build step)
- Tailwind CSS (via CDN)
- Google Fonts (Inter)

## Deployment

### Option 1: GitHub Pages

1. Push to GitHub
2. Settings → Pages → Deploy from main branch
3. Site will be at `username.github.io/portfolio`

### Option 2: Vercel

```bash
npx vercel --prod
```

### Option 3: Netlify

Drag and drop the folder to [netlify.com/drop](https://app.netlify.com/drop)

### Option 4: Firebase Hosting

```bash
firebase init hosting
firebase deploy
```

## Customization

### Update Apps

Edit the apps section in `index.html`:

```html
<!-- Find the apps grid and modify -->
<div class="grid md:grid-cols-2 gap-8">
    <!-- App cards here -->
</div>
```

### Change Colors

The main gradient is defined in Tailwind classes:
- Primary: `from-indigo-500 to-purple-600`
- Modify in the hero section and buttons

### Add New App

Copy an existing app card and update:
- Icon emoji and gradient colors
- App name and tagline
- Description
- Platform tags
- Pricing
- Links

## Files

```
portfolio/
├── index.html      # Main portfolio page
├── privacy.html    # Privacy policy
├── terms.html      # Terms of service (TODO)
└── README.md       # This file
```

## License

MIT
