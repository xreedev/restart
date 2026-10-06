# Robotics Path

A self-contained, 6-month / 120-module robotics engineering learning platform, adapted from
[How to Become a Robotics Engineer](https://technologiee.substack.com/p/how-to-become-a-robotics-engineer).

## Use it

Open `index.html` in a browser, or serve the folder (for example GitHub Pages, or `python3 -m http.server`).
No build step, no dependencies, no server.

## Features

- 24 weeks × 5 day-modules (4 learning days + 1 build day). Finish as many per day as you like.
- Dashboard: progress ring, pace tracking, streaks, activity heatmap, "Up next".
- Roadmap by month and week, with a hardware shopping checklist per month.
- Per module: task checklist, resources, study timer, Markdown notes with preview, file uploads, your own links.
- Notebook for free-form notes, file library, `Ctrl+K` search, dark mode, mobile layout.
- JSON backup and restore, including uploaded files.

## Data and privacy

Progress and notes are stored in your browser (localStorage); uploaded files in IndexedDB.
Nothing leaves your machine. Clearing site data erases it, so use **Settings → Export backup** regularly.

## Editing the curriculum

All content lives in `curriculum.js`. Each module is `[title, goal, [tasks], [resources], hours]`.
A resource is `"Label|https://url"` for a direct link, or just `"Label"` to open a web search.
Hardware prices come from the source article (Sept 2026) and may have changed.
