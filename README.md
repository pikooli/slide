# Slides

HTML presentations in French and English, available online via GitHub Pages.

| Presentation | Link | Folder |
|---|---|---|
| **MCP explained with a phone directory**: what an MCP is, illustrated with small stop-motion films (with music). | [Open](https://pikooli.github.io/slide/mcp/) | [`mcp/`](mcp/) |
| **The FAQ powered by Notion** (Hiway): how the FAQ goes from Notion straight into the app, with stop-motion films. | [Open](https://pikooli.github.io/slide/notion-support/) | [`notion-support/`](notion-support/) |

Home page listing all presentations: <https://pikooli.github.io/slide/> ([`index.html`](index.html)).

## Structure

```
index.html              home page
mcp/
  index.html            the presentation
  README.md             what it covers, controls, notes
notion-support/
  index.html
  README.md
```

## Navigating a presentation

- **← / →** or **Space**: previous / next slide
- **F**: fullscreen
- **L** or the **FR / EN** button: switch language. You can also force it in the link with `?lang=en` or `?lang=fr`.

Each presentation's README lists its own extra controls.

## Adding a presentation

1. Create a folder, e.g. `my-talk/`, with the presentation as `index.html` and a `README.md` next to it.
2. Add a row to the table above with the link `https://pikooli.github.io/slide/my-talk/`, and add a card to `index.html`.
3. Commit and push to `main`: GitHub Pages updates within a minute or two.

## Enabling GitHub Pages (one time)

On GitHub: **Settings → Pages → Build and deployment**, choose *Deploy from a branch*, branch `main`, folder `/ (root)`.

## Author

Pascal Zhang · [zhangpas@gmail.com](mailto:zhangpas@gmail.com) · [zhang-pascal.com](https://zhang-pascal.com/)

## Notes

Each presentation is self-contained (a single `index.html`, no build step), so you can also open it directly in a browser.
