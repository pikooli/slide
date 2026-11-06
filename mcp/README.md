# MCP explained with a phone directory

**Open it:** <https://pikooli.github.io/slide/mcp/>

A short presentation (9 slides) that explains what an MCP (Model Context Protocol) is, using a simple example: you have a leak and need a plumber. Each slide comes with a small stop-motion film.

The key idea: **the MCP server is the AI's phone directory**. It lists which tools exist, how to call them (the input contract) and what they will answer (the response format).

## Slides

1. **Title**: an AI opens the directory and finds a plumber.
2. **The problem**: the AI can talk, but it can't reach the directory.
3. **Before MCP**: one custom connector per AI × service pair (3 × 3 = 9).
4. **The solution**: one standard directory format, so any AI can read any service (3 + 3 = 6).
5. **Who does what**: Host (the app), MCP client (looks things up), MCP server (the directory).
6. **A directory entry**: name, description, input contract, response format.
7. **In action**: "find me a plumber for tonight", step by step.
8. **Under the hood**: what the tool and its entry look like in code (simplified).
9. **Key takeaway**.

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

- Everything is in this single `index.html`: the films are drawn frame by frame on a canvas, and the music is generated live with the Web Audio API. There are no image, video or audio files.
- Browsers block sound until the first click or key press, so the music may only start then.
