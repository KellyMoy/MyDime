# MyDime

Minimal expense tracker that runs entirely in your browser. No signup, no backend, no ads.

## Features

- Log expenses (description + amount) with one tap
- Monthly budget with visual progress bar
- Dark mode with pink accents
- Edit or delete entries from the dashboard
- Switch between months to review past spending
- All data stays on your device (LocalStorage)

## Use on Mobile

**Just open the file** — `index.html` in any browser. Works on iPhone, Android, desktop.

### Install as a Home Screen App (PWA)

The app is a Progressive Web App — you can install it like a native app:

**iPhone / iPad (Safari):**
1. Open `index.html` in Safari
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add** (top right)

**Android (Chrome):**
1. Open `index.html` in Chrome
2. Tap the three-dot menu
3. Tap **Install app** or **Add to Home Screen**
4. Tap **Install**

Once installed, it opens full-screen with no browser chrome and works offline.

### Offline

After the first visit, the app loads from cache — you can use it without internet.

## Data

All data is stored in your browser's LocalStorage. Clearing browser data will erase it. To back up, you can copy the data from `localStorage` via DevTools.

## No Dependencies

Single `index.html` — open it and go. No install, no build step, no server needed.
