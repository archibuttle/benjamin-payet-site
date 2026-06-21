# Benjamin Payet, Personal Website

A single-page personal site and CV for Benjamin Payet, Chief Product Officer (AI / Generative AI / Agentic AI).

**Live:** _(deploy URL to be added)_

## Stack

- Single self-contained `index.html` (inline CSS + vanilla JS, zero build step, zero dependencies)
- Swiss-minimal design system: Inter + JetBrains Mono, strict grid, black on white
- `IntersectionObserver` scroll reveals (respects `prefers-reduced-motion`)
- Print stylesheet for clean "save as PDF" resume export
- Deployable on any static host (Cloudflare Pages, Netlify, GitHub Pages)

## Run locally

Open `index.html` in any browser. No server or build required.

## Deploy

```bash
npx wrangler pages deploy .
```
