# loopbackengineering.com

Static website for Loopback LLC. Every push to `main` is deployed by Cloudflare Workers Builds (`npx wrangler deploy`).

- `public/` – everything served on the site (pages, images, `_headers`, `robots.txt`, `sitemap.xml`)
- `wrangler.jsonc` – Worker name, asset directory and custom domains
