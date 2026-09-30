---
type: Source
source_type: Standard
url: https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html
date_accessed: 2026-09-22
belongs_to: "[[tallowmere-ticketing-audit]]"
related_to:
  - "[[tallowmere-seat-map-findings]]"
  - "[[copperline-transfers-and-bill-pay]]"
_organized: true
---

# Understanding Success Criterion 2.5.8: Target Size (Minimum)

W3C's Understanding document for WCAG 2.2 success criterion 2.5.8, Level AA, new in 2.2.

## Summary

Pointer targets should be at least 24 by 24 CSS pixels, so people with tremors, limited dexterity or less precise input devices do not hit the wrong control. Smaller targets can pass under five exceptions: spacing (a 24 px circle centered on each small target does not overlap another target or circle), an equivalent larger control for the same function, inline links in text, sizes set by the user agent, and cases where the size is essential. The document recommends meeting the size even when spacing would allow less, and pointing to the stricter 2.5.5 for important controls.

## Why It Matters

Tallowmere's seats are 16 px with 2 px gaps on a phone: they fail both size and spacing ([[tallowmere-seat-map-findings]]). The "equivalent control" exception is why a list-based seat picker could make the map acceptable. At Copperline it set the size of the amount keypad and the account card buttons.

## Source Links

- [Understanding Success Criterion 2.5.8: Target Size (Minimum)](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html), W3C Web Accessibility Initiative.
