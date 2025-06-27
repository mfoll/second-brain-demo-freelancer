---
type: Procedure
belongs_to: "[[lintel-kit]]"
related_to:
  - "[[lintel-kit-changelog]]"
  - "[[lintel-kit-coded-tokens-repo]]"
  - "[[jae-won-seo]]"
_organized: true
---

# Release A Lintel Kit Update

How a Lintel Kit version goes from the master Figma file to buyers. Written after 1.0.1 and used for 1.1 and 1.2.

## Steps

1. **Pick the week.** No client deadline in it, and the morning after release kept free for support.
2. **Freeze names** seven days before release. No variable renames after this; renames go into the next version.
3. **Export tokens** from the master file and hand them to [[jae-won-seo]]. His build must pass the alias check and the name-match check ([[lintel-kit-coded-tokens-repo]]).
4. **Check contrast** for every pair touched by the release ([[lintel-v2-contrast-pairs-table]] from V2).
5. **Test in a blank file** on a free Figma plan and on a paid one: duplicate, re-brand by editing primitives, check three components.
6. **Update the buyer file** from the master, the ZIP and the getting-started page.
7. **Write the changelog** entry, including deprecations ([[lintel-kit-changelog]]).
8. **Upload to Gumroad** and send the update email to buyers.
9. **Log release-week support** separately in the [[lintel-support-log]].

## After

Note in the [[lintel-kit]] Maintenance Log; if the release changed the price, give Jae-won 30 days' notice beforehand.
