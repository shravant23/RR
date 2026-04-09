# Ritual Runner

A beautiful, fully local web app for building and running personal daily rituals. No accounts, no servers — everything saves to your browser.

🔗 **Live site:** https://shravant23.github.io/RR

---

## What it does

Ritual Runner helps you design structured routines (morning, wind-down, workout, focus sessions, etc.) and guides you through them step by step with a live countdown timer. It adapts each session to how you're feeling and how much time you have.

---

## Features

### Routines
- Create routines with any number of steps
- Each step has a name, duration (in minutes), optional flag, and energy level (low / medium / high)
- Edit, duplicate, or delete routines anytime
- Each routine gets its own unique color identity

### Smart Adaptation
Before every run, you set your **mood** (1–5) and **available time** (5 min – 5 hrs). The app then:
- Removes optional steps if you're short on time
- Reorders steps by energy level based on your mood
- Adds a "Take a breath" step + reflection prompt if you're feeling low

### Run Mode
- Live countdown timer with animated ring
- Progress bar across the top
- Skip, pause, or reset any step
- Swipe left/right (or use arrow keys) to navigate steps
- Steps slide in with a direction-aware animation
- Ambient background color shifts as you progress
- Particle burst on step completion

### Audio
- Chimes play on step completion and skip
- Chime style varies by step energy level — calm tone for low energy, punchy fanfare for high
- Sound can be toggled on/off

### Activity Monitor
- During a run, if there's no mouse or keyboard activity for **10 minutes**, a nudge appears to check you're still there
- Dismisses automatically when you interact

### History & Stats
- Every completed run is logged with date, mood, and completion %
- Stats bar shows total runs, average completion, and current streak
- Heat map of the last 91 days
- Streak badge on the home screen (pulses on milestone days: 3, 7, 14, 21, 30, 50, 100)

### Share Rituals
- Export any routine as a short code
- Anyone can import it on their own copy of the app using "Import ritual from code"
- No link sharing needed — works across any two devices

### Other
- Dark mode (deep ocean theme)
- Daily quote that changes on every visit
- "Today's Pick" recommendation based on time of day and last run
- Confetti on completion — intensity scales with how many steps you finished
- Keyboard shortcuts: `Space` to pause, `→` to skip/done, `←` to go back, `Escape` to exit
- Fully offline — no internet required after first load

---

## Data & Privacy

All data (routines, history, preferences) is stored in your browser's **localStorage**. Nothing is sent to any server. Each person who uses the app has their own completely separate data.

Data persists across sessions as long as you use the same browser on the same device. Clearing browser data will erase it.

---

## Running locally

Just open `index.html` in any modern browser. No install, no build step.
