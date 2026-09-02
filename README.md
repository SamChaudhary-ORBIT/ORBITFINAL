# Orbit — Installable PWA

This folder is the modified Orbit project with Progressive Web App support.

Files:
- `index.html` — Orbit's original app code, modified for PWA installation
- `manifest.json` — app name, icon, standalone display settings
- `sw.js` — service worker for caching/offline shell
- `icons/` — Orbit app icons

## Deploy
Upload/push these files to the root of the site that serves Orbit. Netlify can then serve the same site as an installable PWA.

## Install
- Android/Chrome: open Orbit and use the Install Orbit prompt/button.
- Windows/Edge/Chrome: use the browser's Install option or the Orbit install button.
- iPhone/iPad: Safari → Share → Add to Home Screen.

No Play Store or App Store listing is required.
