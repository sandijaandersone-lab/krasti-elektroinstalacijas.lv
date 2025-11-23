# krasti-elektroinstalacijas.lv

This repository contains the source and static site files for krasti-elektroinstalacijas.lv.

Minimal files added to make the repo deployable on Netlify:
- `netlify.toml` — Netlify build and publish config (publishes `public/`).
- `public/index.html` — placeholder site index (replace with your real content).
- `public/_redirects` — redirect all routes to index (useful for SPAs).

If your site requires a build step (Hugo, Jekyll, Gatsby, etc.), add the appropriate build files (e.g., `package.json`, generator config). Update `netlify.toml` to set the correct `command` and `publish` folder.
