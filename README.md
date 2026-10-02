# COLD WAR — Season 2 Auction Board

Browser-based drag-and-drop PUBG auction board. No build step: open `index.html`, or deploy the folder to any static host (e.g. Vercel). Keep `html2canvas.min.js` next to `index.html` (used for roster screenshots, works offline).

## Features
- Per-captain budgets (no fixed budget): set when adding a captain, change any time with **+ Points** (add or set)
- **Live bid panel**: Pick Random Player, +500 / +1,000 / +5,000 / +10,000 buttons, leading captain, live remaining / max-bid check, **Confirm SOLD** or **Mark UNSOLD**
- Budget + squad-size enforcement (override with a confirmation). Max bid reserves the base price for each empty slot
- Drag a player onto a team, or use **Assign…** on the card (works on touch devices). Both ask for the selling price
- **Unsold round**: when no players remain available, Pick Random offers to recycle unsold players
- **Undo** (last 40 actions), **Sales Log**, **Export / Import JSON** backups
- **Bulk Import** players (`IGN, Role`) and captains (`Name, Points`) from pasted lists
- **OBS Mode**: hides controls, 4-column team grid (Esc to exit)
- Roster screenshot (PNG), search and filters, browser local persistence
- Esc closes dialogs, Enter submits

## Before the event
1. ⚙ **Settings**: set max squad size (0 = unlimited) and default captain points
2. Set the base price with **Set Base Starting Point**
3. **Export** regularly as a backup. Data only lives in this browser's storage
