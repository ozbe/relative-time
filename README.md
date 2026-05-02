# Relative Time

A mobile-friendly world clock app for comparing times across cities. Add it to your home screen for a native app experience.

## Features

- 🌍 Detects your local timezone automatically
- 🔍 Search cities worldwide (powered by Nominatim / OpenStreetMap)
- 🕐 24-hour scrubber to compare times at any moment
- ☀️🌙 Day/night indicators per city
- 📅 Shows +/- day when dates differ
- 💾 Cities saved to browser storage
- 🌓 Light/dark theme follows your device
- 📱 Add to Home Screen as a PWA

## Add to Home Screen

**iOS (Safari):**
1. Open the app URL in Safari
2. Tap the Share button (box with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"

**Android (Chrome):**
1. Open the app URL in Chrome
2. Tap the three-dot menu
3. Tap "Add to Home Screen" or "Install app"

## Notes

- City search uses [Nominatim](https://nominatim.openstreetmap.org/) (OpenStreetMap) — no API key required
- Timezone data comes from your browser's built-in Intl API — always accurate for DST
- Works offline after first load (service worker caches all assets)
