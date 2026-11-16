# Commercial Video Pipeline — run 2026-11-16 (BLOCKED: out of credits)

**Status:** Phases 0–2 complete. Phase 2 generation refused by Higgsfield: `Out of credits in the selected workspace.` Nothing was rendered, nothing was published, no credits were spent.

## Blocker
| | |
|---|---|
| Higgsfield balance | **28.5 credits** (plan: Plus) |
| Cost, locked spec (seedance_2_0, 720p, 9:16, 14s, audio) | **63 credits** |
| Cost at 480p/14s (fallback, still over budget) | 42 credits |
| Shortfall | ~35 credits |

Nothing at the locked 14s length fits inside 28.5 credits at any resolution, so the run could not be degraded into a usable deliverable either.

### Second issue: `mode: fast` is not available to this account
`models_explore(seedance_2_0)` reports `mode` options as `["std"]` only, and the API silently coerces the request:
`params.mode: {requested: "fast", used: "std", reason: "not in [std]; using model default"}`

The Plus plan page *does* list "Seedance 2.0 Fast — FULL ACCESS", so this looks like an MCP-surface gap rather than a plan limit. `std` is what drives the 63-credit price; `fast` would be cheaper. Worth raising with Higgsfield — if `fast` becomes reachable over MCP, the per-run cost drops and the current balance may well cover it.

## Also missing from the repo
The product brief has **no store URL**. `clickcrafters.us`, `.com` and `.co` do not resolve from this container. The caption below uses `clickcrafters.us` as a placeholder — **replace it before anything goes out.**

## Reference images — imported, ready to reuse
All 9 repo images pulled into Higgsfield from raw GitHub URLs (no upload needed). Hero first.

| # | File | media_id | Used as |
|---|---|---|---|
| 1 | Air purifier black.jpeg | `baec4bf8-7179-47f6-9ae0-331274e72c75` | **hero** — @image_1, open + final packshot |
| 2 | Air Purifier IMG2.jpeg | `f73eb3e6-c9a3-41ec-af00-9aa7336454bf` | @image_2 — macro logo detail beat |
| 3 | Air Purifier IMG4.jpeg | `977fdf61-f327-4d92-affc-245244d74607` | @image_3 — rotate-to-reveal beat |
| 4 | Air Purifier IMG1.jpeg | `34c8c275-7771-4409-a6fe-87e16bcab16a` | identity lock |
| 5 | Air Purifier IMG3.jpeg | `eb37bf92-06b9-45fa-9433-b05aa6102b3f` | identity lock |
| 6 | Air Purifier IMG5.jpeg | `75783ce5-3634-49ff-9216-dd3b75755a1a` | identity lock |
| 7 | Air Purifier IMG6.jpeg | `914c6210-aadd-4184-b5bc-1851a00b65ca` | identity lock |
| 8 | Air Purifier IMG7.jpeg | `0541bd38-bc7c-46a3-ba8e-47343ea4e8cb` | identity lock |
| 9 | Air Purifier IMG8.jpeg | `24373b18-4d8a-4ceb-96da-aa4916202b8d` | identity lock |

Seedance 2.0 caps `image_references` at 9, so all 9 fit exactly — none dropped.

