---
type: Project
status: Completed
start: 2026-01-05
end: 2026-04-30
belongs_to: "[[copperline-online-banking-redesign]]"
related_to:
  - "[[desmond-okafor]]"
  - "[[gideon-marsh]]"
  - "[[design-systems]]"
has:
  - "[[copperline-accessibility-review-2026-02-11]]"
  - "[[copperline-token-set]]"
  - "[[copperline-palette-contrast-audit]]"
  - "[[copperline-foundations-signoff-2026-04-30]]"
_organized: true
---

# Copperline Design Foundations

The design system layer for Copperline: tokens, components and an accessible palette in Copperline's own Figma workspace, built before and alongside the first redesigned flows.

## Outcome

Token set, component library and accessible palette in Copperline's Figma workspace, signed off by the brand and compliance teams. Reached on 2026-04-30 ([[copperline-foundations-signoff-2026-04-30]]).

## Current State

- Completed. The library is published in Copperline's Figma organisation and consumed by the transfers and bill pay files ([[copperline-token-set]]).
- The palette has two teals. Brand teal #2BA59F (3.0:1 on white) is for illustrations, large headings and decoration. Text teal #0F766E (5.5:1) is for body links, text and filled buttons.
- Desmond Okafor signed off but still calls the text teal "the hospital color". Expect him to raise it again at launch.

## Scope and Boundaries

Color, type, spacing and radius tokens; 34 components; light mode only (dark mode is not in Copperline's plans). Not the marketing site, which uses Copperline's agency.

## Working Context

The decision that shaped this phase was the two teals. Copperline's 2019 brand guidelines ([[copperline-brand-guidelines-2019]]) put the brand teal on everything, including white button labels. My contrast audit ([[copperline-palette-contrast-audit]]) showed it at 3.0:1: fine for large text and component boundaries, not for body text or button labels, which need 4.5:1 ([[color-contrast-for-text]], [[wcag-contrast-minimum-docs]], [[wcag-non-text-contrast-docs]]).

At the accessibility review on 2026-02-11 ([[copperline-accessibility-review-2026-02-11]]) I proposed a darker text teal and kept the brand teal for what it can carry. Desmond wanted primary buttons in the original teal. Gideon Marsh backed me on regulatory and member-complaint grounds. Renata signed off the two-teal palette with the rest of the foundations on 2026-04-30.

Hollis Dunmore asked for token names that map straight to CSS custom properties; we used role names (`color.text.accent`, `color.surface.brand`) rather than color names so the next brand refresh does not break code.

The same lesson went into the Lintel Kit as contrast-checked pairs ([[lintel-kit-v2]]) and into my talk ([[design-night-talk-2026]]).

## Important Notes

- [[copperline-accessibility-review-2026-02-11]]
- [[can-buttons-use-the-brand-teal]]
- [[accessibility-is-cheapest-in-the-design-system]]
- [[copperline-design-principles]]

## Maintenance Log

- 2026-04-30: Signed off by Renata, with brand and compliance present.
- 2026-02-11: Two-teal decision at the accessibility review.
- 2026-01-05: Started, overlapping the end of the native app sprint.
