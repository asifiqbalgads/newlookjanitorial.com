# New Look Janitorial Service — Homepage redesign

A premium, mobile-first static homepage concept for New Look Janitorial Service, based on the business information and original service photography published at [newlookjanitorial.com](http://www.newlookjanitorial.com/). Built with semantic HTML, CSS, and vanilla JavaScript; no build step or server-side dependencies are required.

## Run locally

Open `index.html` directly in a browser, or serve this folder with any static web server. All project-owned assets use relative paths so the site works from a GitHub Pages project subdirectory.

## Publish with GitHub Pages

In the repository's **Settings → Pages**, select the deployment branch and `/ (root)` as the source. The homepage is `index.html`; `.nojekyll` is included. GitHub Pages settings were not changed by this project.

## Brand and image notes

- The palette is sampled from the company's published logo mark: navy `#223669` and gold `#E6AC26`; the source mark itself is retained in `assets/logo/new-look-mark.png` and paired with the verified company name as accessible text.
- Typography uses the browser's standard Arial/Helvetica sans-serif stack rather than a downloadable font, avoiding device-specific webfont loading and icon-like glyph fallback.
- `assets/images/hero-clean-interior.jpg` is a custom-generated conceptual cleaning-industry visual, not a photograph of a New Look project, employee, or customer.
- Service and gallery photographs are original images embedded on New Look's existing website and are loaded from its image CDN. Their source URLs are retained in `index.html`.
- Business facts and contact details are drawn from the existing site. No testimonials or unsupported claims have been added. The original contact page's form reported invalid form properties, so the main contact actions use the published phone and email instead.
- `noindex, nofollow` is intentional for this redesign/demo and should be removed only if this project is approved to replace the public production site.
