---
type: Source
source_type: Internal document
date_accessed: 2026-10-16
belongs_to: "[[copperline-transfers-and-bill-pay]]"
related_to:
  - "[[how-do-we-fix-payee-search]]"
  - "[[wai-aria-combobox-pattern-docs]]"
  - "[[hollis-dunmore]]"
_organized: true
---

# Copperline Payee Search Rework Notes

My working notes on the payee search rework since June 2026, kept in the Bill Pay Figma file and summarised here.

## Key Details

- Problem: search matched only the nickname a member gave a payee ("Mum's rent", "power"). Members typed the company name ([[copperline-usability-test-2026-05-21]]).
- Iteration 1 (July): search both nickname and payee name. Hollis Dunmore then found that about 15% of payees in the core platform have no clean company name, only a reference code.
- Iteration 2 (September): editable combobox with suggestions as you type, following the APG pattern so the suggestion count and active option are announced ([[wai-aria-combobox-pattern-docs]]). Matching from the start of each word.
- Retest 2026-10-15: 4 of 5 found the payee first time ([[copperline-payee-search-retest-2026-10-15]]).
- Iteration 3 (now): match anywhere in the name; add category keywords ("electric", "water", "phone") for payees from a list Copperline maintains; for the 15% without clean names, show the last payment date and amount as a second line so members recognise them.

## Caveats

The category list depends on Copperline's operations team keeping it up to date. If they do not, iteration 3 degrades to iteration 2, which is still better than May.

## Source Location

Copperline Figma, "Bill Pay" file, page "Payee search iterations".
