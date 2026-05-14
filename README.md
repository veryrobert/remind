# Remind

A single-page personal reminder app showing two daily at-a-glance screens, swipeable via a horizontal carousel.

## Screens

**Bins** — Shows the next bin collection day and type (Refuse / Recycling + Organic) based on the 2026 Tuesday schedule, with holiday shift support. Tap "Calendar" for a full-year colour-coded view.

**College** — Shows the next in-person college session (module name and date) or a countdown. Tap "Calendar" for a Jan–Aug 2026 overview of all sessions.

## How it works

- Pure HTML/CSS/JS, no build step, no dependencies
- All schedule data is hardcoded in `index.html` — update `TUESDAYS`, `HOLIDAY_SHIFTS`, and `SESSIONS` to change the schedule
- Refreshes every 60 seconds
- Designed for mobile (safe-area insets, scroll-snap carousel, no scrollbar)

## Usage

Open `index.html` directly in a browser, or serve from any static host.
