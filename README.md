<div align="center">

# Frogcus

**A premium study timer with a chill frog pond vibe.**

Pomodoro, Deep Focus, Stopwatch, and custom timers — with music, stats, streaks, and achievements, all in one page. No app. No login. Just press start and focus.

[![Live Demo](https://img.shields.io/badge/START%20FOCUS-Live%20Demo-3DD090?style=for-the-badge&logo=vercel&logoColor=white)](https://frogcus.vercel.app/)
[![Type](https://img.shields.io/badge/Type-Study%20Timer-1B7554?style=for-the-badge)](https://frogcus.vercel.app/)
[![Modes](https://img.shields.io/badge/Modes-Pomodoro%20%2F%20Deep%20Focus%20%2F%20Stopwatch-26784A?style=for-the-badge)](https://frogcus.vercel.app/)
[![No Install](https://img.shields.io/badge/No%20Install-Required-3DD090?style=for-the-badge)](https://frogcus.vercel.app/)

</div>

---

## About

Frogcus is a **study timer** built around a calm frog-pond theme — a looping ambient pond video, a glowing green ring timer, and a soft glassmorphism UI designed to make long study sessions feel less like a grind.

It bundles everything a focus session needs into one page: multiple timer modes, an embedded YouTube music player, session stats, a streak tracker, and unlockable achievements — no sign-up, no tracking, just open and lock in.

> *Sit by the pond. Focus like a frog.*

---

## Session Flow

```
Load Frogcus     →  Pond video loads, logo pulses in
    ↓
Pick a Mode      →  Pomodoro / Deep Focus / Stopwatch / Custom
    ↓
Set the Timer    →  Adjust minutes/seconds, or use a preset
    ↓
Start Session    →  Ring fills, session dot lights up
    ↓
Track Progress   →  Stats, heatmap, streaks, and history update
    ↓
Unlock Rewards   →  Achievements light up as milestones are hit
```

---

## Features

- **4 Timer Modes** — Pomodoro, Deep Focus, Stopwatch, and fully custom minute/second timers
- **Fullscreen Focus Mode** — a distraction-free, oversized glowing timer for deep sessions
- **Ambient Pond Background** — looping desktop/mobile video with a custom cursor and particle canvas
- **YouTube Music Player** — paste a link and play focus music directly in the app, with volume and visualizer
- **Session Stats & Heatmap** — tracked sessions, weekly bars, and a study heatmap at a glance
- **Streaks & Goals** — daily streak counter and an adjustable daily goal with progress bar
- **Achievements** — unlockable badges as study milestones are reached
- **Custom Theming** — everything themed around a single green/teal palette, easy to re-skin

---

## Built For

```
Purpose  → Focused studying & deep work sessions
Users    → Students, remote workers, anyone who needs a Pomodoro
Type     → Study / Productivity Timer
Form     → Single-page Web App
```

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, glassmorphism, SVG ring animations) |
| Interactivity | Vanilla JavaScript |
| Fonts | Fredoka One, Nunito, Space Mono (Google Fonts) |
| Media | Embedded YouTube iframe API, local MP4 background video |
| Hosting | Vercel |

No frameworks. No build step. One HTML file, ~2,000 lines, styles and logic included.

---

## Project Structure

```
frogcus/
├── index.html            # Entire app — styles, timer logic, stats, achievements
├── frogcus-logo.png       # App logo (loading screen + header)
├── frogcus-desktop.mp4    # Pond background video (desktop)
├── frogcus-mobile.mp4     # Pond background video (mobile)
└── halloween.png          # Seasonal favicon variant
```

---

## Colour Palette

| Swatch | Hex | Role |
|--------|-----|------|
| 🟩 | `#26784A` | Deep green — accents, dim states |
| 🟩 | `#1B7554` | Teal-green — secondary accent, gradients |
| 🟢 | `#3DD090` | Bright green — primary highlight, glow, active states |

---

## Customising / Extending

| Section | What to Edit |
|---|---|
| `:root` CSS variables in `index.html` | Colour theme (`--green`, `--teal`, `--pond-dark`, etc.) |
| `frogcus-desktop.mp4` / `frogcus-mobile.mp4` | Swap for your own ambient background video |
| `frogcus-logo.png` | Replace the mascot / logo image |
| Timer mode buttons + JS logic | Add or rename timer modes and default durations |
| Achievements section | Add new milestone badges and unlock conditions |

---

## Deploying Your Own Version

1. Fork or clone this repository
2. Swap the logo, background videos, and colour palette in `index.html`
3. Deploy instantly for free on [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/)
4. Open the link and start your first session

---

## Roadmap / Ideas

- [ ] Persist stats, streaks, and achievements across sessions
- [ ] Add sound alerts / notifications on session end
- [ ] Export session history as CSV
- [ ] Add more ambient background scenes beyond the pond
- [ ] Shareable focus-session leaderboard

---

<div align="center">

*Hop in, tune out, focus up.*

[frogcus.vercel.app](https://frogcus.vercel.app/)

</div>
