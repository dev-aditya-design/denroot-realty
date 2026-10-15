# DenRoot Realty

Complete React + Vite demonstration for Govind Jha’s DenRoot Realty. Original SVG identity, forest green / ivory / champagne palette, responsive layouts, centralized property data, six detail pages with galleries, filters persisted in URLs, about/contact/disclosures pages, FAQ, call links and locally validated WhatsApp enquiry preparation.

## Run

```sh
npm ci
npm run dev
npm test
```

`npm test` builds the production app and runs nine Playwright browser tests. On Linux the configuration uses `/usr/bin/chromium` if available; otherwise install Playwright Chromium (`npx playwright install chromium`). `npm run build` creates `dist/`.

## Integrity

Derived from the supplied local checkout of `dev-aditya-design/real-estate-template`, commit `1199b9f0ed765841d2636af310fcf6bd32da5567`. Template source and deployment were not modified. The new repository has independent Git history and only the intended `denroot-realty` remote.

All property names are fictional concepts and explicitly labelled. Area names and business contact details were provided by the client. No customer reviews, credentials, prices, availability, dimensions, affiliations or investment outcomes are asserted. Photography is retained architectural inspiration from the starting template, not evidence of any local inventory. Confirm inherited image licensing before using beyond the supplied demo context.

The supplied chat posters were visible but had no downloadable file references in the execution environment; no video was accessible. SPJ Vedatam is presented through original conceptual artwork and a specific enquiry link. Poster prices, offers and availability are not repeated.

The contact form has no backend. It validates on the device, prepares a WhatsApp link and lets the visitor explicitly review and send. No data is stored by the site.

## Validation performed

Production build passed. Nine Playwright tests passed in 14.7 seconds. Tested all property routes, gallery controls, filter combinations and persistence, empty state, contact validation, prefilled WhatsApp content, call/WhatsApp link targets and mobile menu. Checked layout overflow on home, collection, detail, about and contact at 375, 390, 768 and 1440 pixel widths. Desktop/mobile screenshots were visually reviewed. No browser JavaScript errors were detected in the page-navigation test. Live browser verification remains blocked by deployment permissions.

## Publishing status

- Requested public GitHub target: `dev-aditya-design/denroot-realty`. Not created: CLI GitHub API access returned Forbidden, and the connector offers no repository-creation capability. Connector lookup confirmed 404.
- Separate Vercel project successfully created: `denroot-realty`, ID `prj_swEsekK4o9dwuqv1f7OpZQyLQAgr`, account ID `team_iN7efdMG0cFi58WC7qx4niQZ`.
- Vercel file upload denied with 403 under scope `devadixo-3641`. No deployment URL exists.
- Default SSO protection remains enabled. Automatic approval review rejected disabling it because public-access security changes require explicit approval.
- Original template and all other realtor projects/deployments were left untouched.

### Finish with authorized account access

After restoring GitHub/Vercel publishing access, create the empty public GitHub repository `dev-aditya-design/denroot-realty` and push this checkout’s main branch. Import that repository into the existing DenRoot Vercel project (do not replace any template/realtor project), using Vite, `npm run build`, and output `dist`. Approve the DenRoot project’s public-access setting if the demo should be visible without Vercel login.

Verify the resulting canonical production domain. Set the canonical and Open Graph absolute URLs in index.html to that verified domain; social image is `/images/social.jpg`. Then verify home, filters, detail URLs, mobile navigation, and contact links on the live site. Do not claim a guessed Vercel address as verified.