## Locked creative direction
- **Lane:** sensory ASMR macro with slow-ritual restraint (matches the brief's calm/gentle hero effect — explicitly *not* a cyclone)
- **Palette:** midnight violet & pearl, warm amber accents
- **Motifs (5):** amber oil bloom in water · violet caustics through curved acrylic · condensation beads · fine scent vapor · drifting dust motes
- **Cuts:** 9, ending on a 2-second still packshot
- **Audio:** low ambient pad, soft water-bubble ASMR, droplet plink on open, airy whoosh on reveal, under the VO
- **VO (30 words, English):** "Your room breathes again. Dust, dander and odor pulled down into water. No filters to buy, ever. Just light, scent, and quiet. ClickCrafters. Air you can see. Bring one home."

## Params (resubmit exactly as-is once credits are topped up)
```
model: seedance_2_0 · mode: fast · resolution: 720p · aspect_ratio: 9:16
duration: 14 · count: 1 · generate_audio: true
medias: the 9 image_references above, in order
```

## Full prompt
14-second premium photoreal product commercial, vertical 9:16, calm off-screen narrator voiceover, sensory ASMR macro camera moves with slow elegant speed-ramps. Product reference @image_1 matches the ClickCrafters Vortex Water Air Purifier: a matte-black, finely pebble-textured dome-shaped top with five curved radiating air slits, seated on a bulbous rounded fully transparent acrylic basin filled with water that is lit violet-indigo from within; fine beads of condensation cling to the inner basin wall; the ClickCrafters wordmark with its small equalizer-bar icon is printed in white on the front of the black dome and in deep navy on the front of the clear basin. One coherent midnight-ritual world across 9 fast cuts, unified by an amber essential-oil bloom in water, violet caustic light refracting through curved acrylic, condensation beads, fine scent vapor and drifting dust motes, in a midnight-violet and pearl grade with warm amber accents.

Ultra-macro open: a single amber essential-oil droplet falls and breaks the still water surface inside the basin, a slow violet-lit ring spreading outward. Cut inside the water: the amber drop blooms into soft golden tendrils, a gentle slow swirl drawing them downward. Cut to backlit dust motes drifting in a dark room, pulled down toward the glow and vanishing at the waterline. A whip-orbit sweeps around the softly glowing basin, violet light refracting through the curved acrylic and sliding caustics across dark stone. The hero unit @image_1 glides into frame through a drifting veil of fine scent vapor, a clean specular highlight tracing the textured dome. Ultra-macro tracks across condensation beads on the clear acrylic and settles razor-sharp on the ClickCrafters wordmark @image_2. Snap to the matte-black dome's curved air slits, a single thread of vapor curling out of one slit in slow motion. The unit rotates about 22 degrees to reveal its full silhouette @image_3, the violet glow swelling gently from within as lavender and eucalyptus sprigs drift past in soft focus. Final lockoff hero packshot: the unit centered and perfectly still, both ClickCrafters logos crisp and clearly readable, a soft violet halo behind it, one last droplet and a drifting petal, held for the final 2 seconds.

Voiceover (Strict English): calm, premium off-screen female narrator, natural English, no on-camera speaker: 'Your room breathes again. Dust, dander and odor pulled down into water. No filters to buy, ever. Just light, scent, and quiet. ClickCrafters. Air you can see. Bring one home.' Paced evenly across the 14 seconds, landing the tagline and call to action on the final packshot. Audio: a calm low ambient pad with soft water-bubble ASMR, a single crisp droplet plink on the open and a gentle airy whoosh on the reveal, all sitting under the narration.

Premium studio lighting, cinematic midnight-violet and pearl grade, 4K look, tasteful motion blur, no rendered on-screen text, subtitles, captions or watermarks; English narration only, absolutely zero Chinese voiceover or foreign dubbing. Identity lock: the purifier @image_1 stays one intact, undeformed, rigid piece throughout, never morphing, melting, bending or changing proportions, and the ClickCrafters logo stays intact and readable; water, glow, vapor and particles may move freely, but the water swirl stays soft and gentle at its true calm intensity, never a tornado, never a violent spin.

## Caption (TikTok + Instagram, ready to post)
> No filters. No refills. Just water, light, and air you can actually see working.
> Drop in your favourite oil and let the room reset.
> clickcrafters.us  ← **placeholder, confirm the real store URL**
>
> #airpurifier #waterairpurifier #homereset #petodor #aromatherapy #cleanair

## What was NOT done
Phase 3 (Buffer → TikTok + Instagram) was never reached — there is no video to publish. No Buffer call was made.
