# HISTORY.md

A log of changes made to this project, newest first.

---

## [Unreleased]

### 2026-05-21 (Emaan daily ops check)
- Verified all 40 Hand Tufted SKUs on Shopify: all ACTIVE, 39/40 in stock.
- OUT OF STOCK FLAG: Arna Hand Tufted Rug 11.4×8 (SKU: BB(TFT)0068) — inventory = 0. Needs sold-out label / hide from collection.
- compareAtPrice NOT set on any tufted product — 30% discount applied as current price only, no strikethrough visible to customers. Zubair to action via theme sticker as planned.
- Eid sale orders (20–21 May): 1 order — #2509 Ali Akbar PKR 33,158.40 PENDING/UNFULFILLED. Dispatch ping to Umair required.
- Orders board: old PAID/UNFULFILLED backlog pre-Eid identified. Needs manual review and cleanup.

### 2026-05-20 (Omni overlay rewrite — shot-aligned)
- Analyzed source reel `Tufted Reel Without Logo.mp4` (23.15s) via VideoDB shot-by-shot indexing. 10 visual segments mapped.
- Pulled live Shopify data for `Hand Tufted Rugs` collection: 40 SKUs, wool+viscose, sizes 8×5 to 13×9 ft, PKR 98k–263k.
- Corrected overlay copy: dropped wrong claims ("50+ colors", "custom sizes", UK delivery). Replaced with real positioning: 70+ yrs craft, since 1952, big-room sizes, 40 designs, Pakistan delivery.
- Rewrote `video-assets/gemini-omni-text-overlay-prompt.md` with per-shot timed overlays for Run 1 (0–10s), Run 2 (10–20s), Run 3 (20–23s CTA).
- Installed `videodb` + `python-dotenv` SDKs. Saved API key to project `.env` (gitignored).

### 2026-05-20 (Tufted video text plan)
- Drafted text-overlay plan for existing silent 23-sec tufted rugs video. 7 beats: Hook → 30% OFF → Proof → Since 1952 → Free delivery → Ends 26 May → CTA. Includes 3 alt cuts (Karachi, price anchor, static), aspect ratios, ad copy. Saved to `video-assets/tufted-video-text-plan.md`. Owners: Zubair edit, Shahzaib approve, Haroon upload.

### 2026-05-19 (Eid open item #1 closed)
- BM ID confirmed: 145166706590306. Ad account: 2130004033776229. Logged into `EID-CAMPAIGN-PLAN.md`. Pixel verification still pending (Haroon).

### 2026-05-19 (Eid campaign planning)
- Drafted Eid 2026 sale campaign for hand-tufted rugs collection. 8-day window 20–26 May (Eid = 27 May).
- Channels: WhatsApp (Umair via Interakt), Omnisend email (Shahzaib), Meta paid ~PKR 80k (Shahzaib + Haroon), IG/Pinterest organic in-house (Zubair + Shahzaib), Shopify site CRO (Zubair). Inventory/orders: Emaan.
- Plan v2 approved by Shahzaib with per-person owner assignments.
- Created project doc `EID-CAMPAIGN-PLAN.md` (full plan + verification steps).
- Mirrored plan to vault: `Plans/2026-05-19-eid-tufted-sale.md`.
- Updated `Imam Carpets/Knowledge Base/business-knowledge-base.md`: §3 Team refreshed (Artwing removed, current in-house team Shahzaib/Haroon/Zubair/Emaan/Umair listed), §4 Organic Marketing rewritten as in-house, §8 COD rule clarified (COD only on orders <PKR 30k; ≥PKR 30k = bank transfer or card), Sales Channels Tahir reference removed.
- Created `Workers/Employees/Umair.md` profile.
- Updated `TASKS.md` with per-person Eid campaign checklists.
- Pre-launch open items pending from Shahzaib: BM/ad-account ID, WhatsApp list size, email list size, Karachi same-day delivery cutoff time, Umair full-time availability confirm.

### 2026-05-19 (earlier)
- Bulk applied 30% off across 40 Hand Tufted Rug products on Shopify store (price = 70% of compareAtPrice). Updates ran ~06:35–06:36 UTC.
- Added Workflow Rules section to CLAUDE.md: every project task must update TASKS.md + log in HISTORY.md.

### Earlier
- Initial project structure created.
- Added CLAUDE.md, HISTORY.md, TASKS.md, README.md, and .gitignore.

---

## How to Use This File

When you make a change, add a new entry at the top under `[Unreleased]`.
When you release a version, rename `[Unreleased]` to the version number and date, then add a new empty `[Unreleased]` section above it.

### Example

```
## [Unreleased]
- Nothing yet.

## [1.0.0] - 2026-05-18
- First public release.
- Added user login feature.
```

---

*Follow [Keep a Changelog](https://keepachangelog.com) conventions.*

## Progress Update — Haroon
## May 21, 2026
### Completed Tasks
- Verified Meta Pixel firing on Shopify
- Confirmed PageView and InitiateCheckout events in Meta Events Manager
- Connected Shopify with Meta Pixel successfully
- Created meta-creatives planning structure
- Added Karachi, Rest of Pakistan, and DPA creative planning files
- Removed accidental image upload from repository
- Added Meta campaign structure planning
- Added KPI / ROAS dashboard planning
- Added Shopify QA checklist for Eid campaign
- Added Meta Ads launch checklist planning
- Added audience targeting strategy planning
- Added Meta ad copy planning for Eid 2026 campaign
- Added retargeting strategy planning