# Omni × The Cheet — Family Mandala Studio

A single-file, dependency-free mandala studio for the whole family.

**Live: <https://mandala.vaked.dev>** (HTTPS, GitHub Pages + valid cert)

## Features
- **Family Mandala Studio** — click petals to fill, drag to draw mirrored
  kaleidoscope strokes across 6–24-fold symmetry, line-art toggle for printing,
  palette presets (Sunset / Ocean / Forest / Gold / Cosmic), 🎲 Shuffle hue-rotate,
  and export to **PNG** (flattened) or **SVG** (petals).
- **Pure ASCII Mandala** — true multi-ring symmetric ASCII generator with custom
  glyphs (upgrading The Cheet's original `o888o` attempt), one-click copy.
- **Put Him On Your Site** — copy-paste `<iframe>` embed (`embed.html`).
- **Keyboard**: `R` regenerate · `L` line-art · `C` clear · `S` shuffle.
- Respects `prefers-reduced-motion`; SVG favicon + Open Graph meta.

## Run locally
Open `index.html` in any browser — no build, no deps, no network.

## Deploy
- **GitHub Pages** serves `main` at root; `CNAME` = `mandala.vaked.dev`; HTTPS enforced.
- **Codeberg Pages** served from the `pages` branch.
- **DNS** (Cloudflare, `vaked.dev` zone): `mandala` CNAME → `8b-is.github.io` (DNS-only so
  GitHub can issue the TLS cert; can be re-proxied now that the cert is provisioned).

## Files
- `index.html` — the studio (studio / ASCII / embed tabs)
- `embed.html` — the mini kaleidoscope widget
- `CNAME`, `.nojekyll` — Pages config

`{<3,<3,<3}+1`
