---
type: Source
source_type: Standard
url: https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html
date_accessed: 2026-02-04
belongs_to: "[[copperline-design-foundations]]"
related_to:
  - "[[color-contrast-for-text]]"
  - "[[wcag-non-text-contrast-docs]]"
  - "[[accessibility]]"
_organized: true
---

# Understanding Success Criterion 1.4.3: Contrast (Minimum)

W3C's Understanding document for WCAG 2.2 success criterion 1.4.3, Level AA.

## Summary

Text and images of text need a contrast ratio of at least 4.5:1 with their background, or 3:1 for large-scale text. The intent is that people with moderately low vision or reduced contrast sensitivity can read text without assistive technology. The ratio is built on relative luminance, so hue barely matters: what counts is light against dark. Large text gets the lower threshold because wider strokes stay readable at lower contrast; the document places the cut-off at 18 point, or 14 point bold. Purely decorative text, logos and inactive components are exempt.

## Why It Matters

The threshold behind the two-teal decision. Copperline's brand teal sits at 3.0:1 on white, so it can carry large headings but not body text or 16 px button labels ([[copperline-accessibility-review-2026-02-11]]). I quote this page to Gideon Marsh and to every audit client when contrast comes up; summary in [[color-contrast-for-text]].

## Key Details

- 4.5:1 normal text; 3:1 large text (18 pt, or 14 pt bold, roughly 24 px and 18.66 px).
- Font size is taken from what the user agent renders, and very thin fonts may need more than the minimum.

## Source Links

- [Understanding Success Criterion 1.4.3: Contrast (Minimum)](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html), W3C Web Accessibility Initiative.
