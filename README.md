# Picture Book Captioner

A tiny, beautiful tool for adding **storybook-style caption panels** to your images — the rounded text box you see at the bottom of graded-reader / Oxford-Reading-Tree pages.

**▶ Live app: https://hejun-coderlife.github.io/picture-book-captioner/**

It runs entirely in your browser. **Your images are never uploaded, nothing touches a server, and it costs nothing** — no account, no API key, no tokens. Make as many books as you like, for free.

## Why

AI image generators can draw the pictures, but **putting your own text onto them is just image editing — it should never cost anything.** This tool does that step for free, so the only thing you ever pay for is generating the art itself.

## Features

- **Drag in one or many images** and caption each page.
- Live preview that renders at the image's **full resolution** (downloads are crisp, not downscaled).
- Tasteful default panel — cream rounded box, thin gold border, centered serif text, optional page number — and you can tweak everything:
  - font, size, line spacing
  - bottom / side margins, inner padding, corner radius, opacity
  - text / panel / border colors, border on-off
  - center or left align
  - automatic page numbers (bottom-right, in import order)
- **English and CJK text both wrap automatically.**
- **Download this page** or **Download all** (exports `page1.png`, `page2.png`, …).

## How to use

1. Open the [live app](https://hejun-coderlife.github.io/picture-book-captioner/) — or download `index.html` and open it locally (it works offline too).
2. Drag your image(s) into the drop zone.
3. Select a page, type its text (one line per sentence; long lines wrap on their own).
4. Adjust the layout sliders until it looks right — settings apply to every page.
5. Click **Download this page** or **Download all**.

## Tech

A single self-contained `index.html` — no build step, no dependencies, no framework. Plain HTML, CSS, and the Canvas API. Hosted on GitHub Pages; Fraunces + Hanken Grotesk load from Google Fonts with system-serif fallbacks for offline use.

## License

MIT — free to use, modify, and share.
