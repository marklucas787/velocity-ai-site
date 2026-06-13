# velocity-ai-site

Public marketing site for **Velocity AI**. Static HTML/CSS, deployed on Netlify.

This repo is intentionally **separate from the private AIOS monorepo**. Only public marketing pages live here. No client data, no secrets.

## Workflow

1. Edit pages here (often authored in AIOS, then copied/committed here).
2. `git push` to `main`.
3. Netlify auto-builds and deploys in about a minute.

## Pages

- `index.html` — 90-Minute AI Audit landing page. Audience: financial-services firms on the Microsoft stack. Front-end of the funnel (Audit → AIOS Install → Fractional AI Officer retainer).

## Stack

- **Host:** Netlify (continuous deploy from this repo)
- **Booking:** the "Book the Audit" CTA points to the GoHighLevel calendar (set the link in `index.html`, currently `#book` placeholder)
- **No build step:** plain HTML, Tailwind + Google Fonts via CDN

## Assets

- `hero-A.png` — hero image
- `problem-1.png` — problem section
- `cc-clean-1.png` — mission-control atmosphere (Why me)
