# Life Dashboard: Demo

**Live demo:** https://benno23.github.io/Life-OS/ (English) · [Deutsch](https://benno23.github.io/Life-OS/de/)

A personal "life operating system" in a single web page. It brings sleep, recovery, training, nutrition, habits, goals, time tracking and career planning into one view, and it looks for patterns across them.

This repository contains a **demo with fictional data**. The person in it ("Alex") and every value are made up. The data is regenerated relative to today's date each time the page loads, so it never looks stale. Inputs work but are not saved.

## What it does

- **Today:** morning and evening check-in, a recovery score based on HRV, resting heart rate and sleep, today's focus, habits and appointments.
- **Body:** an adaptive training plan with a readiness traffic light, guided training and mobility sessions, nutrition log (macros and fibre), gut health log, caffeine, recovery and sleep, and body composition.
- **Mind:** journal, structured thinking, Nerve Reset (short regulation exercises), a meditation timer with binaural beats generated in the browser, and a weekly plan.
- **Review:** weekly reflection and analyses, habits, goals, and patterns: statistical tests across all data (for example, "late caffeine → lower HRV"), shown as robust, trend or no effect.
- **More:** tasks, notebook, reading list with a weekly page goal, time tracking, lab values, net worth, and a career path with milestones.

## How the real version works

The personal version runs as a Claude artifact and reads and writes Notion databases through connectors (Notion, Google Calendar, Google Drive for a spreadsheet export of the smartwatch data, and Gmail for the watch's workout backup e-mails). Meals are logged as free text and Claude estimates calories, macros and fibre. It was built iteratively in more than 260 small steps, each change tested and logged.

This demo replaces that data layer with a local generator and has no backend, tracking or connections. The AI features (meal estimates, "Ask your data", journal reading) need Claude and are switched off here.

*Last updated: 24 November 2026.*

## Feedback and ideas

Ideas for new features or improvements are very welcome. Please open an [issue](https://github.com/benno23/Life-OS/issues/new).
