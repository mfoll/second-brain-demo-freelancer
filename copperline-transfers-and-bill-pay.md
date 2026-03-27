---
type: Project
status: Active
start: 2026-03-02
belongs_to: "[[copperline-online-banking-redesign]]"
related_to:
  - "[[hollis-dunmore]]"
  - "[[imani-clarke]]"
  - "[[system-usability-scale]]"
has:
  - "[[copperline-usability-test-2026-05-21]]"
  - "[[copperline-prototype-test-findings]]"
  - "[[how-do-we-fix-payee-search]]"
  - "[[copperline-payee-search-rework-notes]]"
_organized: true
---

# Copperline Transfers And Bill Pay

Phase 2 flows for Copperline: moving money between accounts and to other members, and paying bills, designed on the new foundations, tested with members and handed off to Copperline's developers.

## Outcome

Tested high-fidelity designs for transfers and bill pay handed off to Copperline's developers by 2026-11-27.

## Current State

- Transfers are done and tested: SUS 76 on the prototype, 9 of 10 completed a transfer between own accounts unaided, against 5 of 12 on the old site ([[copperline-usability-test-2026-05-21]]).
- Bill pay is not done. Payee search failed for 3 of 10 participants, who typed a company name and got nothing because the list matched only the nickname members had given the payee. Rework in progress ([[how-do-we-fix-payee-search]], [[copperline-payee-search-rework-notes]]).
- A quick retest of the reworked search on 2026-10-15 with 5 members: 4 of 5 found the payee on the first try ([[copperline-payee-search-retest-2026-10-15]]). One more iteration before handoff.
- Transfers handed off in July; Hollis's team has them in a staging build. Bill pay handoff is the 2026-11-27 milestone in the [[copperline-bill-pay-change-order-2026-06-24|change order]].

## Scope and Boundaries

Own-account transfers, member-to-member transfers, scheduled and recurring transfers, bill pay (payees, one-off and recurring payments). Not external transfers to other banks (Copperline's vendor limits them), not card controls.

## Working Context

Started 2026-03-02 while foundations were still open so components met real flows early. The biggest structural change from the old site: "Move money" is gone; transfers and bill pay are top-level and the accounts overview has a transfer button on each account card. Confirmation screens restate amount, from, to and date in one sentence, which helped the older members most in testing.

The prototype test on 2026-05-21 used 10 members recruited by Ana Lucía Ferreyra. Imani Clarke moderated 4 sessions and I moderated 6; we used the same script ([[copperline-prototype-test-plan]]). Renata Solberg and Gideon Marsh watched two sessions live, which settled more than any deck ([[clients-should-watch-users-struggle]]).

Accessibility checks specific to these flows: no re-entry of data already given in a multi-step transfer ([[wcag-redundant-entry-docs]]), target sizes on the amount keypad ([[wcag-target-size-minimum-docs]]), and the payee search rebuilt as an editable combobox ([[wai-aria-combobox-pattern-docs]]).

These numbers are the evidence Velora said my portfolio lacked ([[velora-feedback-call-2026-06-03]]). They can only be published after Copperline approves ([[will-copperline-approve-a-case-study]]).

## Next Actions

- [ ] Finish payee search iteration 3 and retest with at least 5 members by 2026-11-13.
- [ ] Annotate bill pay files for handoff with [[hand-off-designs-to-developers]].
- [ ] Walk Hollis's team through edge cases (failed payment, payee deleted mid-schedule) on 2026-11-20.
- [ ] Send final handoff and milestone invoice on 2026-11-27.

## Open Questions

- [[how-do-we-fix-payee-search]]
- [[should-i-propose-copperline-phase-3]]

## Important Notes

- [[copperline-usability-test-2026-05-21]]
- [[copperline-prototype-test-findings]]
- [[imani-clarke-copperline-subcontract]]
- [[copperline-statement-of-work]]

## Maintenance Log

- 2026-10-15: Payee search retest, 4 of 5.
- 2026-07-10: Transfers handed off to Hollis's team.
- 2026-06-24: Change order signed: bill pay handoff moved to 2026-11-27.
- 2026-05-21: Prototype test, SUS 76.
- 2026-03-02: Started.
