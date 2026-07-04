# ÆLabs — aebiolabs.com static site

29 self-contained HTML pages (images inlined as data URIs). Host anywhere static:
GitHub Pages, Netlify, Vercel, S3. No build step required to serve.

Pages: index, shop, 16 product-*.html, test-reports, about, wholesale, contact,
cart, login, and legal (shipping, terms, refund, privacy, cookies).

Compliance built in on every page: 21+ age gate, cookie consent (essential /
analytics / marketing), members-only login gate, research-use-only + 503A/503B.

## Regenerate / edit
Source generator lives outside this folder: sitegen.js + catalog.json +
assets/data-uris.json + site-css.css. Edit catalog.json (products/pricing/mg) or
site-css.css (styles), then `node sitegen.js` to rebuild all pages.
