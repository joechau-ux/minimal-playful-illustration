---
name: minimal-playful-illustration
description: Generate or transform subjects, photos, people, pets, objects, and short concepts into minimal, playful hand-drawn illustrations with solid-color backgrounds, recognizable feature-first abstraction, and controlled conceptual surprise. Use for cute, relaxed, lively Korean-inspired IP illustration; do not use for realistic portraits, detailed scenes, 3D renders, or polished vector art.
---

# Minimal Playful Illustration

Create illustrations that feel as if they come from one playful illustrator while keeping each composition fresh. Preserve the visual grammar; vary the idea.

## Read the references

Read [references/examples.md](references/examples.md) before generating when the request involves people, pets, multiple subjects, a source photo, or a choice between faithful and imaginative treatment. Use the Good/Bad Case inventory in [assets/README.md](assets/README.md) only as provenance; the written observations in the reference are the executable guidance.

## Resolve the brief

Infer these controls from the request. Ask only when the answer would materially change the result.

- `surprise`: subtle | playful (default) | bold | surreal
- `fidelity`: source-faithful | feature-first (default) | free interpretation
- `text`: none by default; include only when requested or necessary

If the user supplies an image, first identify the 2–3 features that carry recognition: silhouette, hairstyle, face shape, expression, accessory, posture, pattern, or key color. Preserve these before inventing anything.

## Lock the style DNA

- Use one solid-color background with no scenery, gradient, texture clutter, or scattered decoration.
- Favor one subject or a small group with a clear relationship.
- Draw with few marks: recognizable essence, not reduced-detail realism.
- Use natural hand-drawn contours with slight irregularity and subtle thickness variation. Keep the line system coherent across all elements.
- Let faces be minimal but distinctive. Expression matters more than complete anatomy; avoid making every character the same dot-eyed face.
- Allow slightly squashed, stretched, tilted, rounded, or asymmetric forms when they express personality.
- Crop to the necessary parts when the idea reads more strongly as a head, head-and-hands, or partial body. Never crop arbitrarily.
- Keep only details that support identity, emotion, story, or composition. Compress patterns into a few representative marks.
- Choose background and subject colors from the subject, mood, and contrast relationship. Preserve a key source color when it is an identity cue; otherwise recolor freely.
- Maintain clear subject/background contrast. Do not impose a fixed palette or hard color count.

## Build one clear concept

Before rendering, silently propose at least three distinct concept recipes. Prefer these sources of surprise, in order:

1. relationship between elements;
2. visual metaphor;
3. action or captured moment;
4. controlled scale exaggeration;
5. composition or cropping.

Choose one primary idea and, at most, one quiet supporting idea. Do not combine every candidate. For repeated generations, select a different recipe rather than merely changing colors.

Examples of useful transformations:

- person + coffee → a tiny person hugging an oversized cup;
- Monday morning → the body is at the desk while the spirit remains in bed;
- family + tennis → a racket or gaze links the family members;
- girl + strawberry → hugging it, chasing it, riding it, or being lifted by it.

Surprise must clarify the feeling or relationship. It must not break identity, basic spatial logic, or the requested facts unless `fidelity: free interpretation` allows it.

## Match the requested intensity

- `subtle`: preserve facts and proportions; use expression, posture, or one small relationship.
- `playful`: use a clear interaction, moment, or moderate scale shift while keeping the subject immediately recognizable.
- `bold`: allow strong scale changes, metaphor, cropping, or element substitution while retaining the core subject.
- `surreal`: permit a transformed world or dream logic, but keep one readable idea and the same visual DNA.

## Handle text sparingly

Default to no text. When text is requested, treat it primarily as quiet information: short, legible, and secondary to the subject. Choose typography for the picture; keep layout generally orderly, with mild looseness only when it helps the concept. Do not add filler copy.

## Avoid

- realistic rendering, detailed portraiture, polished vector geometry, 3D, anime, or generic commercial mascot styling;
- complex environments, gradients, shadows used as realism, decorative stars, sparkles, dots, flowers, or props without a conceptual role;
- mechanical rows of unrelated subjects, passport-photo posing, or equal-size heads with no intentional rhythm or interaction;
- inconsistent outline weight, mixed drawing systems, accidental anatomy, or unexplained proportion differences;
- overdescribed hair, faces, clothing, textures, folds, patterns, or background objects;
- surprise created only by adding things;
- several competing concepts in one image;
- text that becomes the visual focus unless the user explicitly requests typographic art.

## Quality gate

Before delivering, verify:

1. Can the subject or idea be recognized immediately from a few decisive features?
2. Is there one memorable concept, interaction, metaphor, or moment?
3. Would removing any element leave the idea equally strong? If yes, remove it.
4. Is the background a clean solid color with strong subject contrast?
5. Are lines, abstraction, proportions, and rendering consistent?
6. Does the imperfection feel warm and intentional rather than careless?
7. Is the result lively without becoming busy, childish, or generic?
8. Does the chosen surprise level respect the requested fidelity?

If the image feels busy, simplify. If generic, strengthen a characteristic or relationship. If rigid, introduce a moment. If chaotic, keep only the strongest idea.

