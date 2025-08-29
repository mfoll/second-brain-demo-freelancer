---
type: Event
date: 2025-08-22
belongs_to: "[[accessibility-deep-dive-2025]]"
related_to:
  - "[[marisol-vance]]"
  - "[[wcag-audit-checklist]]"
_organized: true
---

# Sablewing Final Assessment 2025-08-22

Final assessment of the Sablewing Academy accessibility course: a timed two-hour audit of a sample checkout site, followed by a written report submitted the same day. Passed.

## What happened

- Sample site: a fictional store's cart, address form and payment step, built by the course with planted barriers.
- I found 23 issues; the answer key had 26. Missed: a focus trap in the address autocomplete, a status message not announced after "apply coupon", and a timeout warning that only appeared visually.
- Report format was mine: one finding per barrier, success criterion, who it blocks, fix, severity.

## Feedback from Marisol Vance

[[marisol-vance|Marisol]] passed the report and wrote two things I took seriously:

- I rated visual contrast issues as critical even when they blocked nothing. A light-gray placeholder is a real failure but not a blocker.
- I rated missing landmarks as minor when they made the page hard to navigate by screen reader. She was right; I had not used landmarks myself in practice.

## What changed

Severity in my [[wcag-audit-checklist]] is now based on which tasks break and for whom, not on which success criterion is involved. All three missed issues were dynamic: things that happen after an action. I added a "do the task, then listen" pass to [[screen-reader-testing]].
