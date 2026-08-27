---
type: Source
source_type: Documentation
url: https://help.figma.com/hc/en-us/articles/15339657135383-Guide-to-variables-in-Figma
date_accessed: 2026-08-04
belongs_to: "[[lintel-kit-v2]]"
related_to:
  - "[[lintel-kit-figma-library]]"
  - "[[lintel-v2-dark-mode-token-plan]]"
  - "[[design-tokens]]"
_organized: true
---

# Guide to variables in Figma

## Summary

Figma's Help Center guide to variables: stored, reusable values that can be applied to design properties and prototype logic. Variables are grouped into collections; a variable can have several values, one per mode, which lets a design switch context such as light and dark themes. The page shows no last-updated date.

## Why It Matters

Lintel Kit's library is built on variables: about 180 in three collections ([[lintel-kit-figma-library]]). Modes are how [[lintel-kit-v2]] adds dark mode without a second library: the semantic collection gets a Dark mode whose values alias different primitives ([[lintel-v2-dark-mode-token-plan]]). I re-read the guide on the second day of V2 to check what buyers need on their side.

## Key Details

- Variables hold reusable values; the guide mentions color and number variables, and expressions that work with strings, numbers and booleans.
- Collections group variables; extending a collection can help with multi-brand systems.
- Modes give one variable several definitions, used for contexts like light and dark.
- Variables can reference other variables, which is how semantic tokens point to primitives.
- Using variables in prototypes and publishing them to team libraries needs an education plan or a paid plan.

## Caveats

- The plan requirement matters for buyers: a buyer on a free plan can use the kit in one file but cannot publish it as a team library. The getting-started page now says so after two support tickets ([[lintel-support-log]]).
- The guide does not mention a limit on modes; I have not hit one with two modes.

## Source Links

- [Guide to variables in Figma](https://help.figma.com/hc/en-us/articles/15339657135383-Guide-to-variables-in-Figma) (Figma Learn, Help Center)
