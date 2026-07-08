# Nictionary

Nictionary is a self-contained offline five-letter word game in the style of Wordle.

## Play online

Upload this repo to GitHub and enable GitHub Pages. The hosted game runs from `index.html`.

## Download for offline play

Open the hosted game, go to **Settings**, and select **Download offline version**. You can also download `Nictionary_Offline.html` directly from the repo and open it in a modern browser.

## Files

- `index.html` — hosted GitHub Pages version.
- `Nictionary_Offline.html` — identical self-contained offline copy.
- `README.md` — this file.

## Notes

- No external scripts, fonts, services, or network calls are required.
- Saves and stats are stored in the browser's local storage.
- Online and offline copies have separate browser storage, so use the built-in export/import tools to move progress between them.

## Current build

Version: 1.10

Fixes in this build:

- Absent keyboard letters now visibly change to a darker state instead of appearing unchanged.
- Keyboard state handling was made more robust by normalizing letters and reapplying same-rank states when needed.
- Daily/Practice remains centered in the single-row mobile header.
- The Settings modal includes a **Download offline version** button.
