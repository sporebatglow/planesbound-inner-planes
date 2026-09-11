# MERGE_NOTES — Port full-wheel atlas into planesbound.grok.me

Supplement only. Do **not** replace the Outer gazetteer. Keep back-link to `/?plane=lighthouse`.

## Main quest lock
- **Will-o’-wisp race** is the campaign spine (flickering lights without source: guide, mislead, or consume).
- Mineral / Ani progenitor aesthetic is a hearth of that race.
- Lore art batches in `art/lore/` are fuel for jump-points (portals, oaths, spells, artifacts, triad figures).

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
- `art/ref/wheel-3d-layout.jpg` — layout source of truth (optional behind-the-scenes)

## Handout IDs (Spells / Objects / Handouts)
`burning-pact`, `frozen-oath`, `firecube`, `counter-gavel`, `tesseract-prison`, `discernment`, `eldritch-grimoire`, `digital-sigil-vision`, `oath-report`

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
