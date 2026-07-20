# palette.

A minimalist color palette tool. Paste a hex code, an RGB/HSL value, or a color name, and get a full palette back — big, rounded, shareable.

**Live site:** [gitwingo.github.io/palette](https://gitwingo.github.io/palette)

## Features

- **Paste anything** — hex, `rgb()`, `hsl()`, or plain color names, one or several at once
- **Auto-generated harmonies** — drop in one color and it builds a full palette around it, picking randomly from analogous, complementary, split-complementary, triadic, tetradic, and monochrome schemes so results stay varied instead of one fixed "vibe"
- **1,566 curated color names** — every swatch is matched to the closest named color from a hand-picked list, not the usual generic CSS 140
- **Lock, shuffle, reorder** — lock swatches you like, shuffle the rest, drag to reorder
- **3–8 colors**, resizable on the fly
- **HEX / RGB / HSL toggle** for the whole palette at once
- **Contrast checker** — pick any two swatches to see their WCAG contrast ratio and AA/AAA pass/fail
- **Light and dark mode**
- **Save palettes** with a title, right in the browser — revisit or delete them anytime
- **Export**
  - Copy as CSS variables, SCSS variables, a Tailwind config snippet, or raw JSON
  - Download a high-resolution (3000×3000) shareable PNG/JPG card of the current palette
  - Export all saved palettes as one JSON file, or as a zip of PNG cards

Nothing is sent anywhere — colors and saved palettes live entirely in your own browser.

## Tech

Plain HTML, CSS, and JavaScript. No build step. Uses:
- [chroma.js](https://gka.github.io/chroma.js/) for color math
- [JSZip](https://stuk.github.io/jszip/) for bundling bulk PNG exports
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) for type

## Running locally

Just open `index.html` in a browser — there's no build step or server required.

```bash
git clone https://github.com/gitwingo/palette.git
cd palette
open index.html   # or just double-click it
```


---

Built by [gitwingo](https://github.com/gitwingo)
