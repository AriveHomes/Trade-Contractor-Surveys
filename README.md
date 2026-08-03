# Arive Trade Performance Index Dashboard

This is the latest complete dashboard package using the newest Construction, Purchasing, and Warranty Fillout exports.

## GitHub Pages setup

Upload/replace these files in your repository:

- `index.html`
- `data/` folder
- `README.md`

Then go to Settings > Pages and make sure the site is deploying from the `main` branch and `/root`.

## Notes

- The dashboard shows all 47 surveyed trades.
- TPI weighting: Construction 50%, Purchasing 25%, Warranty 25%.
- Contractors with no department score still appear in the All Surveyed Trades table.
- Reverse-scored questions, such as excessive VPO/work-order adjustment questions, are converted so higher is always better.


## Review Scheduler

This package also includes `schedule.html` and `data/review_schedule.csv`.

- The schedule starts Wednesday, August 12, 2026.
- It schedules 4 trade partners per week.
- It starts with the lowest TPI score and works upward.
- To update status, meeting time, owner, or notes, edit `data/review_schedule.csv`, commit the change, and refresh GitHub Pages.


## Editable scheduler note

The `schedule.html` page lets you change the meeting date, time, status, and notes for each trade.

Browser edits save locally when you click **Save Changes**. To make the edits permanent on GitHub Pages for everyone, click **Download Updated CSV** from the scheduler page and replace `data/review_schedule.csv` in the repo.


## Branding
This package includes an Arive-themed logo mark at `assets/arive-mark.svg` and matching Arive-style colors across the dashboard and scheduler pages. If you want the exact official company logo later, replace that SVG and keep the same filename.

## Logo update

This version uses the Arive Homes logo style from the screenshot provided, saved as `assets/arive-homes-logo.png`.


## Embedded logo fix

This version embeds the Arive Homes logo directly inside `index.html` and `schedule.html`.
That means the logo should load even if the `assets` folder is not uploaded correctly.


## Clean executive theme

This version removes the semi-transparent washed-out theme and uses a cleaner Arive Homes look:
solid dark green/black backgrounds, lime-green accents, sharper cards, and no foggy transparent overlay.


## Free text scheduler update

The scheduler now uses plain text fields for meeting date and meeting time instead of browser date/time pickers. This lets you type dates like "Aug. 14", "Next Thursday", or "Wednesday, August 12, 2026" and times like "9:00 AM", "Morning", or "2:30 PM".
