# Planner

Personal weekend calendars: `index.html` (Fall, the default) and `summer.html` (Summer).
Events live in the `EVENTS` array near the top of each file's script.

## Workflow

- Commit every change straight to `main` and push it. Don't use feature branches
  or open pull requests.
- GitHub Pages serves the site from `main`, so pushing to `main` deploys it.
  Nothing else needs to be done.
- If a session starts on another branch, still commit to `main`: check out `main`,
  pull, make the change, then commit and push.

## Editing conventions

- To cancel a plan, delete its entry from `EVENTS`.
- `status`: `"confirmed"` or `"tentative"`. Set `away:true` for trips or overnights
  away from home.
- Dates use `D(year, month, day)` with a 1-based month.
