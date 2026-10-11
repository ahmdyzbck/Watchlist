# Watchlist

A simple offline TV show tracker — Western, K-Drama, C-Drama, Turkish, anime, western animation and more.

## Features
- Add shows one at a time or mass-add (one title per line), auto title-casing
- Statuses: Watching, Completed, On hold, Plan to watch, Dropped — fully editable, as are types
- Inline editing of title, type, status, season, rewatch count, rating and notes
- Bulk select to change status/type or delete
- Search, filter, sort, stats summary
- Light / dark mode
- Saves to a `watchlist.json` file you choose (auto-saves after changes)

## Use
Open `Watchlist.html` in Chrome or Edge (file saving needs the File System Access API). Keep all files in the same folder.

## Files
- `Watchlist.html` — the app
- `support.js`, `react.js`, `react-dom.js` — runtime
- `styles.css` — styles

Your `watchlist.json` holds your personal list — add it to `.gitignore` if you don't want it public.
