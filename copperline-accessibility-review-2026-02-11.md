---
type: Event
date: 2026-02-11
belongs_to: "[[copperline-design-foundations]]"
related_to:
  - "[[desmond-okafor]]"
  - "[[gideon-marsh]]"
  - "[[color-contrast-for-text]]"
  - "[[copperline-palette-contrast-audit]]"
_organized: true
---

# Copperline Accessibility Review 2026-02-11

Ninety-minute review of the draft palette and core components at Copperline's office, with Renata Solberg, Desmond Okafor, Gideon Marsh, Priyanka Venkat and Hollis Dunmore. The meeting where the two-teal palette was decided.

## At a Glance

> [!note]
> Decision: Copperline gets two teals. Brand teal #2BA59F (3.0:1 on white) stays for illustrations, large headings and decoration; a darker text teal #0F766E (5.5:1) is used for body text, links and filled buttons. Desmond Okafor disagreed, Gideon Marsh supported, Renata Solberg asked for the full foundations before signing off, which she did on 2026-04-30.

## Context

Copperline's brand guidelines ([[copperline-brand-guidelines-2019]]) use the brand teal for everything, including white labels on teal buttons and teal links in body text. My [[copperline-palette-contrast-audit]] measured the brand teal at 3.0:1 against white. That passes the 3:1 threshold for large text and for component boundaries ([[wcag-non-text-contrast-docs]]), and fails the 4.5:1 needed for normal text, including button labels ([[wcag-contrast-minimum-docs]]). Discovery had already heard it from members: 4 of 5 over-60 participants called the teal buttons hard to read ([[copperline-research-report]]). Background in [[color-contrast-for-text]].

## What happened

1. I showed the audit table and A3 prints of the current buttons and links at reading distance. Then three options: darken the brand teal everywhere; keep it and use dark text on teal buttons; introduce a second, darker teal for text and filled buttons.
2. Desmond rejected darkening the brand teal everywhere outright: the logo and the branch signage use it. He also disliked dark labels on teal buttons ("looks like a warning"). He wanted primary buttons to stay brand teal with white labels and argued that large bold labels would count as large text.
3. I checked: our button labels are 16 px semibold, well under the large-text size. Making them large enough to pass would have meant 24 px labels, which nobody wanted.
4. Gideon said Copperline had two written member complaints in 2025 about unreadable buttons, and that he would rather not explain a known failure to the examiner. That changed the room.
5. Hollis said the second teal costs nothing to build if tokens are named by role, not by color ([[copperline-token-set]]).
6. Renata agreed to the two-teal approach in principle and asked to see it across the whole component set before signing off.

## Decisions

- Text teal #0F766E for text, links, filled button backgrounds with white labels, and focus rings.
- Brand teal #2BA59F for illustrations, headings at 24 px and above, the header band and decorative surfaces.
- Desmond owns where the brand teal goes. That gave him something real to own and has kept the peace.

## Dissent

Desmond still disagrees. He called the dark teal "the hospital color" in the meeting and again at sign-off, and wants primary buttons back in brand teal at the next brand refresh. Recorded in [[can-buttons-use-the-brand-teal]].

## Follow-up

- Full foundations signed off on 2026-04-30 ([[copperline-foundations-signoff-2026-04-30]]).
- The idea became contrast-checked color pairs in [[lintel-kit-v2]] and the subject of my talk at [[design-night-talk-2026]].
