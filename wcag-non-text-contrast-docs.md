---
type: Source
source_type: Standard
url: https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html
date_accessed: 2026-02-04
belongs_to: "[[copperline-design-foundations]]"
related_to:
  - "[[color-contrast-for-text]]"
  - "[[wcag-contrast-minimum-docs]]"
_organized: true
---

# Understanding Success Criterion 1.4.11: Non-text Contrast

W3C's Understanding document for WCAG 2.2 success criterion 1.4.11, Level AA.

## Summary

The visual information needed to identify a user interface component and its state (boundaries, focus indicators, selected states), and the parts of graphics needed to understand content, need at least 3:1 contrast against adjacent colors. Inactive components are exempt. The document stresses that 3:1 is a hard threshold, not rounded (2.999:1 fails), and that thin lines may render fainter than their defined color because of anti-aliasing, so authors should measure from the code and avoid very thin strokes.

## Why It Matters

This is why the brand teal can still be used for component boundaries and illustrations at Copperline, and why focus rings use the text teal. At Tallowmere it is the criterion for seat states that differ only by two grays at 2.1:1 ([[tallowmere-seat-map-findings]]).

## Source Links

- [Understanding Success Criterion 1.4.11: Non-text Contrast](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html), W3C Web Accessibility Initiative.
