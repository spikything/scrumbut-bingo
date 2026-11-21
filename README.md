# Scrumbut Bingo

> We do Scrum, but...

A bingo board of 40 classic "ScrumBut" anti-patterns — the ways teams claim to do Scrum while quietly doing something else.

**Play it:** https://spikything.com/scrumbut-bingo

## How to play

Play at stand-up every day and see how many days it takes to complete ScrumBut Bingo. Tap or click a square whenever you spot it in the wild. Check all 40 to win.

Good luck!

## Features

- 40 squares, responsive grid (5 columns on desktop, 2 on phones)
- Progress and day counter: `Day 3 · 12 of 40`
- Fireworks and a **SCRUMBUT BINGO!** popup showing how many days it took
- Light and dark themes: follows your system setting, with a sun/moon toggle to override
- Print-friendly board
- Board, start date, theme and "seen instructions" are saved in the browser (`localStorage`); nothing is sent anywhere
- **Reset** clears the board and restarts the day count

## Running locally

It's a single static file with no build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

The page loads the Plus Jakarta Sans font from Google Fonts and falls back to system fonts when offline.

## Install as an app

Scrumbut Bingo is a Progressive Web App. Open it in Chrome, Edge or Safari and choose **Install** (desktop) or **Add to Home Screen** (mobile). Once installed it works offline.

## Hosting

Upload the whole folder to any static host served over HTTPS. All paths are relative, so it works from any path, e.g. `/scrumbut-bingo/`.

```
index.html             the app
manifest.webmanifest   PWA manifest
sw.js                  service worker (offline cache)
icons/                 app icons and favicon
```

When you change any file, bump `VERSION` in `sw.js` so installed copies pick up the update.
