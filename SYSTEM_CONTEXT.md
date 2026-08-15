# 🌐 Showcase — System Context
**Last Updated:** 2026-05-27
**Type:** Static GitHub Pages Portfolio Site

---

## Purpose
The public-facing portfolio and product showcase site for all projects. Hosted on GitHub Pages. Contains individual showcase pages for each product with feature highlights, screenshots, and download links.

---

## Tech Stack
- **Hosting:** GitHub Pages (CNAME configured)
- **Frontend:** Vanilla HTML / CSS / JS
- **No build step** — static files served directly

---

## Key Files
| File | Purpose |
|---|---|
| `index.html` | Main portfolio landing page |
| `style.css` | Shared design system |
| `vibe-flow.js` | Shared JS utilities |
| `commanddeck-showcase.html` | CommandDeck product page |
| `ezops-showcase.html` | EzOps product page |
| `flighttracker-showcase.html` | FlightTracker product page |
| `gitsnap-showcase.html` | Gitsnap product page |
| `homeasset-showcase.html` | HomeAsset product page |
| `iowake-showcase.html` | IOWake Discipline Alarm product page |
| `jobboard-showcase.html` | JobBoard Tracker product page |
| `odysseus-showcase.html` | Odysseus AI Workspace product page |
| `piccompare-showcase.html` | PicCompare (Duplicate Image Detective) product page |
| `relayit-showcase.html` | RelayIT Tech Support Ticketing product page |
| `screensaver-showcase.html` | Matrix ScreenSaver product page |
| `spriteslicer-showcase.html` | SpriteSlicer product page |
| `storyreader-showcase.html` | StoryReader AI product page |
| `terminalbuddy-showcase.html` | TerminalBuddy product page |
| `vidsimp-showcase.html` | VidSimp product page |
| `CNAME` | Custom domain config for GitHub Pages |

---

## Notes
- Each showcase page is a self-contained product landing page
- Assets (screenshots, icons) live in `assets/`
- To add a new project: create `<projectname>-showcase.html` and link from `index.html`
