# Watchlist

A simple, offline TV show tracker. Keep track of everything you watch: Western shows, K-Dramas, C-Dramas, Turkish dramas, Japanese anime, Western animation and more.

No accounts and no internet needed. Your list is saved in a file on your own computer.

---

## Features

- **Add shows** one at a time, or **mass add** by pasting a list (one title per line)
- **Automatic title capitalization**: "the lord of the rings" becomes "The Lord of the Rings"
- **Statuses**: Watching, Completed, On hold, Plan to watch, Dropped
- **Types** split into Live action and Animation (Western, K-Drama, C-Drama, J-Drama, Turkish, Thai, Anime, Western animation, Donghua…)
- **Edit everything in place**: title, type, status, season, rewatch count, rating (1–10) and notes
- **Your own types and statuses**: add, rename or remove them
- **Bulk actions**: select several shows to change their status or type, or delete them
- **Search, filter and sort**, including "Recently updated"
- **Stats** summary: totals, average rating, counts per status and type
- **Light / dark mode**
- **Saves to a file** on your computer and saves automatically after each change

---

## Getting started

### 1. Download
Click the green **Code** button at the top of this page, then **Download ZIP**.

### 2. Unzip
Right-click the downloaded ZIP and choose **Extract All** (Windows), or double-click it (Mac).
Move the extracted folder somewhere permanent, for example `Documents/Watchlist App/`.

> ⚠️ Don't open the app from inside the ZIP. Always extract it first, or your list won't save.

### 3. Open
Double-click **`Watchlist.html`**. It opens in your browser.
Use **Google Chrome** or **Microsoft Edge**. Firefox and Safari can't save to a file.

Tip: bookmark the page so you can open it quickly next time.

### 4. Choose where to save (first time only)
Click the **save icon** (top right). Pick where to store your list. We suggest the same folder as the app, as `watchlist.json`.
From now on, the app always saves to that same file.

---

## Everyday use

| To do this | Do this |
| --- | --- |
| Add a show | Type the title, pick a type and status, click **Add show** |
| Add many shows | Click **Mass add**, paste one title per line, pick a type and status, click **Add** |
| Edit anything | Click the field in the list and change it |
| Next season | Click **+** next to Season |
| Mark finished | Click **✓** on the row |
| Add notes | Click **Notes** on the row |
| Change many at once | Tick the checkboxes and use the bar at the bottom |
| Undo a delete | Click **Undo** in the message that pops up |
| Edit types & statuses | Menu (☰) → **Edit types & statuses** |
| Dark / light mode | Menu (☰) → **Dark mode** |
| Save right now | Click the save icon or press **Ctrl+S** (**Cmd+S** on Mac) |

### Saving
- The app **saves automatically** a few seconds after each change.
- A **red dot** on the save icon means there are unsaved changes.
- When you reopen the app, your list appears right away. On your first click, Chrome asks to **Allow** access to your save file. Click **Allow** (or **Allow on every visit** if offered).

---

## Moving to another computer or browser

1. Copy the whole app folder, including `watchlist.json`, to the new computer.
2. Open `Watchlist.html`.
3. Menu (☰) → **Use a different save file…** → select your `watchlist.json`.

Your whole list, including your custom types and statuses, loads in.

---

## Troubleshooting

**My list is empty when I reopen the app**
Menu (☰) → **Use a different save file…** → select your `watchlist.json`.
Also check this Chrome setting: Settings → Privacy and security → Site data. Turn off **"Delete data sites have saved to your device when you close all windows."**

**Chrome asks "Allow" every time**
This is a Chrome security rule. Choose **Allow on every visit** if it's offered.

**The save file is in the wrong folder**
Move `watchlist.json` where you want it. Then go to Menu (☰) → **Use a different save file…** and select it in its new place.

---

## Files

| File | What it is |
| --- | --- |
| `Watchlist.html` | The app; open this |
| `support.js`, `react.js`, `react-dom.js` | Code the app needs to run |
| `styles.css` | The app's look |
| `watchlist.json` | Your list (created when you first save) |

Keep all of these in the same folder.

---

## Privacy

Everything stays on your computer. Nothing is uploaded anywhere.
`watchlist.json` is listed in `.gitignore`, so your personal list won't be pushed to GitHub by accident.
