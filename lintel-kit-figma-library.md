---
type: Source
source_type: Internal design file
date_accessed: 2026-10-12
belongs_to: "[[lintel-kit]]"
related_to:
  - "[[figma-variables-docs]]"
  - "[[design-tokens]]"
  - "[[lintel-kit-v2]]"
_organized: true
---

# Lintel Kit Figma Library

Pointer to the master Figma file for Lintel Kit and a short map of what is in it.

## Key Details

- Three variable collections: Primitives (about 90: color ramps, spacing, radius, type scale), Semantic (about 70: text, surface, border, action, feedback), Component (about 20 aliases for component-specific states).
- 42 components in V1.2, all wired to semantic or component variables, never to primitives directly.
- Rule: a buyer re-brands by editing primitives only. If a component needs a raw value, the token structure is wrong.
- V2 branch: a Dark mode on the Semantic collection; color tokens renamed by role (`text.accent`, `fill.accent`, `decoration.accent`) ([[lintel-v2-dark-mode-token-plan]]).
- Published versions are duplicated into a buyer-facing file that Gumroad links to; the master stays private.

## Why It Matters

This is the product. Every release starts here and ends with the buyer copy ([[release-a-lintel-kit-update]]).

## Source Location

Figma, my personal team, project "Lintel", files "Lintel master" and "Lintel buyer V1.2". V2 work is on the "v2" branch of the master file.
