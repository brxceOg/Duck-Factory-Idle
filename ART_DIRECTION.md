# Quack & Co. Industrial Complex — Art Direction

**Status:** Foundational visual specification  
**Applies to:** Duck characters, factory equipment, terrain, map rendering, effects, icons, and UI  
**Reference images:** Three images supplied in the project kickoff: glossy yellow rubber duck, orange/brown beveled game UI sheet, and a top-down forest/map tileset.

## 1. Visual north star

The game should look like a goofy, wacky cartoon world with the confidence and expressive exaggeration of a high-energy animated comedy. The visual language should feel playful, bold, tactile, and carefully designed—not generic, flat corporate software.

The world itself should be beautiful and inviting, while the factory equipment is delightfully over-engineered. The contrast is the joke: a glossy, adorable sentient rubber duck comes off a serious industrial production line surrounded by conveyors, vats, pipes, warning lights, and overly elaborate machinery.

**Core visual pillars**
1. **Goofy cartoon energy:** exaggerated shapes, strong expressions, readable silhouettes, and visual jokes.
2. **Beautiful top-down world:** attractive terrain, clear tiles, small environmental details, and coherent factory layouts.
3. **Glossy duck mascots:** bright rubbery bodies, warm highlights, dark outlines, and distinct personalities.
4. **Tactile game UI:** warm orange, amber, reddish brown, and gold frames with beveled edges and polished highlights.
5. **Cohesion over asset count:** every asset must look like it belongs in the same game.

## 2. Reference image interpretation

### Duck reference
Use the supplied yellow duck as a style reference for:
- Rounded, toy-like proportions.
- Bright yellow body with warm orange shading.
- Glossy specular highlights.
- Oversized, expressive eyes and a large orange-red bill.
- Thick, dark reddish-brown outlines.
- Exaggerated facial expression and friendly, slightly absurd energy.

The reference image contains watermarks. **Do not ship, crop, trace, or reuse the watermarked image as a production asset.** Create original duck artwork that captures the broad visual qualities described above.

### UI reference
Use the supplied interface sheet as a guide for:
- Chunky beveled frames.
- Orange-to-gold face gradients.
- Dark reddish-brown outlines and deep inset shadows.
- Bright top-edge highlights.
- Wood-like panels with warm grain and small imperfections.
- Chunky button silhouettes, clear icon centers, and decorative borders.

The goal is to adapt this look into a coherent game UI, not to paste the sheet into the game.

### Map reference
Use the supplied top-down tileset/map image as a guide for:
- Modular terrain pieces.
- A readable tile grid.
- Grass, trees, rocks, water, paths, and small environmental props.
- Top-down perspective and assets that snap together into a larger world.
- Rich detail that still leaves enough empty space for factory placement.

Create original assets that match this visual language. Do not use the reference image as a finished map or extract its individual assets without permission.

## 3. Palette and materials

Use these as directional color families; exact hex values may be standardized in an asset palette later.

| Purpose | Direction |
|---|---|
| Primary duck body | Sunflower yellow, golden yellow |
| Duck shadows | Amber, orange, warm ochre |
| Duck beak and accents | Orange-red, coral, deep warm red |
| Primary outlines | Dark reddish brown / near-burgundy |
| UI button faces | Honey gold, amber, orange |
| UI frames and shadows | Chestnut, walnut, dark reddish brown |
| UI highlights | Pale golden cream |
| Grass and foliage | Multiple lively greens, olive, moss, yellow-green |
| Water | Clear blue to turquoise with darker edge shading |
| Industrial materials | Warm steel gray, copper, brass, painted orange, cream |
| Warning / mutation effects | Hot pink, electric cyan, toxic lime, violet—used selectively |

The factory can introduce bright accent colors, but the overall world should remain harmonious. Use color to communicate function and rarity rather than making every object equally saturated.

## 4. Shape language and linework

- Favor rounded, chunky, slightly exaggerated shapes.
- Use strong outer contours to preserve readability against busy terrain.
- Maintain a consistent outline family; outlines may vary by object scale but should not look like unrelated assets were assembled together.
- Use asymmetry and controlled irregularity to keep the world lively.
- Machines can have more hard edges than ducks, but should still belong to the same cartoon universe.
- Avoid overly thin details that disappear on a phone.
- Avoid generic vector icon styling that clashes with the tactile reference UI.
- Keep silhouettes identifiable when an object is small, partly occluded, or viewed at normal zoom.

