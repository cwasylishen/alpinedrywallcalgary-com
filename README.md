# alpinedrywallcalgary.com

Marketing site for Alpine Drywall (Calgary) Ltd. Commercial and institutional drywall, framing, and acoustical ceilings since 1986.

## Stack

Static HTML, no build step. Hosted on Cloudflare Pages.

- `index.html`, `expertise.html`, `safety.html`, `team.html`, `contact.html`, `404.html`
- `assets/styles.css` — design system
- `assets/images/` — optimized JPGs and PNGs
- `_headers` / `_redirects` — Cloudflare Pages config
- `sitemap.xml`, `robots.txt`

## Deploy

Connect this repo to Cloudflare Pages. Build command: none. Output directory: `.`.

## Form

`contact.html` posts to a Formspree endpoint. Replace `https://formspree.io/f/your-form-id` with the real endpoint when ready, or wire the submission to a Cloudflare Worker.
