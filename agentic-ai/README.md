# Agentic AI, explained

**Open it:** <https://pikooli.github.io/slide/agentic-ai/>

A short presentation (9 slides) on what an agentic AI is: an agent that **makes its own decisions**, uses **tools** on the front end, the back end or both, **updates the view and the data**, and reaches **outside services** (email, SMS, platform APIs) through the **MCP** standard. Each slide comes with a small stop-motion film.

## Slides

1. **Title**: the agent gets a goal, thinks, then uses UI, data, email and SMS tools to reach it.
2. **Chatbot vs agent**: both get the same request at the same time; the chatbot lists plumbers, the agent books one and sends an SMS.
3. **Its own decisions**: the observe → decide → act → check loop, run twice until the goal is reached. The four steps light up in sync with the film.
4. **Its tools**: front-end tools (update the view, ask through a form, confirm) and back-end tools (query DB, call API, run code).
5. **Front end**: the agent drives the app: it opens a form to ask the user for a time slot, shows a confirmation window, then updates the list.
6. **Back end**: the agent updates the database and calls an internal API.
7. **Outside services**: email, SMS and platform APIs, all plugged in through MCP.
8. **Full example**: "arrange the plumber's visit", from the customer's message to "goal reached". The six steps light up in sync with the film.
9. **Key takeaway**, with a link to the [MCP presentation](../mcp/).

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

- Same engine as the other presentations: everything is in this single `index.html` (films drawn on a canvas, music generated with the Web Audio API, no media files). The music is its own: soft electro arpeggios.
- Browsers block sound until the first click or key press, so the music may only start then.
