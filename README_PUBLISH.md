# Digital Future — Static website v1.0

## Purpose
Standalone, responsive company website with a truthful pre-launch profile for Digital Future and planned first digital product ChipCareer OS. No third-party JavaScript/CDN, customer ZIP, payment link, newsletter, backend, personal contact data or secrets included. Product screenshot derived from the actual buyer package. The site is not yet ready to submit as a complete operating commercial business website until the owner completes the blockers below.

## Contents
- index.html: Digital Future landing page
- chipcareer-os.html: detailed, honest product information and $59 **planned** one-time price
- about.html, contact.html, privacy.html, terms.html, refunds.html
- assets/site.css, site.js, logo.svg, chipcareer-preview.png
- .nojekyll: GitHub Pages static publishing helper
- QA_CHECKLIST.md: launch and validation tests

## Preview locally
Extract ZIP, open `index.html` in Chrome/Firefox/Edge/Safari, navigate all pages. You may use `python -m http.server 8000` in this folder if desired, then visit http://localhost:8000.

## REQUIRED before sending URL to Stripe (do not skip)
1. Confirm the actual proprietor/merchant identity. The public-facing brand 'Digital Future' must match the operating name entered in Stripe. Check business-name / assumed-name registration requirements where you operate; do not suggest a registration has occurred if it hasn't.
2. Add an actual, monitored public business support email to `contact.html` (replace placeholder text) and to relevant policy pages; send a test email from another account. Do not publish your private personal inbox without explicit choice. Optional domain email can be added later.
3. Review and approve the exact planned refund/chargeback and delivery terms. Replace the prelaunch refund policy with final commercial policy once terms are adopted. Review privacy and website terms for actual services (GitHub Pages host, Stripe payment, fulfillment provider, analytics if ever used) and applicable law.
4. Check naming for collisions/brands and review all product content, pricing, screenshots, technical claims, customer package licensing and user experience.
5. Publish the public site to a GitHub Pages repository (recommended separate repository `digital-future`, not the personal portfolio repo); keep this site publicly accessible and not password-protected. Test each page on a phone.
6. The URL may be `https://YOUR_GITHUB_USERNAME.github.io/digital-future/` after public deployment and Pages configuration; this is EXAMPLE ONLY, not a verified or already-live URL. Use the exact live URL displayed by your host when filling Stripe Business website field.
7. Stripe verification may require additional account information. Confirm payment account is live-mode capable, and do not promise that a website by itself guarantees approval.

## Later: release process
- Choose and provision secure digital delivery: a service integrated with Stripe or a verified webhook flow. Stripe Payment Links alone do not deliver arbitrary ZIPs.
- Create a one-time USD 59 product and live payment link only after the merchant account and fulfillment policy are ready.
- Implement and verify paid event handling, duplicate protection, download link validity, buyer support, failed payment handling, and receipts.
- Update real checkout, refund, privacy and support details; remove prelaunch banner; update FAQ and legal pages only when truthful.
- Test end-to-end with permitted payment testing and, when appropriate, a low-value live transaction handled according to Stripe rules. Never paste secret keys into site code or commit private buyer ZIP.

## GitHub Pages basics
1. Create a new public repo named `digital-future` under your account (or another publisher account you control).
2. Upload the unzipped website files into the repo root, preserving the `assets/` folder; select main branch.
3. Repo Settings → Pages → Deploy from a branch → `main` / root. Wait for the public URL shown by GitHub, then verify all site links and policies.
4. If a custom domain is added later, configure DNS and HTTPS through the hosting provider; do not enter an invented domain during Stripe setup.

No public deployment was performed when this ZIP was built. There is no live purchase link; this is deliberate.
