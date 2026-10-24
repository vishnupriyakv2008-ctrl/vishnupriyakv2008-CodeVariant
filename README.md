# The Project Graveyard

A responsive, local-first archive for unfinished projects. The site is built as a single HTML file with embedded CSS and JavaScript, so it does not require a package manager, build step, backend, or API keys.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

Project records are stored in that browser's `localStorage`. They remain on the same browser and device unless you export a backup. Use the app's JSON export and import features to back up or restore your archive.

## Features

- Create, edit, search, filter, and delete project records
- Track project goals, status, causes, tags, progress, completed work, and unfinished work
- Built-in example projects
- Local browser storage
- JSON archive export and import
- Salvage notes and adoption listings
- Revival prompts, timeline views, and a focus timer
- Drag-and-drop action zones, with keyboard alternatives
- Responsive layout and reduced-motion support

## Files

- `index.html` — the complete application: HTML, CSS, and JavaScript
- `README.md` — setup and project information
- `LICENSE` — Apache License 2.0

No other files or dependencies are needed to run the app locally.

## Hosting

The app now uses the standard `index.html` filename, so static hosting services such as GitHub Pages can detect it as the homepage entry point.

## Privacy

The app is designed to store project data locally in your browser and does not require a server or external database. Exported backups are files you choose to download or share.

## License

Licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for the full license text.
