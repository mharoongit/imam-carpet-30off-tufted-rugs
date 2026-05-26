# CLAUDE.md

This file contains instructions for Claude Code when working in this project.

## Project Overview

This is a beginner-friendly project. Keep code simple, readable, and well-organized.

## Guidelines for Claude Code

- Write clean, simple code with clear variable names.
- Prefer small, focused functions over large complex ones.
- Add comments only when the "why" is not obvious.
- Do not add unnecessary dependencies.
- Always check existing files before creating new ones.

## File Structure

| File | Purpose |
|------|---------|
| `README.md` | Project overview and setup instructions |
| `CLAUDE.md` | Instructions for Claude Code (this file) |
| `HISTORY.md` | Changelog and version history |
| `TASKS.md` | Task tracking and to-do list |
| `.gitignore` | Files excluded from git |

## Coding Conventions

- Use descriptive names for files, functions, and variables.
- Keep functions short — one function, one responsibility.
- Format code consistently before committing.

## Workflow Rules

- Every time work done in this project: update `TASKS.md` (mark done / add new tasks) AND log work in `HISTORY.md` with date + short description.
- **Always auto-commit and push to GitHub after any meaningful change.** Do not wait for user to ask. Repo: `mharoongit/imam-carpet-30off-tufted-rugs`. Every edit ends with `git add` → `git commit` (clean message) → `git push`. Nothing is ever lost; easy to revert.

## Commit Style

Use short, clear commit messages:

```
Add login page
Fix typo in README
Update task list
```

---

# Imam Carpets — Eid 2026 Meta Ads Operations

## Latest GitHub Commit
https://github.com/mharoongit/imam-carpet-30off-tufted-rugs/commit/fd5077160777f86c981a5f0b5338f8599aacdafd

## Recent Operations
- Regenerated Meta access token
- Organised VS Code workspace for Meta ads operations

---

## 26 May 2026 — Haroon (Campaign Optimization + Creative Strategy)

### Meta Campaign Optimization
- Reviewed complete Eid 2026 Jute Rugs retargeting campaign performance.
- Identified:
  - Static ad set as current conversion winner
  - Video ad set as highest CTR/engagement performer
  - DPA retargeting as strongest buyer-intent audience
- Verified confirmed purchase attribution from Static ad set.

### Budget Optimization
Updated budget allocation:
- Static Ad Set → PKR 4,000/day
- Video Ad Set → PKR 2,500/day
- DPA Retargeting → PKR 3,000/day

Reasoning:
- Static ad set generated confirmed purchase and strongest ROAS.
- Video ad set showed strong CTR but high frequency and no purchase activity yet.
- DPA retargeting audience showed stronger buyer intent and efficient CPC.

### Funnel Analysis
- Identified major funnel drop between AddToCart and InitiateCheckout.
- Current funnel signals:
  - 102 Add to Cart events
  - Very low checkout initiation rate
- Future focus:
  - Shopify mobile checkout audit
  - COD visibility
  - Checkout friction reduction
  - Eid delivery clarity

### Creative Production
- Created new Eid-focused static Meta creatives.
- Planned creative replacement/testing strategy for Video Ad Set B if weak conversion trend continues.
- Created new AI-generated luxury Jute Rug creatives for post-Eid campaigns.
- Developed premium/luxury creative angles targeting high-end Pakistani audience.

### WhatsApp + Tracking
- Verified Purchase event firing successfully.
- Verified WhatsAppClick custom event implementation.
- Verified Meta Pixel tracking:
  - PageView
  - ViewContent
  - Search
  - AddToCart
  - InitiateCheckout
  - Purchase

### Future Optimization Plan
- Scale winning static creatives gradually.
- Test WhatsApp-focused retargeting campaigns.
- Build InitiateCheckout custom audience.
- Implement Offline Events tracking for showroom + WhatsApp sales.
- Implement Meta CAPI later.

---

## 25 May 2026 — Haroon (Tracking + Optimization + WhatsApp Attribution)

### Meta Purchase Tracking
- Verified Purchase event successfully firing in Meta Events Manager.
- Confirmed Meta can now optimize using purchase data.

### WhatsApp Tracking Improvements
- Created Meta custom conversion:
  - WhatsApp Click
- Rule:
  - URL contains wa.me

### Direct WhatsApp Pixel Event
Added direct Meta Pixel event tracking in Shopify theme.liquid:

```html
fbq('trackCustom', 'WhatsAppClick')
```

---

## 22 May 2026 — Haroon (Eid Campaign Retargeting Setup)

### Campaign Setup Completed
- Completed full Meta campaign setup for Hand Tufted Rugs Collection Campaign
- Completed full Meta campaign setup for Jute Rugs Collection Campaign

### Jute Rugs Campaign — LIVE
- Budget: PKR 10,000/day
- Objective: Purchase / ROAS

#### Ad Set Structure
- Ad Set A = PKR 4,000/day
  - Major Cities
  - WV-60D audience
  - Static creatives

- Ad Set B = PKR 4,000/day
  - Major Cities
  - WV-60D audience
  - Video creatives

- Ad Set C = PKR 2,000/day
  - All Pakistan
  - ATC + IC + WV 60D
  - DPA / Catalog Retargeting

### Meta Tracking Status
- Meta Pixel active and verified
- PageView event firing
- ViewContent event firing
- Search event firing
- AddToCart event firing
- InitiateCheckout event firing

### WhatsApp Tracking
- Created Meta Custom Conversion:
  - Name: WhatsApp Click
  - Data Source: Imam Carpets - Shop
  - Action Source: Website
  - Event Type: All URL Traffic
  - Rule:
    - URL contains wa.me
  - Category: Contact

### Omnisend Recovery
- Omnisend abandoned cart workflow enabled
- Checkout trigger workflow enabled
- Cart trigger workflow enabled
- Recovery delay configured (20 mins)
- Exit conditions configured correctly

### Interakt Setup
- Interakt Shopify app connected
- Basic automations enabled:
  - Welcome
  - Out of Office
  - Delayed Response
- WhatsApp support active
- Advanced abandoned cart workflow not visible in current setup/plan

---

## KPI / ROAS Rules

### Day 1–2
Do not panic if purchases are low.

Monitor:
- CTR
- CPC
- AddToCart
- InitiateCheckout
- Landing Page Views

### Day 4 Rule
- Kill/pause ad sets below 1.5 ROAS

---

## Future Tracking Plan

### Offline Conversion Tracking
Future implementation planned for:
- WhatsApp sales attribution
- Showroom sales attribution
- Offline Events upload to Meta

### Planned Workflow
1. Customer clicks Meta ad
2. Customer opens WhatsApp / showroom inquiry
3. Team records:
   - Customer name
   - Phone number
   - Product
   - Order amount
   - Date
   - Source
4. Upload offline conversions into Meta Offline Events

### Future Scaling Plan
- Build WhatsApp custom audiences
- Build ATC audiences
- Build IC audiences
- Build Purchaser audiences
- Build Video Viewer audiences
- Launch Lookalikes later

---

## Current Focus
- Meta campaign monitoring
- KPI / ROAS reporting
- WhatsApp conversion tracking
- Omnisend recovery optimisation
- Creative testing:
  - minimalist angle
  - luxury angle
- Daily campaign analysis
