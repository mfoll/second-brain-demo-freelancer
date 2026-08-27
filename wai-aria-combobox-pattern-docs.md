---
type: Source
source_type: Documentation
url: https://www.w3.org/WAI/ARIA/apg/patterns/combobox/
date_accessed: 2026-08-25
belongs_to: "[[copperline-transfers-and-bill-pay]]"
related_to:
  - "[[how-do-we-fix-payee-search]]"
  - "[[copperline-payee-search-rework-notes]]"
_organized: true
---

# Combobox Pattern

The Combobox pattern page in the W3C WAI-ARIA Authoring Practices Guide.

## Summary

A combobox is an input with an associated popup (listbox, grid, tree or dialog) from which users choose a value. It is either select-only or editable; an editable combobox may accept any value or restrict it to allowed values, with typing used to filter suggestions. The popup is collapsed by default, and the page lists the conditions that can expand it, the keyboard interaction (arrow keys, Enter, Escape) and the roles and states that let assistive technology announce the active option.

## Why It Matters

Payee search iteration 2 at Copperline rebuilds the search as an editable combobox restricted to the member's payees, following this pattern so screen readers announce the number of suggestions and the active one. Hollis Dunmore's team uses the APG examples as the reference implementation. The 2026-10-15 retest confirmed the announcements work ([[copperline-payee-search-retest-2026-10-15]]).

## Caveats

APG patterns are guidance, not requirements; screen reader support for comboboxes varies, so we still test with VoiceOver and NVDA.

## Source Links

- [Combobox Pattern](https://www.w3.org/WAI/ARIA/apg/patterns/combobox/), WAI-ARIA Authoring Practices Guide, W3C.
