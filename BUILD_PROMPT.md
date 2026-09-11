# Build Mode — Add Inner filter to Outer gazetteer (planesbound.grok.me)

Paste into Grok Build on the live Outer atlas. Do **not** replace Outer content.

## Goal
Wire the Inner Planes campaign into the existing Outer gazetteer as a first-class filter slide—same shape as the Outer map/folio experience—matching the dark parchment + starfield aesthetic already on Outer.

## Do this

1. **Filter chip `Inner`**
   - Add an **Inner** chip beside the existing chips: All / Upper / Lower / Law / Chaos / Sites.
   - Style it like the other inactive chips (dark fill, brass border, cream label); active = solid brass/gold (`#c5a059`-ish) with dark text.

2. **Selecting Inner opens the full Inner Planes campaign slide**
   - Same layout pattern as Outer: campaign map card (starfield / deep space behind map area) + hotspots + dark parchment folio + rail of circular plane thumbs + bottom quest panel.
   - Include **all Inner shores** with bare titles (never “Plane of …”) and whole-word **and → &**:
     Fire, Water, Air, Earth, Positive Energy, Negative Energy, Ethereal, Magma, Ooze, Ice, Smoke, Dust, Mineral, Digital Void.
   - Include the **Will-o’-Wisp Race** quest panel (Ani/Mineral as hearth; Compass Orb one-liner device only).
   - Header parallel to Outer: **PLANESBOUND GAZETTEER / INNER PLANES CAMPAIGN MAP**.
   - Source staging (art + copy + structure): https://sporebatglow.github.io/planesbound-inner-planes/  
     Repo: `sporebatglow/planesbound-inner-planes` (`index.html`, `art/`).

3. **Match dark parchment + space aesthetic**
   - Charcoal/sepia parchment cards (`#0c0a09` / `#16130f`), cream/off-white serif body (`#d6cbb6`), gold/brass accents (`#c5a059`), Cinzel titles.
   - Starfield behind the map area. Rounded cards like Outer. No cream light-paper theme.

4. **Do not destroy Outer content**
   - Keep the full Outer Wheel map, folios, Lighthouse, Travel, filters, search (“Search the wheel”), and existing routes.
   - Inner is additive: a filter that swaps the campaign slide to Inner; leaving Inner restores Outer.
   - Optional: Lighthouse Travel line → Inner Ring & Will-o’-Wisp Race.

5. **Brand / assets**
   - Avoid Imagine/ffmpeg brand-asset hang. Keep existing brand fallbacks (logo/mark already on Outer).
   - Use Fresh Inner art already in the staging `art/` folder (`inner-campaign-overview.png`, `will-o-wisp-race-quest.png`, plane heroes). Do **not** paste lore JPEGs from `art/lore`. Do **not** rebuild a mega 3D wheel.

6. **Publish when ready**
   - Publish to `https://planesbound.grok.me/` once Inner filter + slide work and Outer is intact.

## Locked customs (do not invent beyond)
- Earth = home of the Beast · Dust = pilots of the agentic body · Mineral = Ani progenitor will-o’-wisp · Digital Void = Astral–Ethereal schism.
- Quest conflict: Will-o’-Wisp Race / Fourth Sundering pressure / Gulthias blight / Shade’s secret Third Sundering.
