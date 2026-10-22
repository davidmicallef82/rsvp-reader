# RSVP Speed Reader

A self-contained speed reading tool that runs entirely in the browser — no install, no dependencies, just open the HTML file.

Built by [David Micallef](https://davemicallef.com) / [Tyrannosoft](https://tyrannosoft.com.au).

---

## What is RSVP?

Rapid Serial Visual Presentation (RSVP) flashes one word at a time at a fixed focal point, eliminating the eye movements that consume most of your reading time. Words are aligned to their **Optimal Recognition Point (ORP)** — the character your brain locks onto first — so you can read faster with less effort.

## Features

- **Adjustable speed** — 150 to 900 WPM via slider or `↑` / `↓` keys
- **Smart punctuation pauses** — automatically slows on periods, commas, and long words
- **Fetch article from URL** — paste any article URL and extract the text automatically
- **Fullscreen mode** — distraction-free reading with massive word display
- **Zoom in/out** — adjust word size in fullscreen with `+` / `-` keys or on-screen buttons
- **Progress bar** — click to jump to any point in the text
- **Keyboard shortcuts** — full control without touching the mouse

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `←` / `→` | Step one word |
| `↑` / `↓` | Speed up / slow down |
| `R` | Reset to start |
| `F` | Toggle fullscreen |
| `+` / `-` | Zoom in / out (fullscreen only) |

## URL Fetching

Paste an article URL into the **Fetch Article from URL** field and hit **Fetch**. The reader extracts the article text using [Mozilla Readability](https://github.com/mozilla/readability) (the same engine as Firefox Reader Mode) via a CORS proxy.

Works best with blog posts, Substack articles, and editorial content. Major corporate sites and paywalled content may not be accessible.

> **Note:** Open the file via a local server (e.g. VS Code Live Server) rather than directly from the filesystem for URL fetching to work correctly.

## Usage

1. Clone or download the repo
2. Open `RSVP Reader.html` in any modern browser
3. Paste your text into the **Source Text** box, or fetch an article by URL
4. Hit **Play** or press `Space`

## License

MIT © 2026 David Micallef / Tyrannosoft
