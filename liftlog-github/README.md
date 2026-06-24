# 🏋️ Lift Log

A mobile-first workout tracking app built as a single HTML file — no installation, no backend, no account required. Open it in any browser and add it to your phone's home screen for a native app experience.

**Live site:** `https://YOUR-USERNAME.github.io/liftlog`

---

## Features

- **4-day upper/lower split** — fully programmed with sets, reps, and rest times targeting every major muscle group 2–4× per week
- **Per-exercise weight logging** — log weight and reps for every set, with history shown directly on each exercise card
- **PT coaching recommendations** — after each save the app analyses your weight trend and gives a specific progression recommendation (add weight, deload, plateau buster, new PR alert)
- **Alternate exercises** — every machine-based exercise has a swap button for when equipment is unavailable
- **Full form cues** — step-by-step instructions written from a certified PT perspective for every exercise
- **Run day logging** — auto-captures live weather (temperature, conditions, wind) via your location at the moment you log a run, with PT notes on how conditions affect performance
- **Golf / active rest logging** — log holes, steps, and how you felt on rest days
- **Body weight tracker** — progress bar toward your goal with a mini chart of recent entries
- **Activity streak** — colour-coded dot grid showing lift, run, golf, and rest days across the last 28 days
- **Personal records** — automatically surfaces your all-time best weight for every exercise
- **Pull-up progression tracker** — phase guidance from lat pulldowns through to weighted pull-ups
- **Editable exercises** — tap any exercise to edit name, sets/reps, muscles, form cues, and key cue
- **Workout journal** — free-text notes screen for logging how sessions felt
- **Offline-capable** — works with no internet connection (weather fetch requires location permission)
- **PWA-ready** — add to home screen on iOS (Safari → Share → Add to Home Screen) or Android (Chrome → menu → Add to Home Screen)

---

## Muscle coverage

Every major group is hit at least twice per week:

| Group | Frequency |
|---|---|
| Chest | ×2 |
| Upper chest | ×2 |
| Lats | ×4 |
| Mid back / Rhomboids | ×4 |
| Traps | ×3 |
| Front delts | ×2 |
| Side (medial) delts | ×2 |
| Rear delts | ×4 |
| Biceps | ×2 |
| Triceps (all 3 heads) | ×4 |
| Forearms / Grip | ×2 |
| Quadriceps | ×3 |
| Hamstrings | ×4 |
| Glutes | ×4 |
| Calves (gastroc + soleus) | ×2 |
| Adductors | ×2 |
| Core / Rectus abdominis | ×4 |
| Obliques | ×4 |
| Rotator cuff | ×4 |

---

## Weekly schedule

| Day | Session | Duration |
|---|---|---|
| Monday | Upper A — Strength | ~65 min |
| Tuesday | Run | 4–7 miles |
| Wednesday | Lower A — Strength + Plyo | ~70 min |
| Thursday | Upper B — Hypertrophy | ~65 min |
| Friday | Lower B — Hypertrophy + KB | ~65 min |
| Saturday | Golf / Active rest | — |
| Sunday | Run or full rest | — |

---

## Hosting on GitHub Pages

1. Create a new public repository on GitHub (e.g. `liftlog`)
2. Upload `index.html` to the root of the repository
3. Go to **Settings → Pages → Source** and select `main` branch, `/ (root)` folder
4. Click **Save** — your site will be live at `https://YOUR-USERNAME.github.io/liftlog` within 2 minutes

To update the app later, simply re-upload `index.html` and the site rebuilds automatically.

---

## Data storage

All data (workout logs, body weight, run history, notes) is stored in your browser's `localStorage`. It is private to your device and never leaves it. If you clear your browser data, your logs will be cleared too — export your notes to the journal screen periodically if you want a backup.

---

## Tech stack

- Single HTML file — HTML, CSS, and vanilla JavaScript
- Zero dependencies, zero build step
- Weather via [Open-Meteo](https://open-meteo.com/) (free, no API key required)
- Storage via browser `localStorage`

---

## Shoulder note

This programme is designed around a partially torn left labrum. All overhead pressing is replaced with landmine press (oblique arc path), and face pulls are included every upper session as rotator cuff maintenance. Any exercise that loads the arm above 90° abduction is excluded.
