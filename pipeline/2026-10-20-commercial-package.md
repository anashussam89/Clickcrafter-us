# Commercial Video Package — 2026-10-20 (render BLOCKED on credits)

Status: creative locked, references imported, **render not submitted** — Higgsfield
workspace had 9.95 credits against a 63-credit cost. Re-run once credits are topped up;
everything below is ready to fire as-is.

## Locked params
- model_id: `seedance_2_0`
- mode: `fast` — **NOTE:** this account's Seedance 2.0 catalog exposes `mode: ["std"]`
  only. The API silently coerces `fast` -> `std`
  (`params.mode: {requested: fast, used: std, reason: "not in [std]; using model default"}`).
  Needs resolving with Higgsfield before a true "Fast" render is possible here.
- resolution: 720p · aspect_ratio: 9:16 · duration: 14 · count: 1 · generate_audio: true

## Cost preflight
- 720p / 14s / 9:16: **63 credits**
- 480p / 14s / 9:16: 42 credits
- Workspace balance: 9.95 (plan: plus, single workspace)

## Concept (rotated lane: Sensory ASMR macro)
- Theme: "Still Water Hour" — a calm nightstand ritual.
- Palette: Indigo Dusk (violet-indigo, slate black, water-clear) with warm amber accents.
- Motifs: amber oil droplet blooming in water · condensation beads on the clear basin ·
  fine scent-vapor ribbons · dust motes drawn into a slow soft swirl · internal violet glow.
- Cuts: 9 · Audio: low ambient pad + water-bubble ASMR under the narration.

## Reference media (Higgsfield media_ids, hero first — all 9 repo images)
| # | file | media_id |
|---|------|----------|
| @image_1 (hero) | Air purifier black.jpeg | d2344493-4d39-40e1-bb50-8d2569dcd112 |
| @image_2 (logo macro) | Air Purifier IMG2.jpeg | 1d452f0a-2aad-4375-83d7-38aea64b2cd2 |
| @image_3 (3/4 violet) | Air Purifier IMG1.jpeg | ded2fa9e-48a7-4874-b0dc-97aebbf109db |
| 4 | Air Purifier IMG3.jpeg | 734eb174-6317-4d9e-8486-2ce4d4df8714 |
| 5 | Air Purifier IMG4.jpeg | 6ac5acc0-15ef-4545-b25d-5904966a8e08 |
| 6 | Air Purifier IMG7.jpeg | 9727c670-f6c2-44f4-b98b-6bd47a901fc5 |
| 7 | Air Purifier IMG5.jpeg | fe740377-cc8e-4ae7-ba86-ef965a0edd40 |
| 8 | Air Purifier IMG6.jpeg | 2e52a514-0c71-4077-95d7-e044ff24ec78 |
| 9 | Air Purifier IMG8.jpeg | 64bcacce-3f8a-4608-ae51-0cfb1fd9da64 |

All passed with role `image_references`.

## Prompt (verbatim, ready to submit)

14-second premium photoreal product commercial, vertical 9:16, calm off-screen narrator
voiceover, sensory ASMR macro camera moves with slow luxe speed-ramps. Product reference
@image_1 matches a ClickCrafters water air purifier: a matte-black, finely textured
dome-shaped top with four curved air slits, seated on a clear bulbous rounded water basin
filled with still tap water, lit from within by a soft violet-indigo LED glow that tints the
water; the white 'ClickCrafters' wordmark with its small bar-graph icon is printed on the
front of the black dome and again on the front of the clear basin. One coherent 'Still Water
Hour' nightstand world across 9 slow cuts, unified by amber essential-oil droplets blooming
in water, condensation beads crawling down the clear basin, and fine scent vapor ribbons, in
an indigo-dusk grade with warm amber accents.

Beat 1: ultra-macro, a single amber oil droplet falls in slow motion and breaks the still
water surface, rings spreading. Beat 2: macro underwater, the amber bloom unfurls into the
violet-lit water in soft ribbons. Beat 3: fine dust motes drift through a dark room and are
drawn gently downward into a slow, soft swirl at the water's surface. Beat 4: a smooth low
orbit sweeps around the glowing basin, violet light raking across the table. Beat 5: the hero
unit @image_1 glides into frame through thin drifting vapor, a clean specular highlight
sliding across the matte-black dome. Beat 6: ultra-macro tracks condensation beads across the
clear basin and settles on the crisp 'ClickCrafters' wordmark as in @image_2, then snaps to
the curved air slits of the dome. Beat 7: the unit rotates about 22 degrees to the
three-quarter view seen in @image_3, the internal violet glow swelling gently. Beat 8: a soft
bloom of scented vapor rises and curls around the unit while lavender and eucalyptus sprigs
drift slowly past. Beat 9: final lockoff hero packshot, the unit centered and perfectly still
on a dark stone nightstand, the ClickCrafters logo on dome and basin clean and clearly
readable, a soft violet halo behind it and slow drifting vapor, held for the last 2 seconds.

Voiceover (Strict English): calm, premium off-screen female narrator, natural English, no
on-camera speaker and no lip-sync: 'Dust settles. Air clears. A single basin of water quietly
catches what you breathe — no filters, ever. Just a soft violet glow, and the sound of still
water. ClickCrafters. Clean air, poured fresh. Pour yours tonight.' Paced evenly across the
14 seconds, the tagline and call to action landing on the final packshot. Audio: a calm low
ambient pad with gentle water-bubble ASMR, a soft droplet plink on the opening beat and an
airy whoosh on the reveal, all sitting under the narration.

Premium studio lighting, cinematic indigo-dusk grade, 4K look, shallow depth of field,
tasteful motion blur, no rendered on-screen text, subtitles, captions or watermarks; English
narration only, absolutely zero Chinese voiceover or foreign dubbing. Identity lock: the
ClickCrafters purifier @image_1 stays one intact, undeformed piece moving rigidly throughout
— it never morphs, melts, bends, stretches or changes proportions, the dome stays matte black
and the basin stays clear, and the ClickCrafters logo stays intact and readable on both
parts. Water, glow, vapor and particles may move freely, but any water swirl stays soft, slow
and gentle — never a tornado, never a violent spin.

## Caption (TikTok + Instagram Reels, same copy)

No filters. No cartridges. Just water doing the quiet work.
A soft violet glow, a still basin, and air that finally feels clean by morning.
Pour it, plug it in, rinse it tomorrow.
clickcrafters.us
#airpurifier #cleanair #homereset #aromatherapy #nightstandessentials #asmrhome

**URL caveat:** the product brief carries no store URL and no prior run recorded one.
`clickcrafters.us` is inferred from the brand name and the repo name (`Clickcrafter-us`)
and could NOT be verified from this sandbox (egress proxy blocks non-allowlisted hosts).
Confirm or replace before this caption ships, and add the real URL to the brief so
future runs stop guessing.

## Publish targets (verified live this run)
- Buffer org: `69f366a0237ef02c98a15d61` ("My Organization", tz America/New_York)
- TikTok: `clickcraftters` -> `69f366d15c4c051afaf72730`
- Instagram: `clickcraftersus` -> `6a20346cc687a22dd4577385`
- Both connected, not disconnected or locked. Mode: addToQueue, schedulingType: automatic,
  IG metadata: {type: reel, shouldShareToFeed: true}, isAiGenerated: true.
