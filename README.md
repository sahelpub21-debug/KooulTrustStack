A Trust-First Communications Thesis for Kooul — Single-Page Pitch

Single-page HTML pitch that outlines a trust-first communications thesis for Kooul (Rules • Clarity • Care).
It’s lightweight (HTML+CSS+JS only), mobile-first, accessible, and deploys cleanly on GitHub Pages.

Quick facts
Item	Value
Type	Static single page
Stack	HTML, CSS, vanilla JS
Hosting	GitHub Pages (free)
File	index.html (+ optional /images)
Live demo (after publish)

Your site will be available at:

https://<username>.github.io/<repository>/


Example: https://zakariagallouch.github.io/sahelpub21-debug/
If you rename the repository to zakariagallouch.github.io, the site will be served at the root domain.

What’s inside

Hero & author block with OG/Twitter meta for clean link previews.

Six strategic gaps section (cards + chips) aligned to growth levers.

Value proposition card tying the trust architecture together.

90-Day plan presented as outcome-first steps.

Case studies snapshot and external portfolio link.

Contact CTA with a single, clear action.

Mobile-first layout, accessible focus styles, and minimal dependencies.

File structure
/
├─ index.html        ← main page (required at repo root)
└─ images/           ← optional local assets (screenshots, logos, etc.)


If your current file is named landing-page-updated.html, either rename it to index.html or create a tiny index.html that redirects to it (snippet below).

Redirect index.html (optional)

<!doctype html>
<meta charset="utf-8">
<meta http-equiv="refresh" content="0; url=landing-page-updated.html">
<title>Redirect…</title>
<p>Redirecting to <a href="landing-page-updated.html">landing-page-updated.html</a></p>

How to publish on GitHub Pages

Put index.html at the repository root.

GitHub Pages serves /index.html by default.

Move/rename the file if needed.

Enable Pages

Go to Settings → Pages (section Code and automation).

Source: Deploy from a branch

Branch: main • Folder: / (root) → Save.

Wait 1–3 minutes for the build.

You’ll see “Your site is live” and the public URL.

Update: every commit to main republishes automatically.

Troubleshooting

If you see 404/blank: verify index.html exists at the root.

Check Actions → pages-build-deployment for errors.

Make image paths relative (e.g., images/screenshot.jpg).

Customize

Brand & title: edit <title>, og:title, twitter:title, header text.

Description: update <meta name="description">, og:description, twitter:description.

Preview image: replace og:image / twitter:image (recommended: local file in /images/og.jpg).

Links: update Website/Portfolio/LinkedIn URLs in the hero and contact sections.

Images: replace placeholders with local assets (prefer /images/... over external hosts for reliability).

Local preview

Double-click index.html and open in your browser or

Run a tiny local server (optional):

# Python 3
python -m http.server 8000
# then open http://localhost:8000/

Accessibility & performance notes

Focus outlines are visible (:focus-visible) and keyboard navigation is supported.

Typography and components use system fonts for speed.

No external JS frameworks; minimal CSS; image placeholders are SVGs.

License / reuse

Unless a license file is added, all rights reserved.
© 2025 Zakaria Gallouch. For pitch/review purposes.

Contact

Zakaria Gallouch — Senior Strategic Communications & PR Consultant
LinkedIn: https://www.linkedin.com/in/zakaria-gallouch/
