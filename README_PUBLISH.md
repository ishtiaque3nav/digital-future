# Digital Future — public website

**Current release status (October 23, 2026): PRE-LAUNCH.** This is the existing Digital Future project, not a new or separate storefront. The planned ChipCareer OS v1.0 price is **$15 USD, one time**. Checkout is intentionally closed pending applicable sales-tax registration and final fulfillment tests. Do not accept orders or represent scheduled promotions as published.

## Customer-facing experience

- `index.html` — Digital Future homepage.
- `chipcareer-os.html` — full product description, actual preview and the $15 pre-launch offer.
- `free-career-exercise.html` — free, interactive 10-minute evidence-to-résumé exercise, with voluntary email-based feedback choices. No payment or signup is required. It does not automatically collect visits or submissions.
- `about.html`, `contact.html`, `privacy.html`, `terms.html`, `refunds.html` — company information and disclosures.
- `assets/` — static CSS, JavaScript, logo and actual product screenshot.
- `robots.txt` and `sitemap.xml` — search-engine discovery helpers.

The public support address is **ishtiaque3nav@gmail.com**. The website is published from the GitHub repository `ishtiaque3nav/digital-future`; actual HTTPS accessibility must be verified separately after each deployment. Public source files do **not** contain the paid buyer ZIP, payment secrets or a working checkout.

## Existing payment and fulfillment design

The **Digital Future live Stripe account** already has a ChipCareer OS product, an active $15 one-time price, and a prepared **inactive** $15 Payment Link. An older $59 price is inactive. Do not create another product, change pricing, or enable checkout just to satisfy a checklist. When legally and operationally ready, use the existing $15 link after checking tax treatment and truthful checkout/delivery disclosures.

Delivery is currently designed as **manual email within 24 hours of verified successful payment**, to the checkout email. A Stripe Payment Link alone does not attach or securely deliver the paid ZIP. Until a supported automated workflow is separately built and tested, do not advertise instant or automatic delivery.

## Launch gate (owner and operator)

1. Confirm seller identity/operating name and obtain any required registrations. New York generally treats downloaded prewritten software as taxable; assess the bundle with a qualified tax professional and obtain any required NY Certificate of Authority before taxable NY sales. The state application and approval are not completed merely by configuring Stripe Tax.
2. Verify the correct tax registrations/tax settings in Stripe; confirm the product tax code and destination-based collection approach for jurisdictions where registered/obligated.
3. Review buyer ZIP, license, refund/terms/privacy copy, desktop/mobile user experience and support inbox; perform a permitted payment-and-manual-delivery test.
4. Independently verify GitHub Pages HTTPS homepage, product page and free-exercise page, including mobile, links, copy function and email feedback links.
5. Only after the above gate passes, activate the existing $15 link and deliberately update the site's checkout state and policy language.

## Measurement and outreach

The free exercise requests explicit email feedback; **no customer replies or page-view metrics may be inferred from the static website alone**. Measure genuine Gmail replies to `ChipCareer validation -`, exclude owner/test mail, and distinguish interested/not-at-price/not-for-me replies from paid purchases. Verify actual social-provider publication before counting outreach exposure. Do not duplicate an existing scheduled campaign. Public GitHub source is not a confidential CRM.

See `QA_CHECKLIST.md` for current test coverage and launch conditions. Historical older instructions referring to a $59 price, sandbox-only Stripe access or a not-yet-created repository are superseded by this README.
