---
type: Question
status: Open
belongs_to: "[[copperline-transfers-and-bill-pay]]"
related_to:
  - "[[copperline-payee-search-rework-notes]]"
  - "[[wai-aria-combobox-pattern-docs]]"
  - "[[hollis-dunmore]]"
_organized: true
---

# How Do We Fix Payee Search

How can Copperline members reliably find a bill payee by typing what they think it is called, when the data only has nicknames for some payees and reference codes for others?

## Current state

- May 2026: 3 of 10 failed to find a payee by company name ([[copperline-usability-test-2026-05-21]]).
- October 2026, iteration 2 (combobox, match from word start, nickname and payee name): 4 of 5 found it first try ([[copperline-payee-search-retest-2026-10-15]]).
- About 15% of payees have no clean company name in the core platform (Hollis Dunmore).

## Options in play

- Iteration 3: match anywhere in the name, category keywords, last payment date and amount as a recognition cue. My preference.
- Ask members to rename unnamed payees the first time they use the new bill pay. Rejected for now: it adds a step before a payment, and Gideon Marsh worried about members renaming payees misleadingly.
- Ask Copperline operations to clean the payee data. The right long-term fix and not possible before 2026-11-27.

## What would settle it

At least 5 of 5, or 9 of 10, in the retest before 2026-11-13, including one screen reader user. If iteration 3 misses, hand off iteration 2 with the data clean-up logged as a phase 3 item ([[should-i-propose-copperline-phase-3]]).
