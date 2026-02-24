---
type: Source
source_type: Standard
url: https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html
date_accessed: 2026-02-24
belongs_to: "[[design-night-talk-2026]]"
related_to:
  - "[[color-contrast-for-text]]"
  - "[[accessibility]]"
_organized: true
---

# Understanding Success Criterion 1.4.11: Non-text Contrast

## Summary

W3C's explanatory page for WCAG 2.2 success criterion 1.4.11 (Level AA). Visual information needed to identify interface components and their states, and the meaningful parts of graphics, needs a contrast ratio of at least 3:1 against adjacent colors. The page treats 3:1 as a hard threshold. Exceptions include inactive components, components styled entirely by the browser, graphics where a specific presentation is essential (such as logos and flags), and decorative graphics.

## Why It Matters

The second half of the argument in my [[design-night-talk-2026]]. Text needs 4.5:1 (3:1 when large), but borders, icons, focus indicators and the shape of a button only need 3:1. That is why a 3.0:1 brand color can still be used for component outlines and large type and fail as a button label, the same split as the Copperline two-teal decision ([[copperline-accessibility-review-2026-02-11]], [[color-contrast-for-text]]). I used my own made-up brand color in the talk, not Copperline's.

## Key Details

- Applies to what is needed to identify a control and its state, not to every pixel of it.
- Hover styles don't have to meet 3:1.
- A low-contrast logo is exempt only when the brand requires it, not as a free design choice.

## Caveats

Doesn't cover text contrast (that is 1.4.3) or focus appearance in detail. The page has been updated since I read it for the talk; re-check before quoting it in an audit.

## Source Links

- [Understanding Success Criterion 1.4.11: Non-text Contrast](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html), W3C Web Accessibility Initiative.
