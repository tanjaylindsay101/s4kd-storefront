# S4KD — GitHub + Vercel Production Package

This is the production-ready static S4KD storefront prepared for:

**GitHub → Vercel → Namecheap / 4eversakred.com**

## Repository root

Upload the CONTENTS of this folder to the root of the GitHub repository. `index.html`, `app.js`, `styles.css`, and `vercel.json` must all remain at repository root.

Do not upload this ZIP as the only repository file. Extract it first, then commit the extracted project files with the existing folder structure intact.

## Vercel import settings

- Framework Preset: **Other**
- Root Directory: **repository root (`./`)**
- Build Command: **leave blank / none**
- Output Directory: **leave blank / none**
- Install Command: **leave blank / none**

`vercel.json` provides SPA rewrites for the storefront's internal routes while leaving static assets and videos untouched.

## Production verification

Verify these URLs after deployment:

- `/`
- `/shop`
- `/collections/sosakred`
- `/products/beretta-boyz`
- `/products/only-grace`
- `/products/frame-it`
- `/about`
- `/cart`
- `/account`
- `/search?q=Beretta`

Also verify:

- ENTER HERE intro screen on a new browser session
- all 3 hero videos
- Beretta Boyz back, clean front, and lifestyle front images
- product gallery swipe on mobile
- add-to-cart and cart badge
- direct refresh on product/internal URLs
- mobile and desktop layout
- HTTPS on the final custom domain

## Custom domain

Final domain: `4eversakred.com`.

Connect the domain in Vercel first, then apply the DNS records Vercel gives you in Namecheap. Use Vercel's displayed records as the source of truth because DNS targets can vary by account/configuration.
