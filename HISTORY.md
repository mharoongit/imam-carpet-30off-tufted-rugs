# HISTORY

## [Unreleased]

---

## 2026-05-25 — Haroon (Meta Tracking + Campaign Monitoring)

### Meta Pixel Verification
- Verified all standard events firing:
  - PageView, ViewContent, Search, AddToCart, InitiateCheckout, Purchase
- Purchase EMQ: 9.3/10 — confirmed excellent match quality

### WhatsApp Conversion Tracking
- Created WhatsApp Click custom conversion in Meta (URL contains wa.me rule)
- Added WhatsAppClick custom pixel event to Shopify theme.liquid
- Identified that Interakt button renders inside an iframe — blocking pixel detection
- Further investigation needed to track Interakt button clicks via Meta Pixel

### Campaign Monitoring
- Reviewed Static, Video, and DPA ad set performance
- Renamed ad sets for accurate reporting
- Identified DPA retargeting ad set as likely purchase source
- Prepared performance reports for Shahzaib

### Omnisend + Interakt
- Verified abandoned cart and checkout recovery workflows active
- Verified Interakt Shopify integration and WhatsApp setup

---

## 2026-05-23 — Haroon (Meta Campaign Live + Tracking Operations)

### Jute Rugs Campaign
- Published Jute Rugs Collection Meta campaign
- Budget: PKR 10k/day
- Objective: Purchase / ROAS

### Ad Set Structure
- Ad Set A:
  - PKR 4k/day
  - Major Cities
  - WV-60D
  - Static creatives

- Ad Set B:
  - PKR 4k/day
  - Major Cities
  - WV-60D
  - Video creatives

- Ad Set C:
  - PKR 2k/day
  - All Pakistan
  - ATC + IC + WV 60D
  - DPA / Catalog Retargeting

### Meta Tracking
- Verified Meta Pixel active
- Confirmed:
  - PageView
  - ViewContent
  - Search
  - AddToCart
  - InitiateCheckout
- Verified Events Manager activity

### WhatsApp Conversion Tracking
- Created Meta Custom Conversion:
  - WhatsApp Click
- Rule configured:
  - URL contains wa.me
- Category:
  - Contact

### Omnisend
- Verified abandoned cart recovery workflow active
- Verified checkout recovery workflow active
- Confirmed trigger delays and exit conditions

### Interakt
- Verified Shopify integration
- Verified WhatsApp setup
- Confirmed basic automations enabled
- Confirmed advanced abandoned cart automation not visible in current setup

### Reporting
- Prepared Meta KPI reports for Shahzaib
- Shared campaign health updates
- Shared CTR / CPC / ATC monitoring updates

---

## 2026-05-22 — Haroon (Eid campaign retargeting setup)

- Completed full Meta campaign setup for two Eid campaigns:
  - Hand Tufted Rugs Collection
  - Jute Rugs Collection

- Configured 3 retargeting ad sets per campaign:
  - Karachi Same Day
  - Rest of Pakistan
  - DPA (ATC / IC / Website Visitors 60d)

- Budget structure:
  - Adset A = PKR 4k/day
  - Adset B = PKR 4k/day
  - Adset C = PKR 2k/day
  - PKR 10k/day per campaign
  - PKR 20k/day total

- Added:
  - Static creatives
  - Video creatives
  - Meta ad copy
  - Catalog setup
  - Retargeting audiences
  - Purchase optimisation
  - Collection URLs

- Both campaigns saved in DRAFT status awaiting Shahzaib approval before publish

---

## 2026-05-22 — Haroon (Ad Creative Production)

- Generated full Meta ad creative suite for Eid 2026 campaign
- Created:
  - Karachi same-day variants
  - Eid-cutoff variants
  - Carousel creatives

---

## Earlier

- Initial project structure created.
- Added CLAUDE.md, HISTORY.md, TASKS.md, README.md, and .gitignore.
- Bulk applied 30% off across 40 Hand Tufted Rug products on Shopify store.
- Drafted Eid 2026 sale campaign plan (8-day window 20–26 May).
- Verified all 40 Hand Tufted SKUs on Shopify.
- Confirmed PageView and InitiateCheckout events in Meta Events Manager.
- Connected Shopify with Meta Pixel successfully.
- Regenerated Meta access token.
- Organised VS Code workspace for Meta ads operations.
