# Farm Medicine Log

A Progressive Web App (PWA) for on-farm animal medicine record keeping.
Works offline, saves to your home screen, and exports to Excel.

## Features
- Log medicine records for cattle, sheep, pigs and poultry
- Identify animals by ear tag + name
- Track withdrawal periods with automatic countdown
- Export to .xlsx (full log, withdrawal report, or by species)
- Works offline after first load
- Installable on iPhone via Safari "Add to Home Screen"

## Setup

No build step needed. Just deploy the files as-is.

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `farm-med-log`)
2. Upload all files in this folder to the repository
3. Go to Settings → Pages → Source: Deploy from branch → main → / (root)
4. Your app will be live at: `https://yourusername.github.io/farm-med-log`

## Adding to iPhone Home Screen

1. Open the app URL in Safari
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Tap "Add" — it will appear as an app icon

## Files

- `index.html` — the entire app
- `manifest.json` — PWA metadata (name, icon, theme)
- `sw.js` — service worker for offline use
- `icon-192.png` / `icon-512.png` — app icons (replace with your own)

## Notes

- All data is stored locally on the device (localStorage)
- No data is sent anywhere — completely private
- Export regularly to Excel as a backup
- Paper records remain the official legal record
