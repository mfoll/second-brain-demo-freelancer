---
type: Source
source_type: Standard
url: https://www.designtokens.org/tr/drafts/format/
date_accessed: 2026-09-29
belongs_to: "[[lintel-kit-v2]]"
related_to:
  - "[[design-tokens]]"
  - "[[lintel-kit-coded-tokens-repo]]"
  - "[[jae-won-seo]]"
_organized: true
---

# Design Tokens Format Module 2025.10

## Summary

The Design Tokens Community Group's draft specification for a JSON file format that lets design tools and code tools exchange tokens. The page is a Draft Community Group Report, explicitly not a W3C Standard, and the version I read was dated 8 September 2026 with a warning not to implement the preview draft.

## Why It Matters

[[jae-won-seo]] has generated Lintel Kit's coded tokens in this format's style since V1 ([[lintel-kit-coded-tokens-repo]]). For [[lintel-kit-v2]] we re-read it to decide how to express dark mode and the color pairs without inventing our own keys. Penpot imports and exports the same shape ([[penpot-design-tokens-docs]]), which is the main reason a Penpot version is cheaper than I first thought ([[should-lintel-kit-support-penpot]]).

## Key Details

- Each token is a JSON object with a required `$value`. A `$type` is required too, either on the token or inherited from its group.
- Aliases point at another token with curly braces, for example `{color.text.accent}`; a JSON Pointer `$ref` can reference a single property.
- Groups organise tokens; they can carry a `$root` token and use `$extends` to inherit from another group.
- Composite types (shadow, border, transition and others) combine sub-values; color is specified in a separate Color module.
- Our use: primitives, semantic and component layers as nested groups; semantic tokens alias primitives, never raw values.

## Caveats

- A draft that has changed since V1 shipped. Our V1 files predate some of these keys, so V2 is the moment to align; buyers who import tokens into other tools may see differences.
- The spec does not say how to represent light and dark modes in one file. Our choice (one file per mode, same token names) is ours ([[lintel-v2-dark-mode-token-plan]]).

## Source Links

- [Design Tokens Format Module 2025.10](https://www.designtokens.org/tr/drafts/format/) (Design Tokens Community Group draft report)
