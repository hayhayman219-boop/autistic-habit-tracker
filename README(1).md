# Autistic Habit Tracker

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A calm, sensory-friendly habit tracker built for people with autism — with full control over your own habits and rewards.

## What it does

- **Daily habits** — a simple checklist you can customize. Tap to mark a habit done, tap again to undo. Add or delete habits anytime.
- **Points & token jar** — each completed habit earns points, and a jar on screen fills up visually as they add up, so progress is easy to see at a glance.
- **Custom rewards system** — type in your own rewards, whatever you're working toward (a snack, screen time, an outing, anything), and set how many points each one costs. Redeem a reward once you've earned enough points.
- **Recently redeemed log** — keeps a short history of what you've earned.

## Why it's designed this way

This app is built around sensory-sensitive, autonomy-first design:

- **Atkinson Hyperlegible font** for easier reading
- **Soft, muted colors** — no harsh contrast or jarring visuals
- **No flashing or sudden animation**, and full support for `prefers-reduced-motion`
- **Large touch targets** for easier, more forgiving interaction
- **User-defined habits and rewards** — nothing is prescribed; you decide what counts as a habit and what you're working toward

## Using it

Open `autism-habit-tracker.html` in any web browser — no install, no account, no internet connection required. All progress is saved automatically in the browser (`localStorage`), so your data will still be there the next time you open it on the same device and browser.

> **Note:** Because data is stored locally in the browser, it won't automatically sync across different devices or browsers.

## Security checks

This repo runs an automated security scan every day at 2:00 AM EST via GitHub Actions (`.github/workflows/security-check.yml`), using:
- **CodeQL** to catch vulnerability patterns like cross-site scripting (XSS)
- **Gitleaks** to catch accidentally committed secrets or credentials

Results show up under this repo's **Actions** and **Security** tabs, and you'll get an email notification if a scan finds something.

## Project status

Actively maintained. Planned/possible next steps:
- Fix known XSS risk from unescaped user input in habit/reward names
- Optional cross-device sync

## Contributing

Contributions are welcome, especially from autistic people, caregivers, and accessibility-focused developers. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines before opening a pull request.

## License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and share.
