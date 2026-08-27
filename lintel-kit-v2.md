---
type: Project
status: Active
start: 2026-08-03
belongs_to: "[[lintel-kit]]"
related_to:
  - "[[color-contrast-for-text]]"
  - "[[jae-won-seo]]"
  - "[[accessibility]]"
has:
  - "[[lintel-v2-scope]]"
  - "[[lintel-v2-contrast-pairs-table]]"
  - "[[lintel-v2-dark-mode-token-plan]]"
  - "[[should-v2-be-free-for-existing-buyers]]"
_organized: true
---

# Lintel Kit V2

The second version of Lintel Kit: dark mode and contrast-checked color pairs, plus the documentation fixes buyers asked for.

## Outcome

Version 2 with dark mode and contrast-checked color pairs released to existing buyers by 2026-12-01.

## Current State

- Light and dark modes exist on the semantic collection; 26 of 32 color pairs checked in both modes ([[lintel-v2-contrast-pairs-table]]).
- [[jae-won-seo]] has the dark-mode token output working in a branch; CSS uses a `data-theme` attribute ([[lintel-v2-dark-mode-token-plan]]).
- Getting-started page rewritten after the unmoderated test; text guidance now sits next to the color pairs.
- Free for existing buyers (decided 2026-08-10, [[should-v2-be-free-for-existing-buyers]]). Price for new buyers still open ([[should-the-kit-price-rise-with-v2]]).
- Work is squeezed between Copperline's bill pay handoff (2026-11-27) and Tallowmere.

## Scope and Boundaries

In: dark mode, the color pairs, role-named color tokens, documentation. Out: new components beyond three (toast, inline alert, data table header), Penpot, and the team license, which has its own project ([[lintel-team-license]]).

## Working Context

Two inputs shaped V2. The first is the two-teal lesson from Copperline: a single "primary" color that has to work both as decoration and as text is a bug waiting to happen ([[copperline-accessibility-review-2026-02-11]], [[color-contrast-for-text]]). V1 had `color.primary` used for button labels and illustrations alike; three buyers shipped light-teal button labels that failed contrast. V2 splits accent colors into role-named tokens (`text.accent`, `fill.accent`, `decoration.accent`), each checked against the surfaces it may sit on ([[semantic-color-pairs]]). I showed an early version at the March Design Night talk ([[design-night-talk-2026]]).

The second is buyer research from the Marrowgate course. In the diary study, buyers changed brand colors early and then had no way to tell whether text stayed readable ([[lintel-buyer-diary-study-2026-07-13]]). In the unmoderated test of the getting-started page, the color guidance was hard to find ([[lintel-docs-unmoderated-test-2026-08-24]]).

Dark mode is modes on the same semantic variables, not a second library ([[figma-variables-docs]], [[wikipedia-dark-mode]]). Each pair needs to pass in both modes, which is where the remaining six pairs are stuck: the warning yellow on dark surfaces.

Jae-won's work on V2 is covered by the existing revenue share; no extra fee ([[jae-won-seo-revenue-share-agreement]]).

## Next Actions

- [ ] Finish the six remaining pairs, mainly warning and accent on dark surfaces, by 2026-11-06.
- [ ] Merge Jae-won's dark-mode output and test it in a blank project.
- [ ] Beta to the six diary-study participants by 2026-11-13.
- [ ] Release to all buyers by 2026-12-01 ([[release-a-lintel-kit-update]]).

## Open Questions

- [[should-the-kit-price-rise-with-v2]]
- [[should-lintel-kit-get-a-team-license]]

## Important Notes

- [[lintel-v2-scope]]
- [[lintel-v2-contrast-pairs-table]]
- [[lintel-support-log]]

## Maintenance Log

- 2026-10-12: 26 of 32 pairs pass in both modes.
- 2026-08-10: V2 free for existing buyers.
- 2026-08-03: Started.
