---
type: Source
source_type: Spreadsheet
date_accessed: 2026-02-06
belongs_to: "[[copperline-design-foundations]]"
related_to:
  - "[[color-contrast-for-text]]"
  - "[[copperline-accessibility-review-2026-02-11]]"
  - "[[wcag-contrast-minimum-docs]]"
_organized: true
---

# Copperline Palette Contrast Audit

Spreadsheet checking every foreground and background pair in Copperline's existing and proposed palette, prepared for the 2026-02-11 accessibility review.

## Key Details

- 26 colors from the 2019 brand guidelines, 9 proposed additions; 212 pairs checked.
- Brand teal #2BA59F on white: 3.0:1. Passes large text and non-text (3:1), fails normal text (4.5:1). On the light gray card background #F4F6F6 it drops to 2.8:1 and fails everything.
- White on brand teal: the same 3.0:1, so white button labels fail.
- Proposed text teal #0F766E on white: 5.5:1, passes normal text. On the gray card: 5.0:1.
- Each pair has an "allowed use" column: text, large text only, non-text only, decoration only.
- Ratios computed from hex values, not screenshots.

## Why It Matters

This table is what turned a taste argument with Desmond Okafor into a measurement ([[copperline-accessibility-review-2026-02-11]]). The allowed-use column became the pair table in the signed-off foundations and the model for Lintel Kit V2's contrast-checked pairs.

## Source Location

Copperline shared drive, Design / Foundations / palette-contrast-audit. Working copy in my Clients / Copperline folder.