## 5. Duck character design

### Base anatomy
The base duck is a rounded rubber-toy character:
- Plump, simple body mass.
- Distinct head/body read without excessive anatomical complexity.
- Large, readable eyes.
- Prominent bill with a clear silhouette.
- Small wings and tail shapes that can support variants.
- Glossy highlights and warm gradient shading.
- Thick dark reddish-brown contour.

Keep the duck charming and readable at small sizes. Expressions should be visible from the game camera, not only in a close-up illustration.

### Personality and expression
Sentience is central to the premise. Ducks can look smug, exhausted, suspicious, delighted, confused, overconfident, or mildly horrified by their working conditions. Use animation and expression to sell the comedy without making every duck look angry or chaotic.

Useful animation beats include:
- Idle bobbing and blinking.
- Small wing flaps or body wiggles.
- A brief reaction when a machine completes a batch.
- Surprise or wobble when a mutation occurs.
- Product-specific idle behavior.
- Rare celebratory, glitchy, or malfunction reactions.

Keep loops short, smooth, and non-distracting. Avoid constant motion on every asset at once.

### Distinct product identities
A duck variant must be more than a hue change. Change at least two meaningful visual features where appropriate, such as silhouette, accessory, surface pattern, facial expression, wing/tail shape, or animation.

Examples:
- **Cyberpunk Ducky:** neon trim, tech details, angular visor or circuitry accents.
- **Existential Dread Ducky:** drooped eyelids, slumped posture, muted accents, tiny existential props.
- **Chef Ducky:** chef hat, apron-like markings, kitchen tool, proud expression.
- **Mutation hybrids:** unexpected combinations such as toaster wings, spring legs, conveyor-belt tail, antennae, or other absurd objects. Ensure the duck still reads as a duck.

Rare variants may receive more elaborate effects, but never obscure their base silhouette.

## 6. Mutation visual language

Mutations should look like an impossible laboratory accident made charmingly legible. The design should combine duck anatomy with one or more incompatible objects, materials, or themes.

- Give each mutation a clear visual hook that reads immediately.
- Use controlled color accents (for example, toxic lime, electric cyan, violet, or hot pink) to distinguish mutation-related effects from ordinary production.
- Show a short, satisfying reveal: vat bubbles or lights intensify, the duck silhouette emerges, then the finished hybrid is presented.
- Use visual feedback for new discoveries, but keep effects brief enough not to interrupt idle play.
- Rare discoveries should have stronger framing or animation than common outcomes.
- Distinguish a new discovery from a repeat result with a clear UI state.
- Avoid relying on color alone to indicate rarity; combine color with icons, borders, labels, or effects.

The Mutation Vat should be visually memorable: a chunky industrial tank with rounded forms, pipes, gauges, glowing liquid, warning labels, and a clear animation state.

## 7. Top-down world and map

### Perspective and grid
Use a consistent top-down or gently elevated top-down perspective inspired by the supplied map reference. World assets must agree on camera angle, scale, lighting direction, and tile boundaries.

- Choose a base grid and document its world-unit dimensions before producing many assets.
- Terrain edges should connect cleanly without seams.
- Objects intended for placement must align consistently to the placement grid.
- Use transparent backgrounds for individual objects when the asset format supports it.
- Keep collision/placement footprints separate from decorative overhangs.
- Large objects may span multiple cells, but their footprint should be clear in placement mode.

### Terrain
The map should have visual character even before it is filled with machines. Use layered grass, paths, soil, rocks, trees, shrubs, water features, and small environmental details to make the land feel like a place.

Terrain principles:
- Use controlled variation rather than repeating the exact same tile visibly.
- Make tile edges blend naturally.
- Keep buildable ground readable; avoid excessive decoration where machines need to be placed.
- Use trees and large props to frame areas rather than obstruct important factory interactions.
- Keep shadows consistent and visually grounded.
- Use a few distinct terrain families rather than a noisy mixture of every color.

### Factory integration
Industrial equipment should look deliberately installed into the terrain. Use foundations, pads, tracks, pipes, service paths, and other visual connectors where they improve readability.

