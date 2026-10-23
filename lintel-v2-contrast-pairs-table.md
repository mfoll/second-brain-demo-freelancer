---
type: Source
source_type: Internal spreadsheet
date_accessed: 2026-10-12
belongs_to: "[[lintel-kit-v2]]"
related_to:
  - "[[semantic-color-pairs]]"
  - "[[color-contrast-for-text]]"
_organized: true
---

# Lintel V2 Contrast Pairs Table

The table of foreground and background token pairs that V2 promises are readable, with contrast ratios in light and dark mode. Status at 2026-10-12.

## Key Details

- 32 pairs: 18 text pairs (must reach 4.5:1, or 3:1 where marked large text only) and 14 non-text pairs (icons, borders, focus rings: 3:1).
- 26 pass in both modes. The six open ones: warning text and warning fill on dark surfaces, accent text on the subtle-accent surface in dark mode, and three border pairs that pass at 2.9:1 to 3.0:1 depending on rounding.
- Each pair names its allowed use. Example: `decoration.accent` on `surface.default` is allowed for illustrations and large headings only.
- Ratios computed with the standard relative-luminance formula in the sheet and spot-checked in Figma.

## Why It Matters

This is the two-teal lesson made into a product feature: a brand color can be fine for decoration and wrong for text ([[copperline-accessibility-review-2026-02-11]], [[semantic-color-pairs]]). The table also becomes a page in the V2 documentation.

## Caveats

Contrast ratios are necessary, not sufficient: they say nothing about font weight or color-blind distinguishability.

## Source Location

Spreadsheet "V2 pairs" in the Lintel folder.
