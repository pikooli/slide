# The FAQ powered by Notion

**Open it:** <https://pikooli.github.io/slide/notion-support/>

An internal Hiway presentation (7 slides) about publishing help articles straight from Notion into the app, with no development step. Each slide comes with a small stop-motion film.

## Slides

1. **Cover**: an article is written in Notion, switched to *Published*, and lands in the app.
2. **Where we started**: support writes, the ticket goes to a developer, back-and-forth, and days later it's finally live.
3. **The solution**: support writes in Notion, flips the status, the article is live in the app within minutes. The three steps light up in sync with the film.
4. **Three immediate wins**: 0 lines of code, faster releases, same tool.
5. **Boosted by AI**: a prompt to Claude & Codex, the article gets written, formatted and published.
6. **The leverage effect**: every team reads the shared knowledge base; only owners can edit it.
7. **Before / Now**: the impact in short.

## Controls

| Key / control | Action |
|---|---|
| ← / → or Space | Previous / next slide |
| Click on a film | Pause / play |
| Bar under a film | Scrub back or forward |
| F | Fullscreen |
| M or 🔊 button | Mute / unmute the music |
| Hover 🔊 | Volume slider |
| L or FR / EN button | Switch language |

Slides are in French or English (follows the browser language, remembers the last choice, or force it with `?lang=en` / `?lang=fr`). The films are always in English.

## Notes

- Built on the same engine as the [MCP presentation](../mcp/): everything is in this single `index.html` (films drawn on a canvas, music generated with the Web Audio API, no media files).
- Browsers block sound until the first click or key press, so the music may only start then.
