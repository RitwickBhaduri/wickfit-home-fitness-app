# WickFit 🏋️

Your personal calisthenics & home workout trainer. Built for one user — you.

## Deploy to GitHub + Vercel (Free)

### Step 1 — GitHub
1. Go to github.com → New repository → name it `wickfit` → Public → Create
2. Upload all files from this folder (drag & drop on the GitHub page)
3. Commit with message: `Initial WickFit release`

### Step 2 — Vercel
1. Go to vercel.com → Sign in with GitHub
2. Add New Project → Import `wickfit` repo
3. No settings to change → Deploy
4. Live at: `https://wickfit-[username].vercel.app`

### Step 3 — Install as PWA
- **Android:** Open in Chrome → 3-dot menu → Add to Home Screen
- **iOS:** Open in Safari → Share → Add to Home Screen

## Files
| File | Purpose |
|------|---------|
| `index.html` | Complete app (single file) |
| `manifest.json` | PWA name, icons, theme |
| `sw.js` | Offline service worker |
| `icon-192.png` | Home screen icon |
| `icon-512.png` | Splash screen icon |
| `vercel.json` | Deployment headers |

## Data
All progress stored in browser localStorage — no login, no backend, no cost.
