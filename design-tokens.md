---
type: Concept
maturity: Evergreen
belongs_to: "[[sell-design-kits]]"
related_to:
  - "[[design-systems]]"
  - "[[dtcg-format-module-docs]]"
  - "[[semantic-color-pairs]]"
_organized: true
---

# Design Tokens

Named design decisions (a color, a spacing step, a radius) stored as data so that design files and code use the same values from one source.

## How I use the idea

- **Three layers.** Primitives hold raw values (`teal-600`, `space-4`). Semantic tokens say what a value is for (`text.accent`, `surface.default`) and alias primitives. Component tokens cover the few cases where a component needs its own decision.
- **Name by role, not hue.** A token called `teal-500` invites someone to use it for a button label. A token called `decoration.accent` tells them not to. This is the lesson of Copperline's two teals ([[copperline-token-set]], [[color-contrast-for-text]]).
- **Modes, not copies.** Light and dark are two values for the same semantic token ([[lintel-v2-dark-mode-token-plan]]).
- **One source.** In Lintel Kit the Figma variables are the source and code is generated from them ([[lintel-kit-figma-library]], [[lintel-kit-coded-tokens-repo]]).

## Limits

Tokens make decisions consistent; they do not make them right. A token set can encode an inaccessible palette perfectly. And a format is still a draft, so tools disagree at the edges ([[dtcg-format-module-docs]], [[figma-variables-docs]]).
