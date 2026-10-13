# Gulion Bank

A responsive, static banking website concept with professional photography, account comparison tabs, product dialogs, and a savings contribution calculator.

## Preview locally

Open `dist/index.html` in a modern browser. No installation or build step is required. Google Fonts requires an internet connection; system fonts provide a fallback.

## Publish with Cloudflare Pages

1. In Cloudflare, open Workers & Pages and create a Pages project using Git integration.
2. Connect this GitHub repository (`Korport/Gulion`).
3. Set the production branch to `main`, framework preset to **None**, leave the build command empty, and set the output directory to `dist`.
4. Deploy and check the provided `pages.dev` URL.
5. After purchasing and verifying ownership of `gulionbank.com`, add the domain to Cloudflare, set the registrar's nameservers to those assigned by Cloudflare, and add `gulionbank.com` under the Pages project's Custom domains.
6. Add `www.gulionbank.com` as another custom domain and configure a redirect to your preferred address.
7. Verify HTTPS and both domain variants before sharing the site.

Future commits to `main` automatically deploy after the Git integration is configured. This repository alone does not activate hosting or register a domain.

## Files

- `dist/index.html`: page structure and metadata
- `dist/style.css`: responsive styling
- `dist/app.js`: account tabs, dialogs, mobile navigation, and calculator
- `dist/assets/`: locally hosted photos
- `PHOTO-CREDITS.md`: photograph sources

## Scope

Gulion Bank is a fictional concept. No real accounts, credentials, applications, payments, or banking services are processed. Calculator inputs are not saved or transmitted; the calculation includes contributions only, without interest, fees, or taxes. Product descriptions are illustrative.

## Checks performed

JavaScript syntax and local asset references were checked. Live hosting, custom-domain setup, and browser visual verification remain to be completed.
