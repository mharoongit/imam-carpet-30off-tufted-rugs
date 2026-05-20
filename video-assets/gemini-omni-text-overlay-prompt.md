# Gemini Omni Prompt — Add Text Overlay to Tufted Rugs Video

> Use case: 10-sec reference clip already attached. Omni should EXTEND clip to 23s and burn in 7 text beats. No new scenes, no new locations — keep the look, lighting, colour grade, and pace of the reference clip.

---

## Master Prompt (paste into Gemini Omni)

```
Using the attached 10-second reference clip of hand-tufted rugs as the visual anchor, generate a 23-second vertical 9:16 video that keeps the exact same look, lighting, colour grade, lens, and pacing of the reference. Do NOT invent new locations, props, or models — extend the existing clip naturally, loop or slow-mo sections where needed to reach 23 seconds.

Match the reference for: colour palette, depth of field, camera movement style, rug texture rendering, and overall premium feel.

Your only job beyond extending is to BURN IN ON-SCREEN TEXT across 7 timed beats. Text must be bold sans-serif (Anton, Bebas Neue, or Inter Black), pure white, with a soft black drop shadow OR a translucent black pill behind the text for readability. Centre-aligned for hook/offer/urgency/CTA. Lower-third for proof/trust/delivery. Smooth fade-in (0.2s) and fade-out (0.2s) on each card. Never let two cards overlap. Spelling MUST be exact — do not warp or hallucinate letters.

TIMED TEXT BEATS:

- 0.0–2.5s — centre, big
  Line 1: HAND TUFTED RUGS
  Line 2 (smaller, italic): Made in Pakistan

- 2.5–6.0s — centre, huge, deep-red underline under "30% OFF"
  Line 1: 30% OFF
  Line 2 (smaller): Eid Sale — All 40 designs

- 6.0–10.0s — lower third
  Line 1: Wool + viscose
  Line 2 (smaller, italic): Loop by loop. By hand.

- 10.0–13.5s — lower third
  Line 1: 70+ years of handmade rugs
  Line 2 (smaller): Imam Carpets, since 1952

- 13.5–17.0s — lower third
  Line 1: Free delivery all Pakistan
  Line 2 (smaller): Karachi — same day

- 17.0–20.0s — centre, red
  Single line: Ends 26 May — Midnight

- 20.0–23.0s — centre, very big
  Line 1: SHOP NOW
  Line 2 (smaller): imamcarpets.com

NEGATIVE: no extra text other than the 7 beats above, no watermark, no spelling variants, no glow/neon effects, no spinning text, no emoji, no logos other than the words "Imam Carpets" inside beat 4, no caption-style subtitles, no auto-generated subtitles, no extra languages.

OUTPUT: 9:16 vertical, 1080×1920, 23.0 seconds, 24fps, MP4.
```

---

## Shorter Prompt (if char limit)

```
Extend the attached 10-sec tufted rug reference clip to 23 sec, keeping the exact same look, grade, and pace. Burn in 7 white bold sans-serif text beats with thin black shadow, spelling exact, no warping:
(1) 0.0–2.5s centre "HAND TUFTED RUGS / Made in Pakistan"
(2) 2.5–6.0s centre huge "30% OFF / Eid Sale — All 40 designs" (red underline on 30% OFF)
(3) 6.0–10.0s lower-third "Wool + viscose / Loop by loop. By hand."
(4) 10.0–13.5s lower-third "70+ years of handmade rugs / Imam Carpets, since 1952"
(5) 13.5–17.0s lower-third "Free delivery all Pakistan / Karachi — same day"
(6) 17.0–20.0s centre red "Ends 26 May — Midnight"
(7) 20.0–23.0s centre big "SHOP NOW / imamcarpets.com"
Smooth 0.2s fade in/out, no overlap, no extra text, no watermark, no neon, no emoji. 9:16 1080×1920 24fps 23.0s MP4.
```

---

## QA Checklist Before Shipping
- [ ] All 7 beats present in correct order
- [ ] No spelling errors / warped letters (re-gen if any)
- [ ] "30% OFF" has red underline
- [ ] "Ends 26 May — Midnight" is red
- [ ] CTA last 3 sec reads cleanly on mobile preview
- [ ] No overlap between cards
- [ ] Total length = 23.0s exactly
- [ ] No phantom subtitles / extra logos

## Owner
- Run prompt: **Zubair** (or Shahzaib).
- QA + approval: **Shahzaib**.
- Upload to Meta Ads (BM 145166706590306 / Ad account 2130004033776229): **Haroon**.
