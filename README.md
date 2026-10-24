# The Project Graveyard

A no-backend, local-first archive for abandoned projects. Built with plain HTML, CSS, and JavaScript—no Supabase, API keys, build step, or external database.

## Run it
- Open `index.html` directly in a browser, or enable GitHub Pages from **Settings → Pages** and deploy from the `main` branch.
- Project edits are saved in the browser's `localStorage`. They stay on that browser/device unless you export a backup.
- Use **Export JSON** to download an archive backup and **Import JSON** to restore one.

## Features
- Create, edit, search, filter, and delete projects
- Status, cause, tags, goals, completed/unfinished parts, and progress
- Local persistence and sample projects
- JSON archive export/import
- Revival prompts and a focused 30-minute timer
- Salvage notes for reusable ideas
- Reduced-motion-friendly responsive layout

## Files
- `index.html` — application UI and client-side behavior
- `data/sample-projects.json` — sample archive data
- `data/archive.schema.json` — documented JSON archive shape
- `package.json` — project metadata and local static-server command

## Privacy
All project data is stored locally in your browser. This repository does not contain your personal archive and the app sends no project data to a server.
