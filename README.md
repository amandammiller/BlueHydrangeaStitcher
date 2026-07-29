# Blue Hydrangea Stitcher

The link-in-bio site for [bluehydrangeastitcher.com](https://bluehydrangeastitcher.com) — Amanda Miller's needlepoint designs, stitch guides, photography, and knitting, all in one place for Instagram.

## What's here

A single static `index.html` page, no build step or dependencies:

- **Light/dark mode**, following system preference by default with a manual toggle that persists via `localStorage`
- **Decorative section cards** — each link group (Needlepoint, Everything else) is a card with a scalloped edge-dot border (tiled via CSS, height-snapped to 16px increments in JS so the border tiles always land cleanly) and a wave-stitch divider between rows
- SEO/social meta tags (Open Graph, Twitter Card) and a favicon

## Structure

```
index.html   — everything: markup, styles, and theme-toggle script
assets/      — logo (light/dark), favicon, social share image, decorative SVGs
CNAME        — GitHub Pages custom domain
```

## Deploying

Pushes to `main` publish automatically via GitHub Pages to the custom domain configured in `CNAME`.
