# MERGE_NOTES — Port full-wheel atlas into planesbound.grok.me

Supplement only. Do **not** replace the Outer gazetteer. Keep back-link to `/?plane=lighthouse`.

## Main quest lock
- **Will-o’-wisp race** is the campaign spine (flickering lights without source: guide, mislead, or consume).
- Mineral / Ani progenitor aesthetic is a hearth of that race.
- Lore art batches in `art/lore/` are fuel for jump-points (portals, oaths, spells, artifacts, triad figures, Concordant Market, demon checkpoints, housing).
- **Compass Orb** is the party sat-phone / planar sat-link for the race.

## Suggested grok.me routes
| Local / concept | Suggested Outer route |
|-----------------|------------------------|
| Full wheel hub | `/?plane=inner-wheel` or `/?view=wheel` (new) **or** Travel link from Lighthouse → this Pages URL until merged |
| Timeline (4th dimension) | Query `?era=first|second|third|fourth` default `fourth` |
| Lore / Singularity | `/?plane=singularity` or lore tab |
| Digital Void | `/?plane=digital-void` |
| Mineral / Ani | `/?plane=mineral` |
| Dust pilots | `/?plane=dust` |
| Earth / Beast | `/?plane=earth` |
| Outer stubs | Existing `/?plane=celestia|bytopia|elysium|beastlands|arborea|ysgard|limbo|pandemonium|abyss|carceri|hades|gehenna|nine-hells|acheron|mechanus|arcadia` |
| Spells strip | Handout drawer or `/?handout=<id>` |

### Travel link suggestion (Lighthouse folio)
Add a Travel / Roads line: **“Full Wheel & Four Sunderings (will-o’-wisp race supplement)”** → until merge, `https://sporebatglow.github.io/planesbound-inner-planes/` ; after merge, local wheel route.

## Timeline data structure
```js
eras: [
  { id, title, body, hint, art, artCap, stageClass }, // stageClass dims/highlights rings
]
// Default eraIndex = 3 (Fourth Sundering / current)
// Scrub updates timeline panel + wheelStage class: era-1..era-4
```

## Assets to upload to grok.me
### Plane art (`art/`)
fire, water, air, earth-beast, dust-pilots, mineral-progenitor, digital-void, magma, ooze, ice, smoke, positive, negative-shade, ethereal (+ stations / shade-* as presentation)

### Cosmology / lore (`art/lore/`) — keep all batches
- `planesbound-cosmology-sunderings.jpg` — Four Sunderings timeline hero
- `planesbound-cosmology-singularity.jpeg` — Singularity / Axiom / triad / auras
- `ice-portal-forest.jpeg` — Ice folio / portal jump-point
- `icy-city-cosmic-overview.jpeg` — Material / empty-state / Lighthouse-adjacent shore
- `oath-of-the-burning-pact.jpeg` — OBP 1
- `pact-of-the-frozen-oath.jpeg` — PFO (Midnight Sun; pack→pact in drawback copy)
- `cantrip-firecube.jpeg` — CTFB L0
- `counter-spell-gavel.jpeg` — CTSL animated object
- `tesseract-prison.jpeg` — TRP magical object
- `spell-discernment.jpeg` — DISK 2nd-level divination
- `planesbound-oath-report.jpeg` — optional meta panel (grades only as printed)
- `eldritch-grimoire.jpeg` — Far Realms artifact
- `warrior-dragon-digital-sigil.jpeg` — Digital Void / Glitch / Fourth Sundering
- `outlands-market-trade-chart.jpeg` — Outlands Concordant Market Trade jump-point (quiet valuation → spike → wick of greed → volatile new normal above old floor; muse only — no tickers / no financial advice)
- `cosmic-lighthouse-beacon.jpeg` — Cosmic Lighthouse Beacon (Compass Orb sat-link home / Old Presence lean)
- `will-o-wisp-sigils.png` — main-quest race marks (eye-star + hooked yellow glyph)
- `art/lore/eggs/palm-bee.jpeg` — **hidden** Easter egg art only (not in strip/rail/lede)
- `art/ref/wheel-3d-layout.jpg` — layout source of truth (optional behind-the-scenes)

