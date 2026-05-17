# 🪐 Mood – Cosmic Journal

A beautiful mobile-first mood tracker that turns your daily emotions into a glowing constellation.

## ✨ Features

- Log your mood and energy level each day
- Watch your **Mood Constellation** grow over time — each entry becomes a glowing orb plotted across an emotional space
- Streaks, achievements, and weekly summaries
- **Save to Home Screen** for a native app feel (PWA)
- Works fully offline after first load
- Export your constellation as an image to share

## 🚀 Deploy with GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app will be live at `https://<your-username>.github.io/<repo-name>/`

Users can then open that URL on their phone and tap **"Add to Home Screen"** to install it as an app with the Mood icon.

## 📁 File Structure

```
├── index.html          # Main app
├── manifest.json       # PWA manifest (name, icon, theme)
├── sw.js               # Service worker (offline cache)
├── icons/
│   ├── icon-192.png    # Home screen icon (Android)
│   ├── icon-512.png    # Splash / high-res icon
│   └── apple-touch-icon.png  # Home screen icon (iOS)
└── README.md
```

## 🔒 Privacy

All data is stored locally on the user's device via `localStorage`. Nothing is sent to any server.
