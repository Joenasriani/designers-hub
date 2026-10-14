# Designers Hub

A browser-based directory for discovering and organizing links to design resources and creative tools.

## Features visible in the deployed bundle

- Search and filter a curated list of external design resources.
- View resource descriptions, categories, and quick-view details.
- Open resource websites in a new tab.
- Mark resources as favorites or save them for later.
- Rate and tag listed resources within the interface.
- Switch display preferences and use quick navigation controls.

## Repository contents

This repository contains a **built website**, not its original editable React source project:

- `index.html` loads the compiled JavaScript and CSS.
- `assets/index-48dc77e5.js` contains the minified application bundle.
- `assets/index-c41f8a83.css` contains compiled styles.

The bundle uses React. There is no `package.json`, source directory, or build configuration here, so `npm install` and `npm run dev` are not supported from this repository alone.

## Running locally

Serve the repository directory with a static HTTP server and open its local URL. The root HTML references the `/assets/` directory using absolute paths, so the site should be served from the server root unless those paths are adjusted.

## Limitations

- The source project and dependency manifest are not included.
- Resource URLs and third-party content may change independently.
- No user authentication or backend service was identified in the inspected bundle.
- A build, production deployment check, and end-to-end functionality tests were not performed.
- A built bundle alone is not sufficient to verify the origin and licensing of every bundled dependency.

Credit: Joe Nasr

Portfolio: https://joe-nasr-signals.vercel.app/
