---
type: Event
date: 2026-10-15
belongs_to: "[[copperline-transfers-and-bill-pay]]"
related_to:
  - "[[how-do-we-fix-payee-search]]"
  - "[[copperline-payee-search-rework-notes]]"
_organized: true
---

# Copperline Payee Search Retest 2026-10-15

Short moderated retest of the reworked payee search: 5 members, 20 minutes each, run by me over video. Recruited by Ana Lucía Ferreyra.

## Results

- 4 of 5 found the payee on the first try by typing the company name. In May, 3 of 10 had failed outright.
- The one miss typed "electric" for a utility whose payee name starts with the town name. Search matched only from the start of each word.
- Everyone used the suggestion list; nobody pressed enter to search.
- The screen reader check (done separately by me with VoiceOver) announced the number of suggestions correctly after the combobox fix ([[wai-aria-combobox-pattern-docs]]).

## Next

Iteration 3: match anywhere in the name and on category keywords for the 15% of payees without clean names. Retest again before 2026-11-13.
