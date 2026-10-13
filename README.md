# Gulion Bank website

A professional, responsive fictional bank website with navy-and-gold styling, lifestyle photography, account comparison tabs, product dialogs, mobile navigation, and a savings contribution calculator.

## Free GitHub Pages hosting

The site files are ready to publish from the root of the `main` branch. No dependencies or build step are needed.

### One-time activation

1. Open [Settings → Pages](https://github.com/Korport/Gulion/settings/pages).
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the **main** branch and **/ (root)** folder, then click **Save**.
4. Wait for the Pages deployment to finish. GitHub will show the published address.

Expected website address after activation: **https://korport.github.io/Gulion/**

This is a public repository and uses GitHub Pages' free static hosting. Future changes to `main` will republish automatically after Pages is enabled. The `.nojekyll` file tells GitHub to serve the site directly.

No custom domain has been configured. To add one later, buy and verify the domain, follow GitHub Pages' custom-domain instructions, and configure DNS before enabling HTTPS. Do not add a CNAME file for a domain you do not own.

## Preview locally

Download or clone the repository and open `index.html` in a modern browser. Google Fonts uses an internet connection; system fonts provide a fallback. Images are included in the repository.

## Files

- `index.html` — page structure and metadata
- `style.css` — responsive layout and styling
- `app.js` — interactive account tabs, calculator, dialogs, and mobile menu
- `assets/` — locally hosted photographs
- `PHOTO-CREDITS.md` — photograph sources
- `.nojekyll` — direct static publishing on GitHub Pages

## Editing

Change text in `index.html`; account cards and dialog content are in `app.js`. Update colors and spacing in `style.css`. All asset paths are relative so the site works under `/Gulion/`.

## Scope

Gulion Bank is a fictional concept, not an operating financial institution. No real accounts, credentials, applications, payments, or banking services are processed. Calculator entries remain on the page and are not saved or transmitted. The calculation includes contributions only, without interest, fees, or taxes. Products are illustrative.

## Validation

JavaScript syntax and local asset references passed checks before upload. Live deployment and visual browser checks must be completed after GitHub Pages is activated.
