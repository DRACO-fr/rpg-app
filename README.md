# Skillion: Gamify your life

Pixel RPG life-tracker. Complete quests, level up six attributes.

## Put it on GitHub Pages
1. Create a new repo and upload everything in this folder to the repo root.
2. Repo Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Wait a minute. Your app is at `https://YOUR-USERNAME.github.io/REPO-NAME/skillion.html`.

## Package it with PWABuilder
1. Go to pwabuilder.com and paste the URL above (use the `skillion.html` link).
2. Fix nothing: manifest, service worker and icons are already included.
3. Choose Package for Stores, then Android (or Windows / iOS), and download.

## Files
- skillion.html: the app
- index.html: redirects to the app
- manifest.webmanifest, sw.js: PWA setup (offline support)
- logo.png and icons/: logo and app icons
