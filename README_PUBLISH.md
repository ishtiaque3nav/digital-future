# Digital Future — ChipCareer OS (current seller operations)

**Updated October 31, 2026.** This is the existing live Digital Future website and its original ChipCareer OS Gumroad product, not a second product or a new Stripe launch. The $15 product is advertised for purchase at https://ishtiaque54.gumroad.com/l/chipcareer-os. Internal Gumroad sales and views must be read in the authenticated Gumroad dashboard; the seller reported zero views and zero sales on October 31, not independently verified through this repository.

## Current customer journey

1. Website: https://ishtiaque3nav.github.io/digital-future/
2. Free exercise (no account or payment needed): https://ishtiaque3nav.github.io/digital-future/free-career-exercise.html
3. Full product details: https://ishtiaque3nav.github.io/digital-future/chipcareer-os.html
4. Paid listing, $15 one-time: https://ishtiaque54.gumroad.com/l/chipcareer-os
5. Successful Gumroad purchases deliver the customer ZIP using Gumroad's download page and receipt, rather than manual Stripe email fulfillment.

The repository HTML includes an explicit Gumroad purchase CTA and UTM-labeled links. It contains no paid buyer ZIP. The static site does not have authenticated visitor or conversion analytics; Gumroad Analytics > Links can track source-specific UTM links and their clicks and sales. Do not report site visitors or paid conversions without evidence. Public URLs were not independently loadable by the external checker on October 31; GitHub source presence does not prove browser accessibility.

## Payment and tax

Gumroad acts as merchant of record for its checkout transactions and says it handles applicable sales tax collection and remittance; see https://gumroad.com/help/article/121-sales-tax-on-gumroad. This is specific to Gumroad, not the separate inactive Stripe link. No new Stripe price, product, link or tax setting should be created or enabled for this Gumroad funnel.

Gumroad sent an October 22 payout-identity-information request to the account email. Owner should check https://gumroad.com/settings/payments directly using Gumroad's authenticated settings. Never send personal identifiers or one-time codes to a promoter/agent/in chat.

## Market access and first sales

Gumroad Discover is not the primary customer-acquisition source for an unproven product. Gumroad's published eligibility requires genuine sales, sufficient seller balance and risk review, plus product category, ratings enabled and a successful sale: https://gumroad.com/help/article/79-gumroad-discover. Do not rely on a new listing being indexed or promoted. Do not buy the product yourself to manipulate Discover.

The historical Oct 26 campaign snapshot was very low exposure (FB 11 impressions, 2 reach, 0 outbound link clicks; Instagram 0 reported views; TikTok publication unverified). This cannot establish product/price-market fit. Prioritize relevant audiences: semiconductor PhD/postdoctoral researchers, semiconductor device/process/reliability engineers, and technical-industry job seekers—not generic household hacks alone.

The standalone campaign originally scheduled for **November 1, 2026, noon Eastern** still had *PENDING* statuses when last checked; its earlier caption claimed checkout was closed, which contradicts the now-live Gumroad listing. Verify publication and correct stale content through authorized native controls, without using Metricool, duplicating the campaign, or changing unrelated content.

## Practical conversion measurement

Track separately and with timestamps:
- Actual published promotions and verified impressions/reach, by destination.
- Unique clicks and referrals, using Gumroad Analytics > Links with distinct sources/campaign names.
- Visits to the free exercise (unknown unless tracking is actually implemented and consent/privacy addressed).
- Gumroad product views, add-to-cart and sales; use authenticated Gumroad analytics for views and orders.
- Genuine buyer feedback and opted-in email replies; do not count owner test messages or self-purchases.

Target a first sample of 20-50 *qualified* product page visits before drawing price, copy or product conclusions. This is a measurement target, not a guarantee.

## Current files

`index.html`, `chipcareer-os.html`, `free-career-exercise.html`, `about.html`, `contact.html`, `privacy.html`, `terms.html`, `refunds.html`, plus `assets/`, `robots.txt` and `sitemap.xml`. Customer-facing content, including support at ishtiaque3nav@gmail.com, was previously updated to reflect Gumroad. Do not replace it with the old prelaunch Stripe copy.

See `QA_CHECKLIST.md` for the current readiness and commercial-validation checks.