### Private (do NOT upload / do NOT commit)
- `art/lore/muse-private/` — gitignored. Copyrighted FFG/CoC / ambiguous muse only. Rewrite as Planesbound-original themes (see Old Things below); never ship filenames or branded pantheon text.

## Handout IDs (Spells / Objects / Handouts)
`burning-pact`, `frozen-oath`, `firecube`, `counter-gavel`, `tesseract-prison`, `discernment`, `eldritch-grimoire`, `digital-sigil-vision`, `oath-report`, `demon-checkpoints`, `player-housing`, `compass-orb`, `will-o-wisp-sigils`, `old-presence`, `wisp-predator`

## Quest jump-points & key device (this pass)
- **Outlands / Concordant Market Trade** — folio `outlands` art `art/lore/outlands-market-trade-chart.jpeg`; epithet Hub Above · Concordant Exchange. Chart muse: long quiet rim valuation → explosive gold-rush spike → wick of greed → volatile new normal still above the old floor. Merchants, gate-town exchanges, will-o’-wisp rumor-runners mispricing caravan routes. Not a real crypto ticker; no financial advice.
- **Demon Checkpoints** (`demon-checkpoints`) — Quest jump-point on evil/Outer approaches (Abyss / Gehenna / Nine Hells corridors): fiendish toll booths, soul-ledgers, will-o’-wisp false guides past checkpoints.
- **Player Housing** (`player-housing`) — Quest jump-point: planar residences / gate-town flats / Material shore housing between will-o’-wisp race legs (reuses icy-city overview art).
- **Compass Orb** (`compass-orb`) — Device / Magical Object; epithet Orbital Phone · Planar Sat-link. Art: `cosmic-lighthouse-beacon.jpeg` (Beacon home). Party sat-phone across the wheel: ring-calls, chase bearings, jump-point coordinates, party link across non-Euclidean domains. Light Domain / Singularity tie. Mentioned in page lede & empty folio.

### Old Things (Planesbound-original; public assets only)
- **Will-o’-Wisp Sigils** (`will-o-wisp-sigils`) — eye-star + hooked yellow glyph race marks (`will-o-wisp-sigils.png`).
- **Old Presence** (`old-presence`) — Elder hush / pre-Sundering watch; no CoC or branded pantheon names. Beacon lean + rim memory.
- **Wisp-Predator** (`wisp-predator`) — consumes those already misled by will-o’-wisps; stalks checkpoint shade & housing eaves under demon watchers.
- Demon checkpoints ↔ player housing: watchers over housing towns / night ledgers between race legs.
- Muse folder `art/lore/muse-private/` is **gitignored** & never published.

Main quest remains the **will-o’-wisp race**.

## Spoiler — super-hard Easter egg (do NOT put on public empty-state / lede / strip)
<details>
<summary>Unlock trigger & reveal (maintainers only)</summary>

- **Who:** **JD Vance · Palm-Bee of the Outlands** (Senator Bee Vance) — unmistakable title on reveal.
- **Art:** `art/lore/eggs/palm-bee.jpeg` (not in spells strip, rail chips, or lede).
- **Trigger:** type the word `sporebat` on the page (keydown buffer; ignores focused inputs). No UI affordance.
- **Reveal:** full-viewport cinematic modal — dark parchment/cosmic backdrop, huge palm-bee art, Cinzel/brass title naming JD Vance, short mock-epic lore (a light without source that buzzes policy into the Concordant Exchange), soundless shake + will-o’-wisp sigils flash, Close the palm / Escape / click backdrop.
- Not discoverable via normal navigation. Keep this spoiler out of player-facing empty folio copy.

</details>

## UI notes for merge
- Cinzel + Source Serif; parchment/brass wheel + dark cosmology timeline.
- Bare titles (never “Plane of”).
- Whole-word **and** → **&** (`&amp;` in HTML text).
- Outer stubs are short & link to existing Outer pages where slugs match.
- Do not invent FR history beyond user cosmology text, locked customs, diagram labels, & printed card text.

## Ship status
Public Pages: `https://sporebatglow.github.io/planesbound-inner-planes/`  
Repo: `sporebatglow/planesbound-inner-planes`  
**Not** published to grok.me from this package.
