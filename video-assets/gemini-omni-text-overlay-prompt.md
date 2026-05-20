# Gemini Omni Prompts — Text Overlay Only (3 runs: 10s + 10s + 3s = 23s)

> Workflow: 3 separate Omni runs. Each run attaches its own reference clip. Omni's job = ONLY add text overlay on top of the attached clip. Do NOT generate new visuals, new scenes, new motion. Just text on existing footage. Stitch the 3 outputs in CapCut after.

> Time stamps below are LOCAL to each clip (0s = start of that clip).

---

## RUN 1 — First 10 seconds (attach Clip 1)

```
You are given a 10-second vertical 9:16 tufted rug video. DO NOT modify the footage. DO NOT generate new visuals, change colour grade, alter motion, or extend length. Output length must equal input length exactly (10.0 seconds).

Your ONLY task: burn in white bold sans-serif text overlays at the exact timings below. Font: Anton, Bebas Neue, or Inter Black. Pure white text with a soft black drop shadow (or translucent black pill behind text) for mobile readability. Smooth 0.2s fade in and 0.2s fade out on every card. No two cards overlap. Spelling exact — do not warp, hallucinate, or auto-correct letters.

TEXT BEATS:

- 0.0–2.5s — CENTRE, large
  Line 1: HAND TUFTED RUGS
  Line 2 (smaller, italic): Made in Pakistan

- 2.5–6.0s — CENTRE, very large. Add deep-red underline under "30% OFF" only.
  Line 1: 30% OFF
  Line 2 (smaller): Eid Sale — All 40 designs

- 6.0–10.0s — LOWER THIRD
  Line 1: Wool + viscose
  Line 2 (smaller, italic): Loop by loop. By hand.

NEGATIVE: no extra text, no subtitles, no watermarks, no captions, no emojis, no logos, no neon/glow, no spinning, no spelling variants, no language other than English. Do not re-render the footage.

OUTPUT: 9:16 vertical 1080×1920, 24fps, 10.0 seconds, MP4.
```

---

## RUN 2 — Middle 10 seconds (attach Clip 2)

```
You are given a 10-second vertical 9:16 tufted rug video. DO NOT modify the footage. DO NOT generate new visuals, change colour grade, alter motion, or extend length. Output length must equal input length exactly (10.0 seconds).

Your ONLY task: burn in white bold sans-serif text overlays at the exact timings below. Font: Anton, Bebas Neue, or Inter Black. Pure white with soft black drop shadow. 0.2s fade in / 0.2s fade out per card. No overlap. Spelling exact.

TEXT BEATS (timings are LOCAL to this 10-sec clip):

- 0.0–3.5s — LOWER THIRD
  Line 1: 70+ years of handmade rugs
  Line 2 (smaller): Imam Carpets, since 1952

- 3.5–7.0s — LOWER THIRD
  Line 1: Free delivery all Pakistan
  Line 2 (smaller): Karachi — same day

- 7.0–10.0s — CENTRE, in deep red (not white)
  Single line: Ends 26 May — Midnight

NEGATIVE: no extra text, no subtitles, no watermarks, no emojis, no logos other than the words "Imam Carpets" inside the first card, no neon, no spelling variants, no extra languages. Do not re-render the footage.

OUTPUT: 9:16 vertical 1080×1920, 24fps, 10.0 seconds, MP4.
```

---

## RUN 3 — Final 3 seconds (attach Clip 3)

```
You are given a 3-second vertical 9:16 tufted rug video. DO NOT modify the footage. DO NOT generate new visuals or extend length. Output length must equal input length exactly (3.0 seconds).

Your ONLY task: burn in a single end-card text overlay, full duration.

TEXT BEAT:

- 0.0–3.0s — CENTRE, very large, white bold sans-serif (Anton / Bebas / Inter Black), soft black drop shadow. Hold full duration with a 0.2s fade in only (no fade out).
  Line 1: SHOP NOW
  Line 2 (smaller): imamcarpets.com

NEGATIVE: no extra text, no subtitles, no watermarks, no emojis, no logos other than the words inside the card, no neon, no spinning. Do not re-render the footage.

OUTPUT: 9:16 vertical 1080×1920, 24fps, 3.0 seconds, MP4.
```

---

## Stitching (CapCut / Premiere)
1. Drop Run 1 → Run 2 → Run 3 on the timeline in order, no transition.
2. Hard cut between each. Total = 23.0s exactly.
3. Add music bed: soft oud + light tabla, low BPM, royalty-free. Volume −18dB.
4. Export 1080×1920 H.264, then 1:1 + 4:5 reframes for Meta feed.

## QA Before Shipping
- [ ] Run 1: 3 cards present, "30% OFF" has red underline
- [ ] Run 2: "Ends 26 May — Midnight" is in red
- [ ] Run 3: "SHOP NOW / imamcarpets.com" holds full 3 sec
- [ ] No spelling errors / warped letters anywhere (re-gen if any)
- [ ] Total stitched length = 23.0s exact
- [ ] No phantom subtitles or extra logos
- [ ] Mobile preview readable, captions not cut off by safe-area

## Owner
- Run prompts + stitch: **Zubair** (or Shahzaib).
- QA + approval: **Shahzaib**.
- Meta upload (BM 145166706590306 / Ad account 2130004033776229): **Haroon**.
