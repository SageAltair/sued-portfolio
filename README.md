# Sued R. Mwaigomole | Living Portfolio

A complete responsive static portfolio, using original photographs, project case studies, experience, a learning journal, a printable résumé, and contact links.

## Quick start

Open `index.html` in a modern browser. No installation, database, paid API, or build process required. For local development with a server (recommended), run `python -m http.server 8080` in this folder and visit `http://localhost:8080`.

## Free deployment to Cloudflare Pages

1. Create a GitHub repository and upload the contents of this folder (keep `index.html` at the repository root).
2. In Cloudflare, create a Pages project connected to that repository.
3. Choose **no framework / static HTML**; leave the build command blank and set the output directory to `/` (the repository root), or use Cloudflare's direct-upload Pages option and upload this folder.
4. Deploy. Cloudflare will give you a `*.pages.dev` address.

No environment variables or API keys are needed. Hash-based navigation (`#/work`, etc.) works on static hosting without server rewrites.

## Update content

- `script.js`: edit `projects`, `posts`, `now`, `about`, and `resume` content. Project and journal detail pages are generated from these objects.
- `styles.css`: change colors in `:root` and `html[data-theme=dark]`.
- `assets/images/`: optimized copies of the ten photos supplied for this project.
- `index.html`: SEO title and description.

## Features

- Responsive layout and accessible mobile navigation
- Light/dark theme saved in the browser
- Projects filter and individual project case studies
- Journal index and individual reading pages
- Printable résumé (browser Print → Save as PDF)
- Email contact, copy email, GitHub, and LinkedIn links
- No backend, cookies, analytics, tracking, or third-party JavaScript

## Before sharing publicly

- Confirm all wording, job titles, dates, project statuses, and photos are accurate and approved for public display.
- The site intentionally does **not** publish a phone number. It publishes the email listed on the résumé.
- Check the live GitHub/project links and add any verified demos.
- Journal entries are starter notes and should be edited into your own voice.
- Fonts load from Google Fonts when online, with system fallbacks offline.

## Notes

This is a working, deployable portfolio, not a CMS. Editing content requires changing `script.js`. It intentionally does not pretend to have a working contact-form backend or production-ready app demos. `mailto:` opens the visitor's email app.

## Photo refinement (October 2026)

This version preserves the original portfolio layout and navigation. All ten photographs were regenerated from the supplied JPG originals with restrained contrast/color and edge-sharpening adjustments. Original JPG files are included in `assets/originals/` for reversibility. No faces or other image content were synthesized. Existing image paths remain unchanged. The source photos' blur and compression cannot be completely recovered.

Use a local browser to review image crops on desktop and mobile before publishing.
