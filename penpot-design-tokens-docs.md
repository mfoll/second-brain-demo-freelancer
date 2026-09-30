---
type: Source
source_type: Documentation
url: https://help.penpot.app/user-guide/design-tokens/
date_accessed: 2026-09-29
belongs_to: "[[lintel-kit]]"
related_to:
  - "[[should-lintel-kit-support-penpot]]"
  - "[[dtcg-format-module-docs]]"
_organized: true
---

# Design Tokens

## Summary

The Penpot user guide page on design tokens. Penpot lets you create tokens in a Tokens panel, reference other tokens in their values and apply them to layers. Tokens are grouped into sets, and themes switch combinations of sets, for example by brand or mode. Import and export follow the W3C community group format (`$value`, `$type`, `$description`) as a single JSON file or a multi-file folder with theme and metadata files.

## Why It Matters

Three of the five Lintel Kit refunds were buyers who expected Penpot files ([[lintel-sales-dashboard]]). In September 2026 I read this page to see whether a Penpot edition could reuse [[jae-won-seo]]'s token JSON instead of a rebuild. It largely can for tokens; components would still be rebuilt by hand. That changes the cost estimate in [[should-lintel-kit-support-penpot]] from "a second kit" to about 40 hours, still too much before V2 ships.

## Key Details

- Token types include color, dimension, spacing, sizing, border radius, opacity, rotation, stroke width and number, typography tokens and composite typography, and shadows.
- Sets: later sets override earlier ones with the same token name; sets can be switched on and off.
- Themes apply combinations of sets; several themes can be active, one per theme group. Light and dark would be a theme group.
- Listed limitations: font sizes in px only for now, line height only inside typography composites, tokens cannot be applied to groups, token references are case sensitive.

## Caveats

Read in September 2026; the feature is moving quickly and the limitations list may be out of date when I revisit. Nothing here covers components or libraries, which are the expensive part of a Penpot edition.

## Source Links

- [Design Tokens, Penpot user guide](https://help.penpot.app/user-guide/design-tokens/)
