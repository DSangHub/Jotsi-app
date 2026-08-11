# Jotsi — Johnny / Joanie On The Spot Images

Real moments. Real people. No paid influencers. No AI fakes.

**jotsi.app**

## What it is

Jotsi is a web app for posting unusual, peculiar, or interesting things you see in the moment.

- Post locally (with geolocation) or to the open forum
- Earn based on time spent on the app
- Chat with followers, search nearby, manage follow requests
- Jotsi Plus curated highlights
- **No-AI Content Bot** flags synthetic images
- Share to X, Instagram, Facebook, LinkedIn, Threads, Bluesky
- **Jotsi Dash** mode for docked / parked viewing (WiFi + auto shutoff if removed from dock)
- Full **English / Español** language toggle

## Safety (Jotsi Dash)

- **Do not use while driving**
- Dash connects via WiFi when docked
- Auto shutoff if removed from dock
- Intended for parked viewing or passenger use only

## Run locally

Just open `index.html` in a modern browser (Chrome, Safari, Firefox).

For best results (camera, geolocation, installability):

```bash
# Simple local server
npx serve .
# or
python3 -m http.server 3000
```

Then open `http://localhost:3000`

## Deploy

### Vercel / Netlify / Cloudflare Pages
- Drag & drop the folder, or connect this GitHub repo
- Set the root to the project folder
- No build step required

### GitHub Pages
1. Push this repo
2. Settings → Pages → Deploy from branch `main` / root

## Tech

- Single-file progressive web app (HTML + Tailwind CDN + vanilla JS)
- localStorage for posts and language preference
- Geolocation API
- Web Share API + platform share intents
- No backend yet (see roadmap below)

## Roadmap

- Real backend (accounts, geo posts, messaging)
- Proper AI-image detection API
- Push notifications
- Earnings → real payouts / points system
- PWA manifest + service worker
- Hardware dock pairing for Jotsi Dash

## License

Private / all rights reserved for now.
