---
name: marsad-design-director
description: Direct, create, or critique logos, social graphics, ads, covers, diagrams, presentations, and web visuals with brand-aware decisions and a contextual AI-cliché review. Use when asked to make or improve a design, use supplied brand rules or assets, avoid repetitive AI-looking output, or check alignment and export quality. Do not impose a house style; work from the brief and available evidence even when no formal brand guide exists.
---

# Marsad Design Director

Use this skill as a decision and quality-control layer. It supplies **no default palette, font, icon, layout, visual metaphor, or composition**. Its purpose is to make the requested artifact fit its own brief and pass visual QA. Do not let the examples or checklists in this skill become visual ingredients for generation.

## Read only what the task needs

- For every creation, read [brand-and-brief.md](references/brand-and-brief.md) and [production-qa.md](references/production-qa.md).
- For a logo, social post, campaign, diagram, web visual, or multi-format work, read the relevant section of [design-modes.md](references/design-modes.md).
- For a critique or the final review of a creation, read [cliche-review.md](references/cliche-review.md). Keep its pattern names out of the generation prompt unless a specific observed failure must be repaired.

Use the available image, vector, layout, Canva, site, or document tools for the actual artifact. Follow their specialized instructions. This skill does not choose a tool for aesthetic reasons.

## Workflow

1. **Ground the job.** Identify the exact deliverable, message/function, audience, destination, size, copy, required assets, and any explicit constraints. Distinguish supplied facts from reasonable assumptions. A logo is a different design problem from an ad or a feature diagram; do not route all of them through one composition recipe.
2. **Resolve the brand from evidence.** Apply explicit user instructions first, then official brand guide and files, then approved examples, then other reliable project context. If only a palette and two fonts are provided, use those exactly and treat every other decision as open. If no guide exists, make context-based, reversible choices and continue. Request an asset only when its absence prevents a faithful final result; do not delay useful work to ask for a complete guide.
3. **Choose the visual approach for this job.** Decide what must be shown and why. Choose image, typography, illustration, data, diagram, or a combination according to the content. Develop materially different directions when options are requested. Do not select from a fixed library of shapes or force one focal-point pattern on all work.
4. **Acquire or create necessary assets.** Prefer supplied and approved assets. If imagery would improve the message, find appropriate stock with usable rights or generate an original visual, inspect it, then compose the design with exact copy and logo. Do not use generic stock as filler. For precise diagrams and data, build exact editable shapes/text rather than asking an image model to invent them. See [brand-and-brief.md](references/brand-and-brief.md).
5. **Produce the requested artifact.** Honor required typefaces, palette, spelling, logo, product features, and sizes. Keep text editable or typeset deterministically when image generation is unreliable for exact wording. Create real exports/links when promising them.
6. **Inspect the rendered result.** Check alignment, spacing, overlap, optical balance, language direction, small-size legibility, brand accuracy, and deliverable files using [production-qa.md](references/production-qa.md). Compare with recent outputs when provided. If two unrelated projects have nearly the same symbol, font treatment, and lockup, rethink the approach. Fix visible defects before sending.
7. **Run a short cliché review.** Look only for patterns actually present and damaging the current job. Explain any meaningful issue in terms of message or brand fit. A circle, card, gradient, arrow, or grid can be correct; none is a default or automatic failure.

## Guardrails against a hidden house style

- Do not import colors, fonts, visual motifs, layout, or logo structures from Marsad or a previous client into another project. The name of this skill is not a brand rule.
- Do not reuse the same symbol construction for a series of unrelated logos merely because all products involve software or scheduling. Compare silhouettes, proportions, stroke behavior, and wordmarks; the concept for each name and product must stand on its own.
- Do not prescribe a rectangular logo card, icon-left/word-right lockup, dark navy canvas, oversized title, timeline, circle-and-dot, or any other recurring arrangement. Use an arrangement only when this artifact calls for it.
- Do not treat “avoid AI clichés” as a style brief. Do not replace one trend with another trend or make every piece deliberately different at the expense of campaign consistency.
- Do not invent an extra accent color, font, certification, claim, button, product feature, or asset. When a color or font is explicitly specified, comply exactly unless the user changes it.

Deliver the finished artifact when asked for a design, with a brief note of any unverified assumption. For critique, report the observed issue, its effect, and the concrete correction. Do not provide a design prompt instead of feasible requested work.
