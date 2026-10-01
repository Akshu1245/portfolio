# K S Akshay — Portfolio

Static site: index.html, style.css, script.js, assets/.

Run: open index.html, or `npx serve .`
Deploy: drag this folder to vercel.com/new or app.netlify.com/drop.

assets/: img1 = photo 1, img2 = photo 2, remaining = silhouette.
Edit content in index.html; project cards and timeline data are in script.js (arrays P and JD).

## v2 changes
- Own-voice copy, sharper hero (AI security + RaksHex), achievements gallery (edit array A in script.js; add certificate links via `b:[['View','url']]`).
- Pinned-section animation loop pauses off-screen; tilt effects only on fine pointers and when motion is allowed.
- Project screens are real buttons; modal closes on Esc and restores focus; skip link and focus outlines added.
- Contact: phone removed; form opens the visitor's email app.
- SEO: canonical + OG/Twitter + JSON-LD (@graph Person/WebSite) all point at `https://akshu1245.github.io/portfolio/`; `sitemap.xml`, `robots.txt` and `assets/og-image.png` (1200x630) included. The Vercel mirror is canonical-only (link tag) and sends `X-Robots-Tag: noindex` for `*.vercel.app` hosts.
- After deploy: submit the sitemap in Google Search Console + Bing Webmaster Tools (URL-prefix property); refresh the social card in the X/Facebook/LinkedIn debuggers; bump sitemap `lastmod` whenever content changes.

- Design references section: 24 third-party templates (array T in script.js), loaded in a popup iframe on demand and clearly credited as not my work.

- Client work (websites developed for clients): array W in script.js (from your verified CSV), filterable by category, live preview in popup.
