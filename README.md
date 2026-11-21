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

## Hosting

Upload `index.html` to any static host. It works from any path, e.g. `/scrumbut-bingo/`.
