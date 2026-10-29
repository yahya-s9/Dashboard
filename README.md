# Daily Habit Tracker

Daily Habit Tracker — a Next.js static export, served by GitHub Pages.

- Check off daily habits; the daily score is 1 point per habit, gated on all
  five prayers (Fajr, Dhuhr, Asr, Maghrib, Isha) — a day without all five
  scores 0.
- Syncs with a Google Sheet (source of truth on load); localStorage is an
  offline cache.
- Features: stacked bar chart by category, single-category viewer, per-category
  heatmaps, backfill panel, habit fields and per-day values, category goals
  and KPI graphs.

Source lives in `~/workspace/next-tracker/` (Next.js app); `out/` is the
static export deployed here. To update: rebuild there (`npm run build`) and
push the new `out/` contents to this repo's root.
