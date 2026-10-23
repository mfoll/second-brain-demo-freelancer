---
type: Source
source_type: Code repository
date_accessed: 2026-10-12
belongs_to: "[[lintel-kit]]"
related_to:
  - "[[jae-won-seo]]"
  - "[[dtcg-format-module-docs]]"
  - "[[design-tokens]]"
_organized: true
---

# Lintel Kit Coded Tokens Repo

Pointer to the private repository where [[jae-won-seo]] builds Lintel Kit's coded tokens.

## Key Details

- Input: token JSON exported from the Figma library's variables, in the community group's draft format ([[dtcg-format-module-docs]]).
- Output per release: `tokens.json` (and from V2 `tokens.dark.json`), `tokens.css` with custom properties, and a small HTML preview page.
- Checks run on every build: unresolved aliases fail the build (added after [[first-token-bug-report-2025-11-26]]), and names must match the Figma file one to one.
- Branches: `main` is the released 1.2; `v2` has dark-mode output since 2026-09.
- I have read access and review the preview page; Jae-won merges.

## Why It Matters

The coded half of the product and the part covered by the revenue share ([[jae-won-seo-revenue-share-agreement]]). Buyers' developers judge the kit by it.

## Source Location

Private Git repository "lintel-tokens" on Jae-won's account, shared with me. Release ZIPs copied to Lintel / Releases.
