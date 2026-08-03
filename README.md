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
