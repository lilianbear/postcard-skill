---
name: postcard
description: Transform one or many user-supplied photos into richly aged vintage postcard fronts while preserving the source subject, pose, geometry, perspective, and defining detail. Use when Codex should create a postcard, vintage travel card, polar or hiking postcard series, batch postcard set, postcard-style photo edit, or printable card front with period-specific lithograph, letterpress, offset, screenprint, or hand-tinted character, visible paper wear, postal marks, and restrained micro-text.
---

# Postcard

Create finished postcard-front images from supplied photos. Use `imagegen` for raster generation or editing. Treat each source image as the factual authority. Make the result feel genuinely printed, handled, faded, and kept—not merely beige, desaturated, or filtered.

## Workflow

1. Inspect every source image before writing prompts.
2. Build a short scene card: subject, spatial invariants, dominant gesture, native colors, quiet areas, details that must survive, one stamp motif candidate, one environmental contour, and one directional rhythm. Read [references/source-derived-elements.md](references/source-derived-elements.md) before designing the stamp or background.
3. Choose the source orientation: 3:5 portrait or 5:3 landscape unless the user requests another ratio. Read [references/vintage-directions.md](references/vintage-directions.md), then select the period direction that best fits the scene. Rotate directions across a batch when the user asks for variety.
4. Preserve the source subject photographically. Never change subject count, identity, pose, anatomy, gaze, facing direction, relative spacing, perspective, or defining object geometry.
5. Choose a photo treatment that fits the selected direction: irregular hand-torn aperture, soft masked plate, full-bleed faded photograph, inset print window, or overlapping paper fragment. Keep the core subject and its key relationship intact and fully legible.
6. Rebuild the background from the source environment rather than inserting generic paper decoration. Carry at least two recognizable source cues into the poster field: a ridge or shoreline contour, vegetation rhythm, ice or water reflection, path direction, architectural profile, weather mass, shadow, or repeated step. Simplify repetitive detail, but preserve the scene's spatial logic and visual flow.
7. Build a period palette from two to four inks. Include one scene-derived accent when helpful, but do not force tomato orange or a single high-chroma hue into every card. Allow oxidized teal, faded vermilion, mustard, tobacco brown, dusty rose, ultramarine, soot black, and warm paper to combine according to the chosen direction.
8. Add convincing age in three distinct scales: paper-level fibers/foxing/edge darkening; print-level fading/ink starvation/halftone breakup/misregistration; handling-level rubbed corners/soft scratches/uneven exposure. Keep the subject readable and avoid uniform digital noise.
9. Design a source-specific stamp as a miniature graphic interpretation of the uploaded photo. Derive its motif from the most distinctive secondary-readable feature—subject silhouette, paired gesture, ridge profile, ice formation, tree canopy, path switchback, boat, building, or native object. Redraw it in the selected period's print language instead of cropping the photograph into a generic stamp. Coordinate the stamp frame, perforation, ink, cancellation, and placement with the background geometry. Never use a real country, currency, date, address, or denomination unless supplied.
10. Add one English micro-text line of five words or fewer, unless the user supplies exact wording or requests Chinese/bilingual text. Use period-appropriate worn grotesk, slab serif, condensed display, typewriter, or letterpress lettering.
11. Generate one image per source. For batches, preserve a family resemblance through paper era and typographic tone while deliberately varying crop device, print method, accent palette, postal placement, wear pattern, stamp motif, and source-derived background geometry.
12. Inspect every result for source fidelity, visible multi-scale aging, period coherence, text correctness, postcard hierarchy, and real variation. Regenerate at most once per failed image with one targeted correction.
13. Return every image with a compact creative rationale naming the selected vintage direction and the preserved source details. Do not reveal the full prompt unless asked.

## Postcard Front Rules

- Keep the card flat and orthographic. Never create a tabletop, hand-held, taped, clipped, framed, or perspective mockup.
- Make at least three aging mechanisms visibly legible at normal viewing size. Let vintage character come from paper fibers, foxing, oxidized edges, sun fading, dry ink, halftone breakup, lithographic grain, letterpress pressure, plate misregistration, handling rub, and edge wear—not a global sepia filter.
- Keep postal cues subordinate to the scene. The photograph remains the focal anchor.
- Make the stamp recognizable as a compressed symbol of that specific source image. Do not reuse generic birds, mountains, globes, flowers, compass roses, or monuments unless they genuinely appear in the source.
- Make the poster background feel like an extension of the source world. Do not use unrelated sunbursts, random geometric blocks, generic map lines, or decorative foliage.
- Preserve natural source colors inside the photographic aperture.
- Use a restrained two-to-four-ink period palette; avoid one-accent-color formulas repeated across the whole batch.
- When using a torn edge, keep its fiber band narrow, irregular, and flat. Do not require torn paper on every card. Avoid sticker outlines, uniform deckled frames, glossy drop shadows, or theatrical curled corners.
- For a front-only request, omit address lines and message fields. Create a back only when explicitly requested.
- Never invent logos, locations, dates, quotations, metadata, or watermarks.

## Batch Rules

- Process each source independently; never combine several photos into one card unless asked.
- Preserve each photo's orientation by default.
- Use a shared era and material family, but vary at least three of these across the set: print method, crop device, palette emphasis, typography, postal placement, abstraction grammar, and wear pattern.
- Do not reuse the same stamp, cancellation, text placement, torn aperture, or accent path on consecutive cards.
- Derive a new stamp motif and environmental contour from every source. For similar images, change viewpoint, silhouette crop, frame geometry, or print treatment rather than duplicating the emblem.
- Keep filenames traceable to the source: `<source-name>-postcard.png`.
- Report failed items separately without discarding successful outputs.

## Prompt Construction

Write four compact paragraphs:

1. Canvas, postcard margin, photographic aperture, focal area, source-derived background field, and eye path.
2. Exact source invariants and photographic details that must remain unchanged.
3. Selected vintage direction, print method, period palette, exact source-derived stamp motif, background cue mapping, postal system, and exact micro-text.
4. Three-scale aging map plus hard avoids, including no uniform sepia filter and no repeated template look.

For detailed composition ranges, color choices, validation gates, and prompt patterns, read [references/postcard-style.md](references/postcard-style.md). Always read [references/vintage-directions.md](references/vintage-directions.md) before choosing the visual direction, and [references/source-derived-elements.md](references/source-derived-elements.md) before designing the stamp and poster background.

## Output

Return the generated postcard image(s), then one brief Chinese paragraph explaining the preserved source relationship, selected vintage direction, stamp motif origin, background cue mapping, print palette, and aging treatment.