Conveyors should be visually continuous and make their direction obvious. Junctions, splitters, mergers, and turns need distinct silhouettes. Machine entrances and exits should be apparent without requiring the player to guess where ducks or materials flow.

### Infinite-feeling expansion
The map should feel expansive through smooth camera movement, distant buildable land, coherent terrain continuation, and gradual expansion. Do not create visible repeating seams or a harsh edge that makes the world feel abruptly unfinished. Unlocked, purchasable, and inaccessible land should be distinguishable without overwhelming the environment.

## 8. Factory equipment

Factory machines should be comically elaborate but easy to identify. Their designs can draw from retro-futuristic industry, toy-like machinery, old factory equipment, and overbuilt cartoon inventions.

Common visual components:
- Rounded metal housings.
- Copper or brass pipes.
- Chunky bolts, rivets, and panels.
- Amber indicator lights and gauges.
- Moving pistons, rollers, belts, fans, and mechanical arms.
- Clearly differentiated inlets and outlets.
- Simple status lights and readable animation states.

Equipment categories should have consistent visual motifs:
- **Production machines:** strong central chamber, rollers or forming tools, obvious output side.
- **Conveyors:** repeating belt or roller detail, directional markings, connected edges.
- **Storage:** larger box/tank silhouette with a capacity indicator when selected.
- **Research machines:** gauges, glass tubes, dials, or illuminated panels.
- **Mutation equipment:** glowing vat, thick pipes, bubbling liquid, warning accents.
- **Upgraded equipment:** visibly improved modules or extra components, not merely a different number in the UI.

Avoid too many tiny gears or lights. Each machine should remain recognizable at the standard camera zoom.

## 9. UI art direction

### Core style
The interface should be based on the supplied orange/brown beveled UI sheet:
- Warm orange and gold button faces.
- Dark chestnut or burgundy outer strokes.
- Deep inset shadows for a raised, tactile appearance.
- Bright golden top highlights.
- Slight texture and carefully controlled wood grain on larger panels.
- Chunky shapes with rounded corners or clipped ornamental ends.
- Clear iconography and generous internal spacing.

The interface should feel like a polished cartoon tycoon game, not a browser dashboard.

### Hierarchy
- **Primary HUD:** currency and production status are always easy to find.
- **Main actions:** build, upgrades, markets, mutations, and collection use clearly differentiated controls.
- **Panels:** use wooden or metal-framed surfaces that complement the button style.
- **Feedback:** purchases, unlocks, warnings, and discoveries need visible, concise responses.
- **Selected states:** use a clear glow, inset, border, or shift in bevel rather than a subtle color change alone.
- **Disabled states:** remain legible but clearly inactive.

### Buttons and icons
- Icons should be bold, simple, and readable at phone scale.
- Keep a consistent icon stroke and shading style.
- Avoid tiny text baked into icons.
- Use recognizable silhouettes for common actions.
- Buttons should have visible pressed/selected feedback.
- Maintain comfortable touch targets and spacing.

### Text
- Use a playful display face for headings and a highly legible face for small operational text.
- Avoid excessively distressed or novelty fonts for numbers and descriptions.
- Currency values, rates, costs, and percentages must remain readable on a phone.
- Use short labels and explanatory tooltips or detail panels for complex mechanics.

### UI texture restraint
Wood grain and scratches add character, but must not compete with text. Decorative trim should support hierarchy rather than make every panel equally loud. Keep the central factory area as visually important as the interface.

## 10. Lighting, shading, and effects

- Establish a consistent light direction across terrain, ducks, machines, and UI.
- Use warm highlights on glossy ducks and metallic machine edges.
- Keep shadows soft enough for a friendly cartoon world, but strong enough to ground objects.
- Use small animated lights, steam puffs, bubbles, and moving parts to make machines feel active.
- Use sound-wave rings, ripples, or compact pulses to visualize Quack generation.
- Use restrained particles for production completion and stronger effects for rare mutations.
- Make visual feedback understandable even when audio is muted.
- Avoid full-screen flashes or long particle storms that interfere with touch controls.

## 11. Motion design

Motion should be bouncy and expressive without becoming exhausting.

