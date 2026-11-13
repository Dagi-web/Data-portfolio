# Dagem Taddese — Portfolio

Personal portfolio of Dagem Taddese, a commercial growth strategist in Addis Ababa working across sales, marketing, business development and operations.

**Live:** https://portfolio-dagi.vercel.app/ · https://dagi-web.github.io/Data-portfolio/

## What's in the repo

| File | Purpose |
|---|---|
| `index.html` | The entire site: HTML, CSS, JS, images and the downloadable CV, in one file |
| `og-image.jpg` | 1200 × 630 preview image shown when the link is shared on LinkedIn, WhatsApp, X and Telegram |
| `.github/workflows/pages.yml` | GitHub Actions workflow that publishes `index.html` and `og-image.jpg` to GitHub Pages on every push to `main` |
| `.gitignore` | Keeps system and editor files out of the repo |
| `LICENSE` | All rights reserved. Reuse needs written permission |

There is no build step and no dependencies. The only external request is the Montserrat font from Google Fonts.

## First-time setup

In the repo, open **Settings → Pages** and set **Source** to **GitHub Actions**. The next push to `main` (or a manual run from the **Actions** tab) publishes the site.

## Update the site

1. Edit `index.html` (or replace it with the new version) and commit to `main`.
2. The workflow redeploys automatically. Check progress under the **Actions** tab.

To change the CV, replace the base64 block inside `<script id="cv-b64">` near the end of `index.html`. The "Download CV" buttons read from it.

## Before you share a new version

- Keep `og-image.jpg` in the repo root. The `og:image` and `twitter:image` tags point to it.
- Link previews are cached by the platforms. After a change, refresh them with the [LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/) and the [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/).
- If the primary domain changes, update `canonical`, `og:url`, `og:image` and `twitter:image` in the `<head>`.

## Contact

Taddesedagem@gmail.com · [LinkedIn](https://www.linkedin.com/in/dagem-taddese-030a52140/) · [GitHub](https://github.com/Dagi-web)

© 2026 Dagem Taddese. All rights reserved. See `LICENSE`.
