# TeritipDB — Documentation Website

Official documentation site for **TeritipDB** — a JSON-based document database engine.

Live site: **https://teritipdb.github.io/website/**

## What is TeritipDB?

TeritipDB is a database engine that stores data in its own internal storage. Clients simply send plain **JSON over HTTP** — no SQL to write. You describe *what* you want as data; the engine handles the rest.

- **JSON-based** — clients send JSON, not SQL queries
- **Portable** — a single data file, works across operating systems
- **Schema-free** — tables and columns are created automatically
- **One-command install** — `npm create teritip-app@latest`

The documentation site is written in Indonesian with an English toggle.

## Site sections

- **Pengantar** — introduction to TeritipDB, the JSON-to-engine flow, installation, and supported targets
- **Sintaks** — every JSON operation: `insert`, `update`, `delete`, `select`, `join`, `tx`, `where`, and aggregates
- **Server & Hosting** — where it can run (PC, Windows/WSL, Linux, macOS, VPS, Docker, panel) and what it cannot
- **Keterbatasan** — structural, security, and completeness limitations
- **Tools & help** — AI-assisted install prompt, official clients (Python, JavaScript/Node, PHP), and HTTP API / WebSocket for developers building their own UI

## Tech

A static documentation site — plain **HTML + CSS** with a single `index.html`, no build step and no dependencies.

## Running locally

Open `index.html` directly, or serve the folder with any static server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Project structure

```
index.html   Documentation page
logo.png     Brand logo
```

## Related

- **NXDOM** — the organization behind TeritipDB: https://iyanrsaleh.github.io/nxdom/

## Sponsor

TeritipDB is developed in the open and free to use. If you or your organization would like to support the work, see [GitHub Sponsors](https://github.com/sponsors/iyanrsaleh).

## License

Released under the [MIT License](LICENSE).
