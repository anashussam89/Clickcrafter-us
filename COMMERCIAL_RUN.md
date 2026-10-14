# ClickCrafters Vortex Water Air Purifier — Commercial Run Package

Run date: 2026-10-14 (scheduled autonomous pipeline)
Status: **BLOCKED — not generated.** Higgsfield balance 17.95 credits; locked render costs 63.
No job was submitted; nothing was charged.

## Blockers

1. **Insufficient credits.** Preflight (`get_cost`, no submission):
   - `seedance_2_0` · 720p · 9:16 · 14s · audio on · 9 refs = **63 credits**
   - same at 480p = **42 credits**
   - Balance: **17.95** (plan: Plus). No credit-reset offer available.
2. **`mode: fast` not enabled on this account.** `models_explore(get, seedance_2_0)` reports
   `mode.options: ["std"]`. Sending `mode: "fast"` returns
   `adjustments.params.mode = {requested: "fast", used: "std", reason: "not in [std]; using model default"}`.
   So "Seedance 2.0 Fast" cannot currently be ordered here even with credits.

## To resume
Top up Higgsfield credits (~63+), enable fast mode, then submit the exact call below.
The reference images are already imported — the media IDs are live and reusable.

---

## Locked generation call

```json
{
  "model": "seedance_2_0",
  "mode": "fast",
  "resolution": "720p",
  "aspect_ratio": "9:16",
  "duration": 14,
  "count": 1,
  "generate_audio": true,
  "use_unlim": false,
  "medias": [
    {"role": "image_references", "value": "1f4f7c41-9916-43ba-aade-4f7ff7587cb6"},
    {"role": "image_references", "value": "9e07ec4f-6192-44b4-9901-b42f5016967e"},
    {"role": "image_references", "value": "cc3a5569-987a-43c9-b67e-df9df3452b7a"},
    {"role": "image_references", "value": "88922163-a862-4819-b427-e9bdf19af295"},
    {"role": "image_references", "value": "7a8ab5b4-79c0-468a-b262-b0de5d62e724"},
    {"role": "image_references", "value": "11df6579-42c1-4f68-8b29-ac9d1f16a048"},
    {"role": "image_references", "value": "4b68e329-817b-4483-b35f-0192b58e8dbe"},
    {"role": "image_references", "value": "04b9a50d-f3ea-40fb-a71a-1dccb7d2880c"},
    {"role": "image_references", "value": "47f95499-45a1-45dd-bbd0-26469827c85d"}
  ]
}
```

### Reference image map (hero first)

| Slot | media_id | Source file | Role in the cut |
|---|---|---|---|
| `@image_1` | `1f4f7c41-9916-43ba-aade-4f7ff7587cb6` | `Air purifier black.jpeg` | Hero — front-on, violet glow, both logos legible. Opening + final packshot. |
| `@image_2` | `9e07ec4f-6192-44b4-9901-b42f5016967e` | `Air Purifier IMG2.jpeg` | Ultra-macro logo detail on clear basin. |
| `@image_3` | `cc3a5569-987a-43c9-b67e-df9df3452b7a` | `Air Purifier IMG1.jpeg` | Three-quarter angle, violet glow. Rotate-to-reveal. |
| 4 | `88922163-a862-4819-b427-e9bdf19af295` | `Air Purifier IMG3.jpeg` | Studio, clear-basin variant. Identity lock. |
| 5 | `7a8ab5b4-79c0-468a-b262-b0de5d62e724` | `Air Purifier IMG4.jpeg` | Clear variant, white internal core visible. |
| 6 | `11df6579-42c1-4f68-8b29-ac9d1f16a048` | `Air Purifier IMG5.jpeg` | Scale/held reference. |
| 7 | `4b68e329-817b-4483-b35f-0192b58e8dbe` | `Air Purifier IMG6.jpeg` | Dome top-down detail. |
| 8 | `04b9a50d-f3ea-40fb-a71a-1dccb7d2880c` | `Air Purifier IMG7.jpeg` | In-situ nightstand, side profile. |
| 9 | `47f95499-45a1-45dd-bbd0-26469827c85d` | `Air Purifier IMG8.jpeg` | In-situ, lid-lift interaction. |

Graceful degradation if a 9-image call errors: retry once with slots 1, 2, 3, 5 (hero first).

---

## Concept lock (Phase 1)

- **Lane:** Sensory ASMR macro — matched to the product's calm/clean emotional promise.
  Motion stays graceful throughout; the brief's vortex is explicitly kept soft, never a tornado.
- **Research signal:** sensory maximalism / "SenseMaxxing" named 2026 trend of the year;
  ASMR product demos outperform standard unboxing on watch time and completion; Pinterest
  Predicts 2026 leans glossy, tactile, comfort-forward against overstimulation.
- **Palette:** *Violet Dusk* — indigo-violet glow, graphite black, water-clear, warm amber accent.
- **Motifs (5):** amber oil droplet blooming in water · condensation beads on the clear basin ·
  indigo light shafts through water · drifting lavender and eucalyptus sprigs · silver dust motes
  sinking into a gentle swirl.
- **Cuts:** 9. **Audio:** calm ambient pad + close-mic water-bubble ASMR + airy whoosh on reveal.

---

