---
name: visual-diagrams
description: Turn systems, processes, hierarchies, and relationships into clear rendered diagrams. Use Mermaid for exact structured communication and Rough.js for intentionally hand-drawn interactive web visuals; do not use for decorative imagery or simple facts better stated in prose.
---

# Visual Diagrams

Choose the smallest visual form that makes the relationship easier to understand.

## Choose the medium

- Use **Mermaid** for flows, sequences, states, architecture, entity relationships, timelines, and other structures that benefit from exact labels and deterministic rendering.
- Use **Rough.js** only when the user requests an informal, sketched, workshop, or annotated-whiteboard aesthetic in a web experience.
- Use a table for exact mappings and compact comparisons. Use a charting workflow for quantitative plots. Use prose for one-step relationships.

## Mermaid guidance

- Pick the diagram type that matches the relationship; do not force everything into a flowchart.
- Keep labels short and move explanations outside the diagram.
- Limit horizontal breadth; prefer top-down flow or split a crowded diagram.
- Quote labels containing punctuation. Avoid unsupported HTML labels, click directives, and diagram-level configuration unless the target renderer explicitly supports them.
- Validate the syntax in the target environment when possible.

## Rough.js guidance

- Use semantic HTML or SVG as the interaction and accessibility layer; treat Rough.js as the visual rendering layer.
- Seed randomized rendering when stable output matters.
- Do not use the hand-drawn style for precise data encoding, dense technical architecture, legal or compliance flows, or luxury-brand work unless the user explicitly asks for it.
- Provide text equivalents or accessible labels for meaningful shapes.

Deliver a readable visual, not a dense picture of every available detail.
