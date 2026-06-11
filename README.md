# Crate King V2 — Phase A Foundation

Open `index.html` in a browser.

Because this version uses `fetch()` to load JSON data, some browsers may block it when opened directly from Finder.
If it does not load, run this inside the folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Included Phase A features:
- Game-style sidebar navigation
- Animated screen transitions
- Dealer/location framework
- Visual record cards
- Visual music room scene
- Save/load system with localStorage
- Buy/sell/crate dig/listen loop
- Room upgrades
- Achievements
- Statistics
- JSON-backed records/dealers data


## Mobile / iPhone version

This folder has been updated as a mobile-friendly Progressive Web App.

How to use it on iPhone:
1. Upload the whole folder to Netlify, Vercel, GitHub Pages, or another HTTPS host.
2. Open the website link in Safari on your iPhone.
3. Tap Share.
4. Tap Add to Home Screen.
5. Open Crate King from your home screen.

Progress is saved in the browser using localStorage. The service worker also caches the app after the first successful online load.
