# Rayed's SAT Sprint Dashboard

Live: **https://riasali-sudo.github.io/sat-sprint/**

A single-file, mobile-first, gamified dashboard for a 14-day SAT prep sprint (Sun May 24 → Sat June 6, 2026).

## What it does

- **Today card** with one-tap AM + PM checkboxes (2.5 hr each = 5 hr/day)
- **Streak counter** with confetti at Day 3 / 6 / 8 / 10 / 13 milestones
- **Topic mastery tiers** (🥉 Apprentice → 🥈 Practitioner → 🥇 Expert → 💎 Master) for PS&DA + Geo/Trig sub-topics
- **Personal Best leaderboard** for practice tests + sparkline of math trajectory
- **Tutor session tracker** (4 × 2-hr blocks scheduled with Prep Expert)
- **NOLA travel banner** auto-shows Days 6–9 (TPA→MSY → MSY→TPA)
- **Pre-test checklist** auto-shows Days 13–14
- **Optional sync** via a Google Apps Script Web App backend (state shared across all viewers' devices)

## How it works

- Single self-contained HTML file (~62 KB)
- Vanilla JS + Tailwind CSS (CDN) + canvas-confetti (CDN)
- State persisted in browser localStorage on each device
- Optional shared state via Google Apps Script backend (pasted into the in-app sync chip)

## Privacy

The published file contains no addresses, phone numbers, financial details, passwords, or sensitive identifiers — only a first name, a public test date, and a study schedule.

## Tech

| | |
|---|---|
| Hosting | GitHub Pages (free, FOSS-aligned) |
| Frontend | Vanilla JS, Tailwind via CDN, canvas-confetti via CDN |
| State | localStorage (default), optional Apps Script + Google Sheet sync |
| Cost | $0 |

## License

Personal use. Schedule + design tailored to one student's June 6, 2026 SAT cycle.
