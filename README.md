# WickFit — Personal Calisthenics Trainer

Your personal home workout app. 4-day calisthenics programme, personalised for you.

## Deploy Free on Vercel (Recommended)

1. Go to https://vercel.com and sign up (free)
2. Click "Add New Project"
3. Choose "Upload" (drag and drop this folder)
4. Click Deploy — done! You'll get a URL like `wickfit.vercel.app`

## Deploy Free on Netlify (Alternative)

1. Go to https://netlify.com and sign up (free)
2. Drag this entire folder onto the Netlify dashboard
3. Done — instant URL

## Deploy Free on GitHub Pages

1. Create a free GitHub account at https://github.com
2. Create a new repository named `wickfit`
3. Upload all files in this folder
4. Go to Settings → Pages → Source: main branch
5. Your app will be at `https://yourusername.github.io/wickfit`

## Install as PWA on your phone

1. Open your deployed URL in Chrome (Android) or Safari (iOS)
2. **Android**: Tap the 3-dot menu → "Add to Home Screen"
3. **iOS**: Tap the Share button → "Add to Home Screen"
4. WickFit icon appears on your home screen — works like a native app!

## Data Storage

All your progress is saved locally in your browser (localStorage).
- Survives app close, phone restart ✓
- Does NOT sync across devices
- Clearing browser data will reset progress

## Files

- `index.html` — The entire app (single file PWA)
- `manifest.json` — PWA metadata (name, icons, theme)
- `sw.js` — Service Worker for offline support
- `icon-192.png` — App icon (home screen)
- `icon-512.png` — App icon (splash screen)
- `vercel.json` — Vercel deployment config
