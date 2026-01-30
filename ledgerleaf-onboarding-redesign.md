---
type: Project
status: Completed
start: 2026-01-12
end: 2026-03-27
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[wen-zhao]]"
  - "[[nadia-ferro]]"
  - "[[value-based-pricing]]"
has:
  - "[[ledgerleaf-proposal-2025-12]]"
  - "[[ledgerleaf-trial-funnel-metrics]]"
  - "[[ledgerleaf-onboarding-retrospective]]"
_organized: true
---

# Ledgerleaf Onboarding Redesign

Redesign of the free trial onboarding for Ledgerleaf, a small bookkeeping SaaS for sole traders. The goal was simple to state: more trial users send their first invoice. My first engagement sold on a value-based proposal with three options.

## Outcome

New trial onboarding shipped; trial-to-first-invoice rate rose from 31% to 44% by June 2026; fee $24,000. Shipped on 2026-03-27 ([[ledgerleaf-launch-2026-03-27]]).

## Current State

- Completed. Fee $24,000 (middle option), 50% deposit of $12,000 paid in December 2025, balance in March 2026.
- Trial-to-first-invoice rate 31% before, 44% in June 2026 over a full month of new trials ([[ledgerleaf-trial-funnel-metrics]]). Wen Zhao has approved a short case study; this is the portfolio's strongest evidence today.

## Scope and Boundaries

Signup to first invoice sent: account setup, business details, first client, first invoice. Not the bank feed connection, which [[callum-reyes]] said was too fragile to touch in this release.

## Working Context

Lead came from [[nadia-ferro]] in the Solo Studio Circle on 2025-11-06 ([[nadia-ferro-ledgerleaf-referral-2025-11-06]]); she had worked with Wen before and was booked until April ([[ledgerleaf-intro-call-2025-11-12]]). The proposal ([[ledgerleaf-proposal-2025-12]]) had three options: $14,000 for a heuristic review and redesign of the first screens, $24,000 for research plus redesign of the whole path, $36,000 adding an in-app checklist and email sequence. Wen picked the middle one, as most clients do ([[value-based-pricing]]).

I interviewed 8 recent trial users ([[ledgerleaf-onboarding-interview-notes]]). The key finding: people stalled at "add your business details" because it asked for a tax ID before they had seen the product. We moved it to the point of sending the first invoice and let them create a draft invoice in the first minute. [[ifeoma-nwosu]] gave me support ticket themes that confirmed it.

Callum built it in three sprints; I paired with him on the empty states. Retrospective: [[ledgerleaf-onboarding-retrospective]].

## Important Notes

- [[ledgerleaf-trial-funnel-metrics]]
- [[ledgerleaf-onboarding-retrospective]]
- [[pricing-decision-2025-11-20]]
- [[client-pipeline-tracker]]

## Maintenance Log

- 2026-06-30: Wen shared June numbers: 44%.
- 2026-03-27: Shipped to all new trials.
- 2026-01-12: Kickoff after deposit.
- 2025-12-08: Proposal accepted, middle option.
