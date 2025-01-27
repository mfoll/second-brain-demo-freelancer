---
type: Concept
maturity: Growing
belongs_to: "[[sell-design-kits]]"
related_to:
  - "[[color-contrast-for-text]]"
  - "[[lintel-v2-contrast-pairs-table]]"
  - "[[design-tokens]]"
_organized: true
---

# Semantic Color Pairs

Defining colors as checked foreground and background pairs with a stated use, instead of as single swatches.

## The idea

A color is never readable or unreadable on its own; only a pair is. So the kit should not offer "accent teal" but "accent text on default surface: 5.5:1, any text" and "decoration accent on default surface: 3.0:1, large headings and illustrations only". Each pair is checked in every mode.

## Where it came from

The Copperline accessibility review of 2026-02-11, where the brand teal passed for components and large type and failed for body text, so the palette got a second, darker text teal ([[copperline-accessibility-review-2026-02-11]], [[color-contrast-for-text]]). I generalised it in the Design Night talk ([[design-night-talk-2026]]) and in [[lintel-kit-v2]] ([[lintel-v2-contrast-pairs-table]]).

## Limits

Contrast is one criterion. Pairs say nothing about color-blind distinguishability between states, or about thin fonts. And buyers can still put a token on a surface it was not paired with.
