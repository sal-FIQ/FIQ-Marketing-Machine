# Urban District Developments — Marketing Command Center (app)

A single-file, self-contained web app version of the marketing diagnostic & 90-day
growth plan for Urban District Developments Inc. No build step, no dependencies.

## What it does
- **Overview** — the core finding and the buyer journey in this market
- **Scorecard** — visual grades across the seven diagnostic areas
- **90-Day Plan** — an interactive execution board; check tasks off (progress saved in the browser via localStorage)
- **Quick Wins** — the five things to start this week
- **Templates** — copy-to-clipboard review-request, homepage-hero, and referral-outreach copy
- **KPIs** — set baselines/targets and track current numbers (saved locally)

## How to use / deploy
Pick any of these — it's just one static HTML file:

- **Open locally:** double-click `index.html` (or open in any browser).
- **GitHub Pages:** push this folder, enable Pages on the branch, point it at `/output/urban-district-developments/app/`.
- **Netlify / Vercel / Cloudflare Pages:** drag-and-drop this folder, or connect the repo and set the publish directory to `output/urban-district-developments/app`.
- **Any static host / S3:** upload `index.html`.

## Notes
- All task progress and KPI inputs are stored in the visitor's browser (localStorage) — nothing is sent anywhere.
- Source diagnostic write-up lives alongside this folder at `../marketing-diagnostic.md`.
