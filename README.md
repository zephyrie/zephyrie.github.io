# zephyrie.com

Personal site for **Michael Zephyr** — Technical Marketing Engineer Manager at NVIDIA Healthcare. Leads developer engagement and technical strategy across Holoscan, Isaac for Healthcare, MONAI, and the broader medical-AI portfolio (digital twins for hospitals, Cosmos, VSS).

## Stack

Static HTML + hand-written CSS. No build step, no framework, no JS runtime.

- `index.html` — the page
- `styles.css` — design tokens, layout, type system
- `assets/images/profile.jpg` — portrait
- Type: **Antonio** (display) + **Geist Mono** (body) via Google Fonts
- Theming: `light-dark()` + `prefers-color-scheme`, with `forced-colors` fallback
- Hosting: GitHub Pages (custom domain via `CNAME`)

## Local dev

```bash
npm install
npm run dev
```

Serves at `http://0.0.0.0:3000` so you can review on any device on your LAN.

To regenerate favicons from `mz-logo.svg`:

```bash
npm run favicons
```

## Contact

- GitHub: [@zephyrie](https://github.com/zephyrie)
- LinkedIn: [michaelzephyr](https://linkedin.com/in/michaelzephyr)
