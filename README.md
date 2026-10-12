# Return to Court

A personal 12-week knee-durability and volleyball/tennis performance program — a real, installable web app (not a Claude Artifact), because the GPS run tracker needs device location, which Artifacts can't access.

## Features
- 12-week program across 6 training days + a dedicated running day, with a phase toggle (Foundation / Build / Performance)
- Full-screen guided Workout Mode: animated exercise demo → written instructions + real YouTube reference → timed sets with a live weight input → rest countdown → finish stats
- Per-exercise weight tracking, adjustable with +/- steppers, saved on-device
- Live calorie estimate during a workout (MET-based)
- End-of-workout stats: total weight lifted, sets, reps, duration, calories
- GPS-tracked running (distance, pace, calories) using the Geolocation API — requires HTTPS or localhost
- Installable as a home-screen PWA with a screen wake lock so a session doesn't time out mid-workout

## Local development
```
node serve.js 5500
```
then open http://localhost:5500

## Deployment
Static site — deployed via GitHub Pages from this repo's `main` branch, `/ (root)`.

## Credits
- Muscle-highlight diagrams: [wger project](https://github.com/wger-project/wger), CC BY-SA 3.0
- Exercise demo clips (main program list links) verified against real coaching channels on YouTube
