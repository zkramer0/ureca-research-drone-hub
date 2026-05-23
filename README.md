# URECA Research Hub

**Autonomous Multi-Drone Grid Monitoring System — Component Research Tool**

A real-time collaborative web app for the URECA Summer 2026 research team to evaluate and compare hardware components for a four-drone wildfire detection system.

## What This Does

The team is building four autonomous quadcopters that patrol a 4×3 GPS waypoint grid, capturing visible and thermal imagery to detect spreading wildfires. This tool lets all four team members research, log, compare, and vote on components across nine hardware categories:

- Flight Controllers
- Companion Computers
- GPS Modules
- Motors & ESCs
- Frames
- Batteries
- Cameras
- Thermal Sensors
- Telemetry Radios

## Features

- **Real-time sync** — powered by Firebase Realtime Database; changes appear on all screens within 1–2 seconds
- **Component cards** — log specs, source links, notes, and status (Researching → Candidate → Selected → Rejected)
- **Compare mode** — side-by-side spec table for candidates in each category
- **Voting** — team members upvote preferred components
- **Activity feed** — chronological log of who added or updated what
- **Connection status** — live indicator showing sync state
- **Mobile responsive** — works on phones and tablets

## Setup

This app runs as a single HTML file hosted on GitHub Pages with Firebase Realtime Database for shared storage.

### Prerequisites

- A Firebase project with Realtime Database enabled (free Spark plan)
- The `firebaseConfig` values pasted into `index.html`

### Deployment

1. Clone this repo
2. Open `index.html` and verify the `firebaseConfig` block contains valid values
3. Push to GitHub and enable GitHub Pages (Settings → Pages → Deploy from branch → `main`)
4. Share the GitHub Pages URL with the team

## Tech Stack

- Vanilla HTML/CSS/JavaScript (no build tools, no frameworks)
- Firebase Realtime Database (free tier)
- GitHub Pages (free hosting)

## License

Internal project — Stony Brook University URECA Program, Summer 2026.
