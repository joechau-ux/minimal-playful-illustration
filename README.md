# Minimal Playful Illustration

A Codex Skill for converting photos, people, pets, objects, and short concepts into icon-like, minimal naïve hand-drawn illustrations.

The Skill treats Good Cases as the style authority and source photos as identity evidence only. It defaults portraits to heads or simplified busts and rejects detailed picture-book rendering, texture, shading, and photographic composition.

## Install

Copy this repository folder into your personal Codex skills directory, or ask Codex to install the repository as a personal Skill. Keep the structure intact so relative links in `SKILL.md` work.

## Use

```text
Use minimal-playful-illustration to turn this family photo into a minimal portrait.
Keep 2–3 identity anchors per person, prefer heads or simplified busts, and use no text.
```

```text
Draw a cat hugging an oversized coffee cup in this style.
Surprise: playful. Keep one clean idea.
```

Defaults:

- `surprise: playful`
- `fidelity: identity-first`
- no text
- head, head-and-shoulders, or simplified bust for people
- roughly 10–20 major shapes per character, often fewer

## Core behavior

- **Complexity ceiling:** recognition comes from a small shape budget, not accumulated detail.
- **Reference hierarchy:** Good Cases control style; source photos control identity only.
- **Minimal naïve line art:** sparse, relaxed, slightly irregular contours with coherent weight.
- **Flat construction:** solid background and opaque blocks; no gradients, modeling, or texture.
- **Hard exclusions:** no strands, garment folds, facial shading, realistic fingers, detailed shoes, photographic scenery, or decorative clutter.
- **One idea:** playfulness comes from one relationship, moment, metaphor, scale shift, or crop.

## Contents

- `SKILL.md` — activation metadata, workflow, MUST/MUST NOT rules, and quality gate
- `references/examples.md` — source translation, budgets, Good/Bad patterns, and prompts
- `assets/good/` — retained location for positive references
- `assets/bad/` — retained location for negative references
- `assets/README.md` — asset inventory and provenance notes

## Reference assets

The existing `assets/good/` and `assets/bad/` structure is unchanged. `references/examples.md` is the executable translation of those visual preferences; `assets/README.md` remains the inventory.
