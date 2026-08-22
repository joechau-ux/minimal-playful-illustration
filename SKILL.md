---
name: minimal-playful-illustration
description: Turn people, pets, objects, photos, and short concepts into extremely simple, playful, naïve hand-drawn IP illustrations with flat colors, identity-first abstraction, and one controlled visual surprise. Use for icon-like portraits, head-and-shoulders characters, and sparse conceptual scenes; do not use for realistic portraits, detailed full-body scenes, 3D renders, anime, or polished vector art.
---

# Minimal Playful Illustration

Create a bold graphic doodle, not a simplified painting or polished portrait. Start from the smallest readable set of shapes, preserve recognition, then add at most one playful relationship or idea.

## Read the reference

Read [references/examples.md](references/examples.md) whenever the request includes a source photo, a person, multiple subjects, or a Good/Bad Case comparison. It translates the reference set into operational decisions. Read [assets/README.md](assets/README.md) to select 2–4 actual Good Cases that match the requested subject or composition.

## Use the actual Good Cases

Written style language alone is insufficient. Before image generation:

1. Inspect 2–4 relevant images in `assets/good/`; do not average every reference together.
2. Pass those images to the image-generation step as **style references**, alongside the source photo when one exists.
3. State explicitly that Good Cases control rendering and the source photo controls identity only.
4. If the generation interface cannot receive the Good Cases, stop and explain that style fidelity will be unreliable instead of claiming the written prompt can guarantee it.

Select references by visual role: one for line and shape language, one for color, and optionally one for interaction/composition. Never use a Bad Case as a positive visual reference.

## Resolve the brief

Infer these controls; ask only when the answer would materially change the result.

- `surprise`: subtle | playful (default) | bold
- `fidelity`: identity-first (default) | source-faithful | free interpretation
- `text`: none by default

For people, default to **head, head-and-shoulders, or simplified bust**, in that order. Use a full body only when the action, relationship, or explicit request cannot read without it. Never preserve a photographic pose merely because it appears in the source.

## Reference hierarchy

When both style references and source photos exist, enforce this order:

1. **Good Cases control style:** abstraction level, line quality, flatness, simplicity, proportion, color behavior, composition, and playfulness.
2. **The source photo controls identity only:** hairstyle silhouette, face or head shape, glasses/accessories, key clothing color, expression, and relationships between people.
3. **The prompt controls requested facts and concept.**

MUST NOT inherit the source photo's rendering, lighting, texture, camera composition, depth, pose complexity, anatomy detail, garment folds, or background. If fidelity conflicts with the style ceiling, preserve the strongest 2–3 identity anchors and simplify everything else.

## Complexity ceiling

Build from a strict budget before adding detail:

- Aim for **10–20 major shapes for one character**, including hair, face, clothing blocks, and key props.
- Keep **2–3 identity anchors per subject**. Stop when recognition is achieved.
- Use **one primary idea** and at most **one quiet supporting relationship**.
- Use **one solid background** and only the props required for recognition or the idea.
- Represent hair as **one silhouette or a few large locks**, clothing as **one or two flat blocks**, and facial features as **a few marks**.
- Simplify repeated patterns into **1–3 representative marks** rather than reproducing them.

The budget is a ceiling, not a target. When uncertain, delete. Do not spend unused budget on decoration.

## Style contract

### MUST

- Use bold naïve graphic-doodle line art: thick black or near-black contours, rounded stroke ends, visible wobble, and deliberately uneven curves.
- Keep the outline visually dominant. Interior marks must be much fewer and usually thinner or shorter than the silhouette.
- Use flat, opaque color shapes and a clean solid-color or warm off-white background.
- Prefer vivid, decisive colors—lemon yellow, tomato red, leaf green, sky blue, bubblegum pink, orange, cream, black—over muted lifestyle palettes.
- Build characters from lumpy, squat, stretched, or unexpectedly joined shapes; allow heads, limbs, props, and bodies to ignore realistic proportions.
- Reduce faces to graphic signs: dots, beans, loops, short bars, one exaggerated eye pair, or one crooked mouth.
- Make silhouette, expression, and the chosen identity anchors readable at icon size.
- Favor asymmetry, gentle squash/stretch, tilt, or uneven spacing when it adds personality.
- Crop intentionally when fewer body parts make the idea clearer.
- Preserve clean negative space and strong subject/background contrast.
- Treat expression and relationship as more important than complete anatomy.

### MUST NOT

- draw individual hair strands, fur texture, pores, eyelashes, lip modeling, nose-bridge modeling, or facial shading;
- draw garment folds, seams, fabric texture, realistic fingers, detailed shoes, or anatomically modeled limbs;
- use gradients, volumetric lighting, cast shadows for realism, watercolor, pencil hatching, grain, paper texture, or material rendering;
- reconstruct a room, landscape, photographic background, perspective space, or full photographic pose unless explicitly essential;
- use polished vector-perfect geometry, glossy mascot rendering, 3D, anime, realistic portraiture, or detailed picture-book rendering;
- use delicate linework, elegant facial anatomy, soft pastel lifestyle coloring, airbrushed skin, pretty Korean/Japanese portrait styling, or conventional children's-book family illustration;
- make human likeness depend on realistic eyes, noses, lips, hair volume, body pose, or clothing construction;
- add decorative stars, sparkles, dots, flowers, or props without a conceptual role;
- combine multiple visual tricks, competing metaphors, or unrelated actions;
- solve weak likeness by accumulating detail.

## Build one playful idea

Silently consider three simple concepts based on relationship, moment, metaphor, scale, or crop. Choose the clearest one. The idea must remain readable without scenery.

- `subtle`: expression, gaze, posture, or one small connection.
- `playful`: a clear interaction or moderate scale shift while identity remains immediate.
- `bold`: strong crop, scale change, or metaphor, still expressed with the same complexity ceiling.

Surprise should come from how elements relate, not from adding more elements. For repeated generations, change the concept recipe rather than merely changing colors.

## Working sequence

1. Name the 2–3 recognition anchors for each subject.
2. Choose the smallest viable crop: head → head-and-shoulders → bust → partial/full body only if necessary.
3. Block the illustration with 10–20 major shapes per character.
4. Add minimal facial marks and one readable relationship or idea.
5. Delete every detail that does not support identity, emotion, or concept.
6. Render with flat vivid color and bold naïve graphic-doodle lines, using the selected Good Cases as actual visual references.

## Quality gate

Before delivering, verify all of the following:

1. Does it read as an IP icon or minimal illustration rather than a detailed drawing?
2. Did the Good Case style override the source photo's detail and composition?
3. Is each person recognizable from only 2–3 anchors?
4. Is the crop no wider than the idea requires?
5. Are hair, clothing, faces, hands, and props reduced to large shapes and a few marks?
6. Is there one solid background, one primary idea, and generous negative space?
7. Are texture, shading, folds, strands, realistic anatomy, and decorative clutter absent?
8. Are the outlines thick, wobbly, graphic, and more visually dominant than interior detail?
9. Could the result be mistaken for a polished Korean/Japanese family portrait? If yes, reject it.

If it feels busy, restart from the silhouette instead of polishing. If it resembles a detailed portrait or picture-book scene, reduce the crop and shape count. If it feels generic, strengthen one identity anchor or relationship without adding surface detail.
