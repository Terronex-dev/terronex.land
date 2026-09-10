# terronex.land

Static marketing site for **Terronex LLC** — Mid-Atlantic utility land rights, easement acquisition, and non-environmental permitting (fiber, electric, gas, midstream). Software tools: [ROWFlow](https://rowflow-alpha.vercel.app) and [Tractsource](https://tractsource.vercel.app).

## Contents

- `index.html` — single-page site (SEO: canonical, Open Graph, Twitter card, JSON-LD)
- `robots.txt` — allow all; sitemap pointer
- `sitemap.xml` — homepage only

## Deploy

Publish this directory as the site root for `https://terronex.land/` (any static host: Vercel, Netlify, S3+CloudFront, GitHub Pages, etc.).

1. Point the domain apex (and optional `www` → apex) at the host.
2. Serve `index.html` at `/`.
3. Confirm `https://terronex.land/robots.txt` and `/sitemap.xml` are reachable.
4. No build step — upload or sync as-is.

Contact: terronex.dev@gmail.com
