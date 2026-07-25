# FastTrack ⏳

Offline-first PWA to track fasting and weight — zero dependencies, no build step.

**Features:** fasting timer with presets (13:11 → 36h + custom), editable start time,
fasting-stage education, past-fast logging & history, streaks, weight log with SVG chart,
**30-day weight projection** (linear regression over your last 30 weigh-ins) with
goal-date estimate, water tracking, body/blood/electrolyte measurements, notes,
dark/light theme (follows system), JSON export/import backup, installable & offline.

## Run

```sh
python3 -m http.server 8000
# open http://localhost:8000 — install via browser "Add to Home Screen"
```

Data lives in `localStorage`; use Settings → Export for backups.
