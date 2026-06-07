# Ship69 Hub — Day 69

> The final ship. One page linking all 65 projects built across 69 days.

## What it is

The public hub for the Ship69 challenge — hero, featured projects, filterable grid of all ships, about section, and CTA.

## Sections

- **Hero** — 69 days, 69 ships. Stats strip: shipped / AI tools / games / landing pages / days
- **Featured** — 6 standout ships: Designdigest, Whyframe, Motionstudio, Foliopath, Statboard, Typefeel
- **All Projects** — Filterable grid of all 65 projects by type (AI Tool / Game / Landing / Design / Multi-stage)
- **About** — The story, links, stats
- **CTA** — Hire me / GitHub

## URLs pulled from Vercel

All live project URLs matched directly from Vercel deployments. Projects without a live URL show at 60% opacity with no link.

## Stack

- Vanilla HTML/CSS/JS — zero dependencies
- No API — fully static
- Vercel hosting

## Deploy

1. Push to GitHub repo `ship69-hub`
2. Connect to Vercel
3. Deploy — no env vars needed

## Updating URLs

Edit the `projects` array in the `<script>` tag. Each entry:

```js
{ day: 1, name: 'Project Name', type: 'tool|game|landing|design|multi', desc: 'Short description', url: 'https://...' }
```

Set `url: '#'` for projects without a live link.

---

Built during Ship69 · design engineering portfolio challenge · 2025
