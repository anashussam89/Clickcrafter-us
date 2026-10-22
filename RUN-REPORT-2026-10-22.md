# Commercial Video Pipeline — run 2026-10-22 11:17 UTC

## Status: BLOCKED before render. Nothing generated, nothing posted.

### Blocker 1 — out of Higgsfield credits
- Quote for the locked spec (seedance_2_0, 720p, 9:16, 14s, audio, 1 count): **63 credits**
- Workspace balance: **9.95 credits** (private workspace, Plus plan) — short by ~53
- Submission returned: `Error starting generation: Out of credits in the selected workspace.`
- Only one workspace exists, so there is no other balance to bill against.
- Top-up requires a purchase; not done autonomously.

### Blocker 2 — `mode: fast` is not offered on this account
`models_explore(seedance_2_0)` lists `mode` options as `["std"]` only, and the cost preflight
returned this adjustment:

    params.mode: requested "fast" -> used "std" (not in [std]; using model default)

So "Seedance 2.0 Fast" cannot actually be requested here — the API silently falls back to
`std`, which is the slower/more expensive mode. The routine's spec needs either fast mode
enabled on the account or the locked spec changed to `std`.

### Healthy / verified this run
- All 9 repo images imported to Higgsfield as media ids, hero first.
- Buffer: org `My Organization` (69f366a0237ef02c98a15d61); TikTok **clickcraftters**
  (`69f366d15c4c051afaf72730`) and Instagram **clickcraftersus** (`6a20346cc687a22dd4577385`)
  both connected, neither disconnected or locked. Publish step would have worked.

### Open assumption
The product brief contains **no store URL**. Nothing in the repo or its git history has one, and
no ClickCrafters storefront was findable. The caption below uses `clickcrafters.us` derived from
the repo name — **verify or replace before this ships.**

---

## Imported reference media ids (reusable, hero first)

| # | File | media_id |
|---|------|----------|
| 1 (hero) | Air purifier black.jpeg | 3e908f3f-ac7a-4165-bce3-1986e489c217 |
| 2 | Air Purifier IMG1.jpeg | de3243ee-7a43-4409-ac34-945ae6528624 |
| 3 | Air Purifier IMG4.jpeg | c3be0730-c063-4903-8939-1874ed53c9f2 |
| 4 | Air Purifier IMG2.jpeg | fc86bbc7-98ce-467b-8089-963399b4d0ba |
| 5 | Air Purifier IMG3.jpeg | 0e268fcb-a1b8-4457-9323-973b42a9f6d0 |
| 6 | Air Purifier IMG5.jpeg | f35b966b-9633-48a4-b6ad-6bf21b755ca4 |
| 7 | Air Purifier IMG6.jpeg | 3c00195b-3020-4d75-9498-8dc4ecd565ce |
| 8 | Air Purifier IMG7.jpeg | 04d318d1-519b-48fa-be13-aabdb5ce7388 |
| 9 | Air Purifier IMG8.jpeg | 4fa37ee9-b90f-4d16-9b2f-d7a5f03d2393 |

## Concept locked this run
- **Lane:** Sensory ASMR macro + slow-ritual speed-ramps (matched to the product's calm/wellness
  promise; backed by the 2026 "SenseMaxxing" tactile-sensory trend and the research finding that
  slow motion reads as luxury).
- **Palette:** Amethyst Dusk — charcoal / deep indigo / violet glow, pearl-white highlights,
  warm amber accents.
- **Motifs:** amber oil droplets blooming in water · violet-indigo internal glow · condensation
  beads on clear glass · drifting lavender + eucalyptus sprigs.
- **Cuts:** 9, ending on a 2s still logo-readable packshot.
- **Audio:** low warm pads + soft piano, water-bubble ASMR, droplet plink, airy whoosh on reveal.

## Final prompt (ready to resubmit as-is once credits are topped up)

