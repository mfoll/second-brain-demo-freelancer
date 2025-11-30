---
type: Source
source_type: Email
date_accessed: 2025-11-26
belongs_to: "[[lintel-kit-v1-launch]]"
related_to:
  - "[[mirela-dobos]]"
  - "[[first-token-bug-report-2025-11-26]]"
_organized: true
---

# Mirela Dobos Token Bug Email

[[mirela-dobos]]'s email of 2025-11-26 reporting the first bug in Lintel Kit's coded tokens. Summarised.

## Key Details

- Symptom: the focus ring was invisible in her team's build.
- Cause she found: the CSS variable for the focus ring pointed to a primitive token that had been renamed in the Figma file the week before launch; the coded tokens still used the old name, so the variable resolved to nothing.
- She included the token name, the exported line, the expected value and a screenshot.
- Fix: [[jae-won-seo]] corrected the alias and added a build check that fails on unresolved aliases. Released as 1.0.1 on 2025-11-28.

## Why It Matters

The best bug report the kit has had, and the reason every release now runs the alias check ([[release-a-lintel-kit-update]]). A missing focus ring is an accessibility failure, not a cosmetic one.

## Source Location

Lintel mailbox, thread "Focus ring missing in 1.0".
