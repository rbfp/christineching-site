# christineching-site

Professional portfolio / bio landing page for **christineching.com**.

- **Hosting:** GitHub Pages (served from the `main` branch, root).
- **Custom domain:** `christineching.com` (see `CNAME`), DNS on Cloudflare.
- **Stack:** single self-contained `index.html` (no build step, no dependencies).

## Editing

Edit `index.html` and push to `main` — GitHub Pages redeploys automatically within a minute or two. Replace the placeholder bio, tagline, work items, and contact links.

## DNS (Cloudflare)

Apex `christineching.com` → GitHub Pages A/AAAA records; `www` → `rbfp.github.io` (CNAME). All records set to **DNS only** (grey cloud) so GitHub Pages provisions its own TLS certificate.
