# Daily Tracker

A personal daily checklist and productivity tracker that installs on a phone like an app.

## What it does
- Daily checklist for a **College day** or a **Holiday** timetable (switch or swipe)
- Hours logged per day, week and cycle
- 30-day charts: **Hours** bars and a completion **Trend** line (swipe or tap to switch)
- **Weekly report** with completion %, best and lowest day, comparison with last week, streaks and patterns, built only from the ticks you saved
- Calendar to open any past day
- Backup and restore by copy and paste
- Works offline once installed

## Install on Android
1. Open the site link (Settings > Pages shows it) in **Chrome**.
2. Tap the **three-dot menu > Install app** (or Add to Home screen).

## Your data
Everything is saved **on your phone only**, inside the browser. Nothing is stored in this repository.
Use **Backup and restore data** at the bottom of the app to keep a copy or move to a new phone.

## Weekly report timing
The app cannot run in the background or send notifications. The report for a finished week
(Monday to Sunday) is created when you open the app from **Monday 12:00 AM** onward.

## Updating
Upload new files over the old ones. In `sw.js` change `daily-tracker-v1` to `daily-tracker-v2`
so phones drop the old saved copy. The new version appears the second time you open the app.

## Files
`index.html` app - `manifest.webmanifest` install info - `sw.js` offline support - `icon-*.png` app icons
