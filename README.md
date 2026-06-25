# Query Vitals — landing page

A self-contained, zero-build marketing page for [queryvitals.com](https://queryvitals.com).

- `index.html` — the entire page (HTML + inline CSS). Fonts load from Google Fonts; everything else is local.
- `icon.png` — app icon, copied from `../resources/icon.png`.

The design mirrors the app's developer-tool dark palette and "Liquid Glass" surfaces
(see `tailwind.config.js`): base `#0b0e14`, accent `#5b8def`, JetBrains Mono for code.

## Preview locally

```bash
# from this folder
python3 -m http.server 4173
# then open http://localhost:4173
```

Or just open `index.html` directly in a browser.

## Deploy

It's static — drop the folder on any host (GitHub Pages, Netlify, Vercel, S3, Cloudflare Pages)
and point `queryvitals.com` at it. No build step.

> Note: GitHub and release links use the placeholder `github.com/queryvitals/query-vitals`.
> Update them to the real repository before publishing.
