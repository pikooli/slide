# Slides

HTML presentations in French and English, available online via GitHub Pages.

| Presentation | Link | File |
|---|---|---|
| **MCP explained with a phone directory**: what an MCP is, illustrated with small stop-motion films (with music). | [Open](https://pikooli.github.io/slide/content/mcp.html) | [`content/mcp.html`](content/mcp.html) |
| **The FAQ powered by Notion** (Hiway): how the FAQ goes from Notion straight into the app. | [Open](https://pikooli.github.io/slide/content/notion-support.html) | [`content/notion-support.html`](content/notion-support.html) |

Home page listing all presentations: <https://pikooli.github.io/slide/> ([`index.html`](index.html)).

## Navigating a presentation

- **← / →** or **Space**: previous / next slide
- **F**: fullscreen
- **M**: mute / unmute the music (MCP presentation)
- **L** or the **FR / EN** button: switch language. You can also force it in the link with `?lang=en` or `?lang=fr`.

## Adding a presentation

1. Drop the `.html` file into `content/`.
2. Add a row to the table above with the link `https://pikooli.github.io/slide/content/<file>.html`, and add a card to `index.html`.
3. Commit and push to `main`: GitHub Pages updates within a minute or two.

## Enabling GitHub Pages (one time)

On GitHub: **Settings → Pages → Build and deployment**, choose *Deploy from a branch*, branch `main`, folder `/ (root)`.

Each file is self-contained (a single `.html`, no build step), so you can also open it directly in a browser.
