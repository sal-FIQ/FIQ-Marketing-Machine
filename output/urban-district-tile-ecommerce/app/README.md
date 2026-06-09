# Urban District (Tile E-commerce) — Growth POV & Call Prep (app)

A single-file, self-contained web app for Sal's ~15-minute call with Adam Tenzythoff,
CEO of Urban District (the **tile e-commerce** venture). No build step, no dependencies.

> Not to be confused with `output/urban-district-developments/`, the marketing
> diagnostic for Adam's separate **construction/design-build** firm.

## The share / prep toggle
A switch in the top-right controls what's visible:

- **Prep view** (default) — everything, including your private material.
- **Share view** — hides the private prep so you can safely screen-share the growth POV.

Tabs marked with a copper dot (and a "Private" badge) are prep-only and disappear in Share view.

## What's inside
**Share-safe — the growth POV (safe to show Adam):**
- **Opportunity** — the tile e-commerce model and the growth thesis
- **Sample Funnel** — the core mechanic, the metric everything ladders to, and the lever at each stage
- **First 90 Days** — interactive plan (instrument → optimize → scale); check tasks off
- **B2B / B2C** — the two acquisition engines

**Private — your call prep (hidden in Share view):**
- **Your Pitch** — 30-sec positioning, proof points, alignment map
- **Ask Adam** — strategic questions; tap to star your 3–4 picks
- **Red Flags** — what to listen for
- **Fit Score** — score 8 dimensions 1–5 after the call; auto-verdict by the decision rule
- **Cheat Sheet** — executive phrases, traps, Maropost framing, close, follow-up (copy-to-clipboard)

## Deploy / use
- **Open locally:** double-click `index.html`.
- **GitHub Pages:** enable Pages on the branch, point it at `/output/urban-district-tile-ecommerce/app/`.
- **Netlify / Vercel / Cloudflare Pages:** drag-drop this folder, or set publish dir to `output/urban-district-tile-ecommerce/app`.

## Notes
- Picks, task progress, and fit scores are stored in your browser (localStorage) — nothing is sent anywhere.
- Source brief: `research/urban-district-tile-interview-prep.md`.
- Brand accent is a single CSS variable (`--accent`) at the top of `index.html` — swap to match Urban District's palette.
