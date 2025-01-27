---
type: Concept
maturity: Evergreen
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[accessibility]]"
  - "[[wcag-contrast-minimum-docs]]"
  - "[[wcag-non-text-contrast-docs]]"
  - "[[copperline-accessibility-review-2026-02-11]]"
_organized: true
---

# Color Contrast For Text

How readable a color is against its background, measured as a ratio, and why the same brand color can be fine for a button outline and fail for the button's label.

## Definition

> [!info]
> Contrast ratio compares the relative luminance of two colors, from 1:1 (identical) to 21:1 (black on white). WCAG 2.2 AA asks for at least 4.5:1 for normal text, 3:1 for large text, and 3:1 for the visual parts of interface components and meaningful graphics. Hue does not enter the formula; only lightness does.

## The thresholds I use

- **4.5:1** for body text, links in text, form labels, placeholder text that carries meaning, and button labels at normal size ([[wcag-contrast-minimum-docs]]).
- **3:1** for large text: about 24 px regular or 18.66 px bold and up.
- **3:1** for component boundaries, focus indicators, icons that carry meaning and chart elements against adjacent colors ([[wcag-non-text-contrast-docs]]).
- Thresholds are not rounded. 2.99:1 fails 3:1.
- Disabled controls and pure decoration are exempt. Logos too.

## Why a brand color can pass and fail at once

Mid-tone brand colors (teals, oranges, light greens) often land between 3:1 and 4.5:1 on white. Such a color is fine for a button's fill seen as a shape, for a large heading, or for an illustration, and it fails for the white label on that button or for a text link. Copperline's brand teal #2BA59F is exactly 3.0:1 on white: it passes for large text and components, fails for text. Hence the two-teal palette: text teal #0F766E at 5.5:1 for text and filled buttons ([[copperline-accessibility-review-2026-02-11]]).

The common mistakes I see in audits:

- Checking a color against white only, when it actually sits on a light gray card.
- Calling 16 px semibold "large text". It is not.
- Treating focus rings as decoration. They are interface state and need 3:1.
- Fixing contrast by making text bigger, which breaks layouts at 200% zoom.

## How I work with it

- In a design system, name tokens by role (`color.text.accent`) and check every allowed text and background pair when the token is defined, not when a screen is reviewed. See [[accessibility-is-cheapest-in-the-design-system]].
- Keep a pair table: which foreground may be used on which background, with ratio and allowed use. Copperline's is [[copperline-palette-contrast-audit]]; Lintel Kit V2 ships the same idea as contrast-checked pairs ([[lintel-kit-v2]]).
- In audits, measure from the code or the design file, not from a screenshot, because anti-aliasing makes thin text look lighter than it is.

## Limits

The ratio is a proxy. Very thin fonts can fail readers at 4.5:1, and some pairs that pass are still tiring to read. Newer contrast models weigh font size and weight more carefully; I mention them to clients but audit against WCAG 2.2, which is what contracts and regulators cite ([[wikipedia-web-content-accessibility-guidelines]]).

## Related

[[accessibility]], [[design-night-talk-2026]], [[can-buttons-use-the-brand-teal]].
