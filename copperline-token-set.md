---
type: Source
source_type: Figma file
storage_system: Figma
date_accessed: 2026-04-30
belongs_to: "[[copperline-design-foundations]]"
related_to:
  - "[[design-systems]]"
  - "[[copperline-palette-contrast-audit]]"
  - "[[hollis-dunmore]]"
_organized: true
---

# Copperline Token Set

The Foundations library in Copperline's Figma workspace: tokens as Figma variables and 34 components, as signed off on 2026-04-30.

## Key Details

- About 140 tokens: color (48), type (22), spacing (12), radius (6), elevation (4) and component-level aliases.
- Names by role, agreed with Hollis Dunmore in January 2026: `color.text.default`, `color.text.accent`, `color.surface.brand`, `color.action.primary`, and so on. No color names in token names, so a brand refresh changes values, not code.
- The two teals: `color.action.primary` and `color.text.accent` resolve to #0F766E; `color.surface.brand` and `color.illustration.primary` resolve to #2BA59F.
- Exported to JSON for Hollis's team; they generate CSS custom properties from it.

## Why It Matters

Role naming is what made the second teal cheap to adopt ([[copperline-accessibility-review-2026-02-11]]). I reuse the naming scheme in [[lintel-kit-v2]].

## Source Location

Copperline Figma organisation, "Foundations" file, published library. See [[copperline-figma-workspace]].
