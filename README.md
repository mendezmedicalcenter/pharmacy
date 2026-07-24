# Mendez Pharmacy — Daily Log

Standalone Pharmacy Daily Log for Mendez Medical Center.

- **Single file, no build step.** Everything lives in `index.html` (HTML + CSS + vanilla JS).
- **Installable PWA** — "Add to Home Screen" via `manifest.json` + `logo.png`.
- **Offline / local.** Patient rows are stored per day in the browser's `localStorage`
  (key `mmc-pharm-dailylog-<YYYY-MM-DD>`). No server or account required.

## Features
Add patients, TECH sign-in, status workflow (Waiting → In Progress → Ready → Completed,
with back-one-step and No Show / Left), auto-filled employee, live wait timer, wait-time
status board, Rx / debit / cash entry with automatic payment posting, daily totals,
date picker to review past days, full-screen presentation mode, and print.

## Run
Open `index.html` in a browser, or serve the folder statically (e.g. Vercel / any static host).

> The Daily Log was moved here out of the `mendez-training` app so the pharmacy system
> and the training modules live in separate repos.
