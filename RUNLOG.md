# Autonomous Commercial Pipeline — Run Log

Concept ledger for the scheduled Seedance commercial pipeline. Each run reads this
file to rotate the creative lane, palette and voiceover, so consecutive commercials
do not repeat. Append a new row at the top on every run.

| Date | Lane | Palette | Product variant | Hero ref | VO tagline | Job ID |
|---|---|---|---|---|---|---|
| 2026-10-06 | Element-in-motion | Porcelain Morning (bone white / sunlit cream / oak, pale clay accents) | Standard Monochrome (clear basin) | Air Purifier IMG4 | "Clean air you simply pour out." | f40df4a9-eed2-4937-beb8-0fbf3c217664 |
| 2026-10-04 | Smooth luxe / slow ritual | Midnight Amethyst | Purple UV glow | — | "Breathe your room back to life." | ac0b8ddb-18a1-40b7-b23c-a508d3442ebb |
| 2026-10-02 | Sensory ASMR | Midnight Violet Hush | Purple UV glow | — | "Breathe the difference." | d9d016f0-632c-42d8-a91d-e6ddb1d99a02 |
| 2026-09-30 | Sensory ASMR | Indigo Dusk | Purple UV glow | — | "Air you can see getting cleaner." | d40d4d9e-f348-4c44-aeaf-66260dd2248a |
| 2026-09-28 | Sensory ASMR | Midnight Lavender | Purple UV glow | — | "Breathe the difference." | 92c3c4e8-c6d7-42f9-a7cf-3ff9b217e247 |
| 2026-09-26 | Sensory ASMR | Dawn Eucalyptus | Purple UV glow | — | "Air, softened by water." | bdd32c6c-589f-4add-80c0-2bf37089a582 |

## Notes for the next run

- **Avoid repeating** the violet/indigo night-ritual world — it ran five times in a
  row (Sep 26 – Oct 4). The 2026-10-06 run broke that streak with a bright daylight
  treatment on the clear monochrome variant.
- **Unused lanes worth rotating to next:** hypermotion abundance, and a
  smooth-luxe treatment built on the *White Internal Filter* variant, which has not
  been used as a hero yet.
- **Model entitlement:** `seedance_2_0` with `mode: fast` is accepted but the API
  silently downgrades it — the response carries
  `adjustments: {params.mode: {requested: "fast", used: "std", reason: "not in [std]"}}`.
  Fast mode last actually ran on 2026-09-28. Every run since has rendered in `std`.
  This is an account entitlement issue, not a prompt problem.
- **Store URL:** https://clickcrafters-us.com — the product brief does not carry a
  link, so the caption uses the official store found for the ClickCrafters brand.

## 2026-10-06 run artifacts

- **Video (Seedance, 9:16, 720p, 14.08s, native audio):**
  `https://d8j0ntlcm91z4.cloudfront.net/user_3ECe42dMPbcksPXv9LgzY2fgZuJ/hf_20261006_111848_f40df4a9-eed2-4937-beb8-0fbf3c217664.mp4`
- **References:** all 9 repo images, hero `Air Purifier IMG4` (clear monochrome,
  front-on), `@image_2` = `Air Purifier IMG2` (logo macro), `@image_3` =
  `Air Purifier IMG3` (three-quarter angle).
- **Buffer posts** (one render reused for both, queued to each channel's next slot):
  - TikTok `clickcraftters` — post `6ac4db4dd2b2583c5a3e9317`, due 2026-10-06 11:44 UTC
  - Instagram `clickcraftersus` (Reel, shared to feed) — post `6ac4db56643068755bb1f318`, due 2026-10-06 21:23 UTC
- Both posts flagged `isAiGenerated: true`.