## Prompt (Phase 2 — paste verbatim)

14-second premium photoreal product commercial, vertical 9:16, calm off-screen narrator voiceover, sensory ASMR macro camera moves with slow luxe speed-ramps.

Product reference @image_1 matches the ClickCrafters Vortex Water Air Purifier: a matte-black, finely pebbled-texture dome top with five curved arcing air slits, seated on a clear, bulbous, glass-like rounded water basin filled with tap water; a soft violet-indigo LED glow rises from inside the basin up through the water; the white "ClickCrafters" wordmark with its small equaliser-bar icon is printed low on the black dome, and a second indigo "ClickCrafters" wordmark is printed across the front of the clear basin.

One coherent calm night-ritual world across 9 fast cuts, unified by an amber essential-oil droplet blooming in water, condensation beads crawling on the clear basin, drifting lavender and eucalyptus sprigs, and fine silver dust motes sinking into a gentle swirl — in a violet-dusk grade of indigo, graphite black and water-clear with warm amber accents.

Beat 1: extreme ultra-macro, a single amber essential-oil droplet falls and blooms into still water, violet light refracting through it. Beat 2: fine silver dust motes drift down through a shaft of indigo light and are drawn into a soft, slow swirl at the water's surface. Beat 3: a smooth whip-orbit sweeps around the softly glowing violet basin, caustics sliding across a dark stone tabletop. Beat 4: the hero unit @image_1 glides into frame through low scented vapour, a clean specular highlight travelling across the matte-black dome. Beat 5: ultra-macro tracks condensation beads across the clear basin and settles on the @image_2 ClickCrafters logo detail, crisp and readable. Beat 6: snap to a macro of the curved air slits on the dome as a fine thread of vapour curls out. Beat 7: the unit rotates roughly 25 degrees into the @image_3 three-quarter angle, revealing its full form as the violet glow swells gently. Beat 8: sensory payoff — a soft bloom of scented vapour lifts and lavender and eucalyptus sprigs drift slowly around the unit. Beat 9: final lock-off hero packshot, the unit centred and perfectly still on a dark stone surface, both ClickCrafters logos clean and clearly readable, a soft violet halo behind it, a few droplets and petals drifting — held for the last 2 seconds.

Voiceover (Strict English): calm, premium off-screen female narrator, natural English, no on-camera speaker: "Dust settles. Water catches it. No filters to buy — just a quiet basin that turns a whole room into clean, scented air by morning. ClickCrafters. Breathe the difference — link in bio." Audio: a calm ambient pad with close-mic water-bubble ASMR, a soft airy whoosh on the reveal and a low sub-bloom on the final packshot, all sitting under the narration.

Premium studio lighting, cinematic violet-dusk grade, 4K look, shallow depth of field, tasteful motion blur, no rendered on-screen text, subtitles, captions or watermarks; English narration only, absolutely zero Chinese voiceover or foreign dubbing.

Identity lock: the ClickCrafters purifier @image_1 stays one intact, undeformed piece moving rigidly throughout — it never morphs, melts, bends, stretches or changes proportions, the dome stays matte black with its curved slits, the basin stays clear, and both ClickCrafters logos stay intact and readable. Water, glow, vapour, petals and particles may move freely, but the unit itself stays rigid, and the water swirl stays soft, slow and gentle — never a tornado, never a violent spin.

---

## Phase 3 — publish caption (TikTok + Instagram, same single video)

> No filters. Just water, light, and quieter air by morning. 🌙
> ClickCrafters Vortex Water Air Purifier — pour in your favourite oil and let the basin do the rest.
> https://clickcrafters.us
>
> #airpurifier #aromatherapy #cleanhome #asmr #nightstandessentials #petownersofinstagram

**Store URL is an assumption.** The product brief contains no store link; `https://clickcrafters.us`
was inferred from the repo name and brand. Replace before posting if incorrect.

## Pre-render self-check
1. Format line + 9:16 — yes · 2. Dense identity description incl. both logos — yes ·
3. Palette + 5 motifs + 9 cuts — yes · 4. Ends on a still, logo-readable packshot held ~2s — yes ·
4b. Narrator VO, 31 words, English, tagline + soft CTA — yes · 5. Identity-lock clause — yes ·
6. Soft swirl, no exaggeration — yes · 7. No rendered on-screen text — yes ·
8. All 9 repo images in `medias`, hero first, @image_1/2/3 referenced across the beats — yes ·
9. Params `seedance_2_0` + `mode: fast` + 720p + 9:16 + 14s — sent as specified
   (server coerces `fast` → `std` until fast mode is enabled on the account).

---

## Phase 3 — Buffer targets (verified live, read-only)

Organization: **My Organization** (`69f366a0237ef02c98a15d61`) · timezone America/New_York ·
scheduled-post limit 10.

| Platform | Handle | channelId | Connected |
|---|---|---|---|
| TikTok | `clickcraftters` | `69f366d15c4c051afaf72730` | yes |
| Instagram | `clickcraftersus` | `6a20346cc687a22dd4577385` | yes |

The org also holds an Instagram channel `ai_fahm` (`6acd68f7778b240e2feee369`) — **not** this brand,
do not post to it.

Post the single Seedance video to both channels with `create_post` (`addToQueue`), same caption.
