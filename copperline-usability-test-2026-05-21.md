---
type: Event
date: 2026-05-21
belongs_to: "[[copperline-transfers-and-bill-pay]]"
related_to:
  - "[[imani-clarke]]"
  - "[[system-usability-scale]]"
  - "[[copperline-prototype-test-findings]]"
_organized: true
---

# Copperline Usability Test 2026-05-21

One day of moderated usability testing of the transfers and bill pay prototype with 10 Copperline members, in two rooms at Copperline's main office. Imani Clarke moderated 4 sessions, I moderated 6.

## At a Glance

> [!success]
> The redesigned transfers work: SUS 76 against the discovery baseline of 58, and 9 of 10 participants completed a transfer between their own accounts unaided, against 5 of 12 on the old site. Bill pay payee search failed for 3 of 10 and is being reworked.

## Setup

- Plan and script: [[copperline-prototype-test-plan]]. Same transfer task wording as the 2025 baseline so the results compare ([[copperline-research-report]]).
- 10 participants, P1 to P10, recruited by [[ana-lucia-ferreyra]]: 4 over 60, 2 small-business members, 1 screen reader user, 3 others. All new to the redesign.
- High-fidelity Figma prototype on a phone (6 sessions) and a laptop (4 sessions). Sessions 50 minutes. SUS questionnaire at the end of each session ([[system-usability-scale]]).
- Observers in a second room: Renata Solberg and Gideon Marsh for two sessions, Hollis Dunmore and Priyanka Venkat for most of the day.
- [[imani-clarke]] subcontracted for the day plus analysis ([[imani-clarke-copperline-subcontract]]). We calibrated on one pilot session on 2026-05-19.

## Results

- SUS 76 (mean of 10; range 60 to 92).
- Transfer between own accounts: 9 of 10 completed unaided. The one failure was a laptop participant who looked for the transfer in the account details page, not on the account card.
- Scheduled transfer: 8 of 10.
- Pay a bill to an existing payee: 10 of 10.
- Find and add a payee: 7 of 10. The 3 failures typed the company name; search matched only the payee nickname. All three gave up or picked the wrong payee.
- The screen reader participant completed transfers but the amount field announced the currency twice.

## What we changed straight away

- Account card transfer button kept; added a secondary transfer link on the account details page.
- Fixed the double currency announcement in the component spec.
- Payee search moved to rework ([[how-do-we-fix-payee-search]], [[copperline-payee-search-rework-notes]]).

## Notes

Renata watched P3, a member in her seventies, move money in under a minute and said it was the first time she had seen the project "work". In June the board approved the budget for the change order ([[copperline-bill-pay-change-order-2026-06-24]]).

Full notes, clips and the scoring sheet are in [[copperline-prototype-test-findings]], with recordings on Copperline's drive.
