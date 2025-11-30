---
type: Event
date: 2025-11-26
belongs_to: "[[lintel-kit-v1-launch]]"
related_to:
  - "[[mirela-dobos]]"
  - "[[mirela-dobos-token-bug-email]]"
  - "[[jae-won-seo]]"
_organized: true
---

# First Token Bug Report 2025-11-26

[[mirela-dobos]] reported that the focus ring was invisible in her team's build of Lintel Kit's coded tokens.

## What happened

- Cause: an alias to a primitive renamed in Figma the week before launch; the coded output kept the old name ([[mirela-dobos-token-bug-email]]).
- I confirmed it within the hour and messaged [[jae-won-seo]]. He fixed the alias and added a build check that fails on unresolved aliases.
- 1.0.1 shipped on 2025-11-28 with an email to all buyers ([[lintel-kit-changelog]]).

## Why it mattered

A missing focus ring breaks keyboard navigation, the kind of failure I audit clients for. The fix was cheap; the lesson was process: renames happen late, so the alias check is now step one of [[release-a-lintel-kit-update]].
