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
- TODO after you pick a domain: add absolute `og:image` (1200x630), `canonical`, sitemap.xml, robots.txt.

- Design references section: 24 third-party templates (array T in script.js), loaded in a popup iframe on demand and clearly credited as not my work.

- Client work (websites developed for clients): array W in script.js (from your verified CSV), filterable by category, live preview in popup.
