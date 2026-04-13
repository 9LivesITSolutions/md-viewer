# md-viewer

![HTML](https://img.shields.io/badge/HTML-single--file-orange?logo=html5)
![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)

A clean, self-contained Markdown editor and live preview — no build step, no server, no dependencies to install. Open `md-viewer.html` in any modern browser and start writing.

![md-viewer screenshot](https://github.com/user-attachments/assets/5d395cd6-a790-4e50-9139-9c0525b3b899)

---

## Features

- **Real-time preview** — rendered output updates on every keystroke
- **Drag & drop** — drop any `.md` / `.markdown` / `.txt` file onto the editor panel
- **Scroll sync** — editor and preview scroll in lockstep (toggle on/off)
- **Resizable panels** — drag the divider to adjust the editor/preview split (20 %–80 %)
- **Export PDF** — opens a clean print-ready page via the browser's print dialog
- **Copy HTML** — copies the generated HTML to the clipboard in one click
- **Syntax highlighting** — fenced code blocks rendered with highlight.js (GitHub theme)
- **GFM support** — tables, task lists, strikethrough, line breaks (marked.js v9)

---

## Usage

No installation required.

```bash
# Clone
git clone https://github.com/9LivesITSolutions/md-viewer.git
cd md-viewer

# Open
open md-viewer.html          # macOS
start md-viewer.html         # Windows
xdg-open md-viewer.html      # Linux
```

Or simply download `md-viewer.html` and open it directly in your browser.

---

## Keyboard shortcuts

| Action | Shortcut |
|--------|----------|
| Open file | Click **Open file** or drag & drop |
| Clear editor | Click **Clear** |
| Copy rendered HTML | Click **Copy HTML** |
| Export / Print PDF | Click **Export PDF** |
| Toggle scroll sync | Toggle switch in the header |

---

## Technical stack

| Component | Library / Source |
|-----------|-----------------|
| Markdown parser | [marked.js](https://marked.js.org/) v9.1.6 — GFM enabled |
| Syntax highlighting | [highlight.js](https://highlightjs.org/) v11.9.0 — GitHub theme |
| Fonts | Inter · Merriweather · Fira Code (Google Fonts) |
| Build | None — single standalone HTML file |

CDN resources are loaded from `cdnjs.cloudflare.com` and `fonts.googleapis.com`. The tool works offline if those assets are cached by the browser.

---

## Browser support

Works in all modern browsers: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+.

---

## License

MIT — see [LICENSE](LICENSE).

---

*9 Lives IT Solutions — Healthcare IT & Infrastructure Automation*
