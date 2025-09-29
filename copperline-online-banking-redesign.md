---
type: Project
status: Active
start: 2025-09-08
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[renata-solberg]]"
  - "[[priyanka-venkat]]"
  - "[[accessibility]]"
has:
  - "[[copperline-transfers-and-bill-pay]]"
  - "[[copperline-statement-of-work]]"
  - "[[copperline-research-report]]"
  - "[[copperline-stakeholder-map]]"
  - "[[copperline-lessons-so-far]]"
_organized: true
---

# Copperline Online Banking Redesign

Umbrella for my work with Copperline Credit Union (about 41,000 members) on a redesigned responsive online banking site. It is the largest engagement I have had since going solo and runs in phases, each with its own child project.

## Outcome

Copperline launches a redesigned responsive online banking site whose core tasks score at least 70 on the [[system-usability-scale]] and meet WCAG 2.2 AA.

## Current State

- Phase 2 is live: [[copperline-transfers-and-bill-pay]] hands off to Hollis Dunmore's developers on 2026-11-27.
- Evidence so far: baseline SUS 58 with 5 of 12 completing a transfer ([[copperline-research-report]]); prototype SUS 76 with 9 of 10 ([[copperline-usability-test-2026-05-21]]). The outcome threshold of 70 is met in testing, not yet in production.
- Payee search in bill pay is the one known failure (3 of 10) and is being reworked ([[how-do-we-fix-payee-search]]).
- Copperline has not approved a case study. Nothing from this engagement goes into the portfolio until Renata Solberg says yes in writing ([[will-copperline-approve-a-case-study]]).
- Fees to date: $18,500 discovery, $9,800 native app concept sprint, $62,000 phase 2, plus the June 2026 [[copperline-bill-pay-change-order-2026-06-24|change order]] for $7,500.

## Scope and Boundaries

Responsive web online banking: sign-in, accounts overview, transfers, bill pay, and the design system behind them. Out of scope: the vendor mobile app (left untouched until 2027 after [[copperline-responsive-first-decision-2026-02-20]]), card management, loans, and anything in the core banking platform itself.

All deliverables, recordings and member data live in Copperline's Figma organisation and shared drive ([[copperline-figma-workspace]]). This vault holds pointers, decisions and numbers I would note anyway, never screens of confidential flows or member data.

## Working Context

Copperline came to me through a former Orchard & Vane client contact who had moved to the credit union's board; there was no pitch, just a discovery proposal. Discovery ran from 2025-09-08 to 2025-11-14 ([[copperline-discovery-research]]) and gave us the baseline numbers. I then ran a short native app concept sprint ([[copperline-native-app-concepts]]) because the board wanted an app story; that was superseded once Hollis showed what the vendor contract allowed.

[[copperline-design-foundations]] produced the token set, components and the two-teal palette, signed off on 2026-04-30 after a real argument with brand ([[copperline-accessibility-review-2026-02-11]]). Transfers and bill pay overlap with the end of foundations by design, so components were tested in real flows.

People: [[renata-solberg]] sponsors; [[priyanka-venkat]] is my day-to-day contact; [[desmond-okafor]] owns brand and still dislikes the text teal; [[gideon-marsh]] in compliance is my best ally on accessibility; [[hollis-dunmore]] leads front end; [[ana-lucia-ferreyra]] recruits members for research. [[imani-clarke]] subcontracted on research ([[imani-clarke-copperline-subcontract]]). See [[copperline-stakeholder-map]].

## Active Workflows

- Weekly status email to Priyanka every Friday ([[copperline-weekly-status-emails]]).
- Fortnightly design review with Priyanka, Hollis and whoever owns the flow under review.
- Monthly milestone invoice under the phase 2 terms, net 30.

## Next Actions

- [ ] Hand off transfers and bill pay by 2026-11-27 using [[hand-off-designs-to-developers]].
- [ ] Retest the reworked payee search before handoff and log the result in [[copperline-prototype-test-findings]].
- [ ] Ask Renata for case-study approval with a draft that uses only the SUS and completion numbers.
- [ ] Decide whether to propose phase 3 ([[should-i-propose-copperline-phase-3]]).

## Open Questions

- [[how-do-we-fix-payee-search]]
- [[will-copperline-approve-a-case-study]]
- [[should-i-propose-copperline-phase-3]]
- [[can-buttons-use-the-brand-teal]]

## Important Notes

- [[copperline-statement-of-work]]
- [[copperline-research-report]]
- [[copperline-design-principles]]
- [[copperline-lessons-so-far]]
- [[color-contrast-for-text]]

## Maintenance Log

- 2026-06-24: Change order signed for bill pay handoff support and the payee search rework.
- 2026-05-21: Prototype test: SUS 76, 9 of 10 transfers.
- 2026-04-30: Design foundations signed off, two-teal palette included.
- 2026-02-20: Native app concepts superseded by responsive web first.
- 2025-12-15: Phase 2 signed at the $62,000 middle option.
