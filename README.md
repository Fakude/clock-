# Moment

Moment is a browser-native time dashboard that expands the original broken digital-clock exercise into a polished, interactive project.

## Features

- Live local or selected world time using `Intl.DateTimeFormat`
- 12- and 24-hour display options
- Animated digital clock interface
- Stopwatch with start, pause and reset controls
- Configurable 25-, 45- or 60-minute focus timer
- Responsive design with no framework, build step or external runtime dependency

## Run

Open `index.html` in a modern browser.

The original files remain in `Flip-clock/` as the starting point for the project.

## Quality and deployment

[![Validate and deploy site](https://github.com/Fakude/clock-/actions/workflows/pages.yml/badge.svg)](https://github.com/Fakude/clock-/actions/workflows/pages.yml)

GitHub Actions checks `app.js` and any other browser JavaScript on pushes and pull requests. Successful pushes to `main` deploy to GitHub Pages. Main files: `index.html`, `style.css`, `app.js`, and `.github/workflows/pages.yml`.
