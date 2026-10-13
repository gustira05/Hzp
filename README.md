# HZP Law Firm Website

This repository contains a bilingual static landing page for HZP Law Firm. It is designed as a premium, responsive legal website with English and Indonesian language toggling, friendly accessibility, and SEO basics.

## Files included
- `index.html`
- `assets/css/style.css`
- `assets/js/main.js`
- `assets/images/logo.svg`
- `assets/images/logo-footer.svg`
- `assets/images/favicon.svg`
- `robots.txt`
- `sitemap.xml`

## Local preview
Open `index.html` directly in a browser, or run a simple local web server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## GitHub Pages
To publish on GitHub Pages, enable Pages in the repository settings and choose the `main` branch as the source (root folder). If you use project pages, set the folder to `/root` (or repo root).

## Before production publication
Update the following placeholders before publishing or making the site live:
- official office address
- official phone number
- official email address
- any team names and bios if they are not verified
- all image sources if they are external and not licensed for your use

## Notes on images
This version uses a mixture of the provided logo concept and Unsplash CDN imagery for presentation. If you have the official firm logo file or licensed image assets, replace them locally in the `assets/images` folder or update the URLs in `index.html`.

## Legal notice
Do not publish client information or legal claims that are not verified. Make sure any formal consultation links, addresses, and contact details are validated before going live.