14-second premium photoreal product commercial, vertical 9:16, calm off-screen narrator voiceover, sensory ASMR macro with slow-ritual speed-ramps and gentle orbiting camera moves. Product reference @image_1 matches a ClickCrafters Vortex Water Air Purifier: a matte-black, finely textured dome-shaped top with five curved air slits, seated on a clear bulbous glass-like water basin filled with tap water, lit from within by a soft violet-indigo LED glow, with the white 'ClickCrafters' wordmark and small equalizer-bar icon printed on the black dome and a violet-blue 'ClickCrafters' wordmark printed on the clear basin; cool condensation beads cling to the inside of the glass. One coherent calm nightstand-ritual world across 9 fast cuts, unified by amber essential-oil droplets blooming through water, a soft violet-indigo internal glow, condensation beads on clear glass, and drifting lavender and eucalyptus sprigs, in an Amethyst Dusk grade of charcoal and deep indigo with pearl-white highlights and warm amber accents.

Beat 1: extreme ultra-macro, a single amber essential-oil droplet falls in slow motion and kisses a still water surface, the impact crown ringing outward. Beat 2: speed-ramp as the amber drop blooms and unfurls into the water in silky ribbons, backlit violet. Beat 3: fine household dust motes drift down and are drawn gently into a soft, slow swirl of water, vanishing beneath the surface. Beat 4: a smooth orbit sweeps around the softly glowing violet basin, light refracting through the water. Beat 5: the hero unit @image_1 glides into frame through a low veil of cool mist and settles, a clean specular highlight tracing across the matte dome. Beat 6: ultra-macro tracks a bead of condensation sliding down the clear glass and comes to rest on the printed ClickCrafters wordmark on the basin, holding on the crisp logo detail of @image_2. Beat 7: snap to a tight detail of the curved vents on the black dome, cool air breathing through them. Beat 8: the unit rotates roughly 22 degrees in a slow reveal of its full silhouette using the angle of @image_3, the internal glow swelling softly from indigo to violet. Beat 9: sensory payoff, a fine bloom of scented vapor rises and curls around the unit while lavender and eucalyptus sprigs drift weightlessly past. Final lockoff hero packshot: the unit centered and perfectly still on a dark stone nightstand, the ClickCrafters logo clean and clearly readable on both the dome and the basin, a soft violet halo behind it, a few suspended droplets and petals hanging in the air, held for the last 2 seconds.

Voiceover (Strict English): calm, premium off-screen female narrator, natural English, no on-camera speaker and no lip-sync: 'Air you can actually see getting cleaner. Dust and dander, pulled down into water. No filters to buy, ever. Just pour, glow, and breathe. ClickCrafters. Clean air, quietly.' Paced evenly across the 14 seconds, the brand line and soft call to action landing on the final packshot. Audio: a calm ambient music bed of low warm pads and soft piano, with gentle water-bubble ASMR, a delicate droplet plink and a soft airy whoosh on the reveal, all mixed under the narration.

Premium studio lighting with soft gradient falloff, cinematic Amethyst Dusk grade, 4K look, shallow depth of field and tasteful motion blur; no rendered on-screen text, subtitles, captions or watermarks anywhere in frame; absolutely zero Chinese voiceover or foreign dubbing, English narration only.

Identity lock: the ClickCrafters purifier @image_1 stays one intact, undeformed, rigid piece throughout, moving only as a solid object; it never morphs, melts, bends, stretches or changes proportions, the matte-black dome and clear basin keep their exact shapes and finishes, and the ClickCrafters logo stays intact, correctly spelled and readable. Water, glow, mist, droplets and botanicals may move freely, but any water swirl stays soft, slow and gentle, never a tornado, never a violent spin, never splashing over the rim.

## Caption prepared for both channels

Water does the filtering. You just breathe.
Dust, dander and odour pulled down into the basin — no filters to replace, ever.
Pour in your favourite oil and let the room reset.
https://clickcrafters.us   <-- UNVERIFIED, confirm before posting

#waterairpurifier #cleanairathome #aromatherapy #petownermusthaves #nightstandessentials #asmrhome
