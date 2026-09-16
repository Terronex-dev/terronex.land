# terronex.land

Static marketing site for **Terronex LLC** — utility easements and non-environmental permits, midstream easements and permits, seismic permitting, and crossing agreements (rail, highway occupancy, foreign-utility crossings) — project-based across the United States. Software tools: [ROWFlow](https://rowflow.terronex.land), [Tractsource](https://tractsource.terronex.land), and [ROWScope](https://rowscope.terronex.land).

## Contents

- `index.html` — single-page site (SEO: canonical, Open Graph, Twitter card, JSON-LD)
- `404.html` — real not-found page (Cloudflare Pages static 404)
- `privacy.html` — short Terronex LLC privacy note for the estimate form
- `assets/` — header lockup, favicons, apple-touch icon, Open Graph image
- `favicon.ico` — default favicon
- `robots.txt` — allow all; sitemap pointer
- `sitemap.xml` — homepage and privacy

## Deploy

Publish this directory as the site root for `https://terronex.land/` (any static host: Vercel, Netlify, S3+CloudFront, GitHub Pages, etc.).

1. Point the domain apex (and optional `www` → apex) at the host.
2. Serve `index.html` at `/`.
3. Confirm `https://terronex.land/robots.txt` and `/sitemap.xml` are reachable.
4. No build step — upload or sync as-is.

Contact: hello@terronex.land
