# Daily Smiles
A cheerful, private, no-account social-interaction tracker for phones.

## Publish using GitHub Pages
1. Create a **public** GitHub repository named `daily-smiles`.
2. Upload the files in this folder to the **root** of the repository (not inside an extra folder).
3. In repository **Settings → Pages**, choose **Deploy from a branch**, `main`, `/ (root)`, and save.
4. Once GitHub publishes, visit `https://YOUR-USERNAME.github.io/daily-smiles/`.
5. On iPhone: open the link in Safari, tap Share → Add to Home Screen. On Android: open in Chrome and choose Install app or Add to Home screen.

## Notes
- All records are stored locally in this browser/device. The hosting repository never receives them.
- The tracking day runs 3:30 a.m. to 3:29 a.m. local time.
- The archive shows 30 completed tracking days, with detailed entries older than 30 days removed.
- Daily totals are retained separately to support streaks.
- Double tap a current-day entry to edit, or use Enter on a focused entry for accessibility.
- Archive includes optional JSON backup and restore; backups contain private names/notes.
- Opening `index.html` directly may work for basic testing, but GitHub Pages is needed to test installability and offline caching.
- The animation uses original SVG/CSS and respects reduced-motion preferences.
