---
type: Source
source_type: Standard
url: https://www.w3.org/WAI/WCAG22/Understanding/reflow.html
date_accessed: 2026-02-16
belongs_to: "[[copperline-online-banking-redesign]]"
related_to:
  - "[[copperline-responsive-first-decision-2026-02-20]]"
  - "[[accessibility]]"
_organized: true
---

# Understanding Success Criterion 1.4.10: Reflow

W3C's Understanding document for WCAG 2.2 success criterion 1.4.10, Level AA.

## Summary

Content should reflow when users enlarge it, so they never have to scroll in two directions to read. The criterion's sizes are a 320 CSS pixel wide viewport for vertically scrolling content (equivalent to 400% zoom on a 1280 pixel screen) and 256 pixels high for horizontally scrolling content. Scrolling back and forth along each line makes people lose their place and adds physical and cognitive effort. Content that needs a two-dimensional layout to make sense, such as a data table or a map, is excepted, though its parts (each table cell) should still reflow.

## Why It Matters

Part of my case to Renata Solberg before the 2026-02-20 board meeting: a responsive site built for phone width already does most of what reflow requires for members who zoom, and 62% of sessions came from phone browsers anyway ([[copperline-responsive-first-decision-2026-02-20]]). The two-dimensional exception also comes up at Tallowmere, where the seat map can be excepted only if a list alternative exists ([[tallowmere-seat-map-findings]]).

## Source Links

- [Understanding Success Criterion 1.4.10: Reflow](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html), W3C Web Accessibility Initiative.
