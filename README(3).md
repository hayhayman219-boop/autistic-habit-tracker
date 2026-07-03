# Autistic Habit Tracker

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A calm, sensory-friendly habit tracker built for people with autism — with full control over your own habits and rewards.

**[Try it live →](https://yourusername.github.io/autism-habit-tracker/autism-habit-tracker.html)** *(update this link once GitHub Pages is enabled — see Setup below)*

<p>
  <img src="screenshots/screenshot-1-overview.png" alt="Habit tracker overview showing the token jar and today's habits" width="45%">
  <img src="screenshots/screenshot-2-rewards.png" alt="Habit tracker showing custom rewards and progress toward them" width="45%">
</p>

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

## Setup: enabling the live demo link

To make the "Try it live" link above work with your own copy of this repo:
1. Go to **Settings → Pages** in your repo.
2. Under "Build and deployment," set **Source** to **Deploy from a branch**.
3. Set **Branch** to `main`, folder to `/ (root)`, then **Save**.
4. GitHub will give you a live URL after a minute or two — update the link at the top of this README with it.

## Security checks

This repo runs an automated security scan every day at 2:00 AM EST via GitHub Actions (`.github/workflows/security-check.yml`), using:
- **CodeQL** to catch vulnerability patterns like cross-site scripting (XSS)
- **Gitleaks** to catch accidentally committed secrets or credentials

Results show up under this repo's **Actions** and **Security** tabs, and you'll get an email notification if a scan finds something.

## Project status

Actively maintained. Planned/possible next steps:
- Optional cross-device sync

## Contributing

Contributions are welcome, especially from autistic people, caregivers, and accessibility-focused developers. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines before opening a pull request.

## License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and share.
