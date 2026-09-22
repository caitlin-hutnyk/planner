# Summer & Fall 2026 · Weekend Planner

Two single-file, self-contained calendars for planning weekends. No build, no
dependencies — just open the HTML file.

- **Summer** (`index.html`) — Jun 1 → Sep 21, ending with the Europe trip
- **Fall** (`fall.html`) — Sep 1 → Jan 1 2027, starting with the Europe trip

Both are served by GitHub Pages from `main`, and link to each other.

## Features

- Continuous month-grid calendar with multi-day event bars
- Weekends + BC stat holidays shaded
- Status styles: **solid** = confirmed, **dashed outline** = tentative, **underline** = ongoing/background
- Category colours: music, family, friends, sports, away/travel
- Click any event for a detail panel — add notes, confirm tentative plans
- "Want to fit in" wishlist + a reality-check panel
- Everything saves automatically to the browser (localStorage)
- Responsive mobile layout (Add to Home Screen for an app-like view)

## Use

Open `index.html` or `fall.html` in any browser. Your notes and edits persist per-device in
localStorage (key `summer2026.v2`). The "Reset all edits" button restores the
original plan.
