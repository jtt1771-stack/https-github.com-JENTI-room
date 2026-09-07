---
name: premium-web-design
description: Design or refine polished, brand-led websites and web interfaces using an intentional visual system. Use for landing pages, storefronts, portfolios, editorial sites, and product UI where visual quality matters; do not use for standalone raster artwork or document layout.
---

# Premium Web Design

Create a coherent web experience whose typography, spacing, color, imagery, and interaction express the subject rather than a generic template.

## Visual direction

- Establish one concise visual thesis before editing. Carry it through type scale, layout rhythm, surfaces, image treatment, controls, and motion.
- Preserve an existing brand system. When none exists, derive a restrained palette and type pairing from the subject and audience.
- Make one memorable compositional choice, but keep navigation and primary actions immediately understandable.
- Avoid shipping a default component-library theme, excessive cards, ornamental gradients, filler copy, or decorative interface elements without a purpose.
- Design mobile and desktop together. Main text should normally be at least 16px, with usable contrast, focus states, touch targets, and reduced-motion behavior.

## Library routing

Use the libraries only when they fit the existing stack. Inspect the package manager and declared dependencies before proposing or installing anything.

- **shadcn/ui:** Prefer for accessible React interaction primitives such as dialogs, sheets, menus, tabs, forms, and selectors. Compose and restyle components; the generated default theme is not the finished design.
- **Radix Colors:** Use as a starting scale for accessible UI states and dark/light themes. Map scales into semantic tokens such as background, surface, text, border, accent, and danger instead of scattering raw color names.
- **Fontsource:** Use when self-hosted open-source web fonts improve reliability or privacy. Load only required families, weights, and character subsets; include appropriate CJK fallbacks when Chinese text is present.
- **Simple Icons:** Use only for real brand or platform marks. Preserve recognizable geometry, provide accessible labels, and do not use brand icons as generic interface symbols.

Do not add every library merely because this skill loaded. Use platform-native HTML and CSS when that is the clearer and lighter solution. Ask before making a dependency change that materially expands the user's project.

## Delivery check

Verify the primary route, responsive layout, local asset references, keyboard interaction, and production build. Remove placeholder content and unused starter styling before handing off.
