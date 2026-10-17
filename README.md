# Life Dashboard: Demo

**Live demo:** https://benno23.github.io/Life-OS/ (English) · [Deutsch](https://benno23.github.io/Life-OS/de/)

A personal "life operating system" in a single web page. It brings sleep, recovery, training, nutrition, habits, goals, time tracking and career planning into one view, and it looks for patterns across them.

This repository contains a **demo with fictional data**. The person in it ("Alex") and every value are made up. The data is regenerated relative to today's date each time the page loads, so it never looks stale. Inputs work but are not saved.

## What it does

- **Home:** daily status, a recovery score based on HRV, resting heart rate and sleep, habits, weekly focus, goals and trends.
- **Body:** recovery, gut health log, nutrition log (macros and fibre) and caffeine, guided training and mobility sessions, sleep, and lab and body composition values.
- **Mind:** Nerve Reset (short regulation exercises), a meditation timer and binaural beats generated in the browser.
- **Insights:** statistical tests across all data (for example, "late caffeine → lower HRV"), shown as robust, trend or no effect.
- **Organization:** tasks, notebook, reading list, a career path with milestones, and net worth.

## How the real version works

The personal version runs as a Claude artifact and reads and writes Notion databases through connectors (Notion, Google Calendar, and Google Drive for an hourly Health Connect export of the smartwatch data). Meals are logged as free text and Claude estimates calories, macros and fibre. It was built iteratively in almost 200 small steps, each change tested and logged.

This demo replaces that data layer with a local generator and has no backend, tracking or connections. The AI features (meal estimates, "Ask your data", journal reading) need Claude and are switched off here.

*Last updated: 17 October 2026.*

## Feedback and ideas

Ideas for new features or improvements are very welcome. Please open an [issue](https://github.com/benno23/Life-OS/issues/new).
