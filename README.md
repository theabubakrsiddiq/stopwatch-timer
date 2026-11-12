# Stopwatch Timer

A minimal, stopwatch-style countdown timer that runs in the browser. Set 30 seconds or 15 minutes, then **pop it out** so it floats above your slides, video calls, or any other window.

- Presets (15s to 30m) and custom minutes/seconds
- Ring that drains as time runs out, with amber and red warnings, plus a beep at zero
- Pop-out always-on-top window (Chrome / Edge, via the Document Picture-in-Picture API; display-only fallback in Safari)
- Share a preset with a link: `?t=90` (seconds) or `?m=5` (minutes)
- Keyboard: **Space** start/pause, **R** reset
- One file, no dependencies, no tracking, no sign-up

## Run locally
Open `index.html` in Chrome.

## Deploy (GitHub Pages)
1. Create a new public repo and upload `index.html` (and this README).
2. Repo **Settings > Pages > Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)`.
3. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.

## License
MIT
