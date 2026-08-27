---
type: Source
source_type: Internal document
date_accessed: 2026-08-12
belongs_to: "[[lintel-kit-v2]]"
related_to:
  - "[[figma-variables-docs]]"
  - "[[wikipedia-dark-mode]]"
  - "[[jae-won-seo]]"
_organized: true
---

# Lintel V2 Dark Mode Token Plan

The plan [[jae-won-seo]] and I agreed on 2026-08-12 for adding dark mode to Lintel Kit.

## Key Details

- Figma: a second mode, Dark, on the Semantic collection. Primitives stay single-mode; dark values are aliases to different primitives (for example `surface.default` points to neutral-950 in Dark).
- Names do not change between modes; components need no edits.
- New dark-only primitives: four neutrals and two accent steps, because the light ramps had no usable dark surfaces.
- Code: one JSON file per mode with identical token names; CSS outputs `:root` for light and `[data-theme="dark"]` for dark, plus a `prefers-color-scheme` block that buyers can delete.
- Contrast: every text and fill pair must pass in both modes ([[lintel-v2-contrast-pairs-table]]).
- Rejected: a separate dark library (doubles maintenance), and auto-inverting colors (fails contrast in the middle of the ramps).

## Why It Matters

The structure decision for [[lintel-kit-v2]]; changing it after release would break buyers' files.

## Source Location

Shared document "V2 dark mode plan" in the Lintel folder.