- Use quick, readable ease-in/ease-out movement for buttons and menus.
- Machine loops should communicate function and status.
- Conveyors should show flow through moving belts, rollers, or subtle directional cues.
- Duck motion should feel rubbery and elastic, with small squash-and-stretch where appropriate.
- Mutations should have a short build-up and reveal.
- Quack generation may produce localized waves or pulses near active equipment.
- Avoid animating every decorative element continuously; prioritize important feedback and conserve mobile performance.

Animations should respect reduced-motion preferences where practical and should not be required to understand game state.

## 12. Mobile readability and performance

The game targets iPhone browsers. Art must be designed for the actual gameplay camera and small-screen UI.

- Test assets at their in-game scale early.
- Prioritize silhouette, contrast, and clear interaction footprints.
- Avoid tiny text, hairline outlines, and intricate details that vanish when zoomed out.
- Keep HUD panels compact and allow secondary panels to collapse or slide away.
- Use sprite sheets or other appropriate batching where useful.
- Avoid excessive oversized transparent images and unnecessary per-frame effects.
- Use a consistent asset scale and naming scheme.
- Test dense factory scenes, not just an empty starter plot.

## 13. Asset production and organization

Create original assets for the project. Reference images define broad style, not production-ready files.

Suggested organization (adapt to the chosen implementation):
- `assets/ducks/` — base duck, product variants, mutations, expression and animation frames.
- `assets/machines/` — production equipment, vats, storage, upgrades.
- `assets/conveyors/` — straight, corner, junction, split, merge, and end pieces.
- `assets/terrain/` — ground tiles, paths, water, rocks, trees, shrubs, and environment props.
- `assets/ui/` — panels, button states, frames, currency icons, skill nodes, badges.
- `assets/effects/` — Quack waves, steam, sparks, mutation reveals, unlock effects.
- `assets/docs/ or docs/` — optional reference sheets and asset inventories if useful.

Use transparent backgrounds for standalone sprites where suitable. Keep pivots, dimensions, animation frame order, and collision/placement footprints documented. Do not commit watermarked reference images as production assets.

## 14. Asset naming and consistency

Use predictable, descriptive names. For example:
- `duck_base_idle_01`
- `duck_cyberpunk_idle_01`
- `duck_existential_dread_idle_01`
- `machine_duck_press_idle`
- `machine_mutation_vat_active`
- `conveyor_straight`
- `conveyor_corner_ne`
- `terrain_grass_variant_01`
- `ui_button_primary_normal`
- `effect_quack_pulse`

Adapt naming to the chosen engine and format, but do not mix arbitrary naming conventions. Reuse shared palettes, outlines, shadows, and material rules across assets.

## 15. Do / Don't checklist

### Do
- Make ducks expressive, glossy, rounded, and recognizable.
- Use thick dark outlines and warm highlights consistently.
- Make top-down terrain beautiful and modular.
- Make machinery funny, overbuilt, and functionally readable.
- Use warm beveled orange/brown UI with golden highlights.
- Use mutations to create memorable visual surprises.
- Test everything at real gameplay scale on a phone-sized viewport.
- Keep the world visually rich while preserving clear buildable space.

### Don't
- Ship watermarked reference images.
- Mix pixel art, flat vector icons, photorealism, and glossy cartoon sprites without a deliberate unifying treatment.
- Make product variants simple recolors of one duck.
- Let decorative terrain obscure placement or machine connections.
- Use UI textures that make text hard to read.
- Make every machine equally detailed or equally bright.
- Rely on sound alone to communicate Quack production.
- Use uncontrolled flashing, excessive particles, or constant motion.
- Assume an asset looks good just because it looks good in a zoomed-in editor.

## 16. Visual acceptance checklist

An asset or UI change is ready when:
- It belongs to the established cartoon style.
- Its silhouette is readable at the intended zoom.
- Its palette, outline, shading, and light direction match related assets.
- It communicates its gameplay purpose clearly.
- It integrates cleanly with neighboring terrain or interface elements.
- It remains legible on a phone-sized viewport.
- It uses original artwork or properly licensed assets.
- It does not introduce unnecessary performance cost or visual clutter.

---

**Visual north star:** A beautiful, top-down cartoon factory full of glossy, expressive sentient rubber ducks, absurdly elaborate machinery, and warm beveled game UI—polished enough to feel cohesive, and silly enough that a duck with toaster wings looks completely at home.
