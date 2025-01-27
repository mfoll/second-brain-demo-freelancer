---
type: Procedure
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[accessibility]]"
  - "[[audit-severity-levels]]"
  - "[[an-audit-needs-a-ranked-fix-list]]"
_organized: true
---

# Run An Accessibility Audit

How I run a WCAG 2.2 AA audit of a client's site or flow, as developed at Thistlewood and reused at Tallowmere. Typical size: 8 to 13 days.

## Inputs

- Signed quote with scope (templates or flows), exclusions and the retest listed as separate.
- Test environment access and a contact who can configure it.
- Analytics or support logs if they exist ([[client-kickoff-questionnaire]], question 6).

## Steps

1. **Scope inventory (0.5 day).** List every template or step in scope; agree it with the client in writing.
2. **Automated pass (0.5 day).** Run automated checks on each template. Treat the output as a lead list, never as findings.
3. **Keyboard pass (1 day).** Every task by keyboard only: focus order, visible focus, traps, skip links.
4. **Screen reader pass (1.5 to 3 days).** Scripted tasks with NVDA on Windows and VoiceOver on macOS and iOS. Log what is announced against what should be ([[thistlewood-screen-reader-test-log]]).
5. **Visual pass (0.5 day).** Contrast from the code values ([[color-contrast-for-text]]), 200% and 400% zoom, reflow at 320 px, target sizes ([[wcag-target-size-minimum-docs]]).
6. **Patron or user sessions (1 day).** Two to five people who use assistive technology, recruited by the client, paid by the client, pseudonymous.
7. **Findings.** Each finding: page, criterion, severity ([[audit-severity-levels]]), owner (configuration, client templates or code, vendor only), steps, suggested fix.
8. **Report and fix list (2 days).** One-page board summary, method, findings by area, positive findings; the fix list as a spreadsheet the client can extend.
9. **Readout (half to one day).** Clips with consent, the three worst issues, the owner split.
10. **Retest offer.** Priced at the day rate, valid 12 months ([[should-audits-include-a-retest]]).

## Guardrails

- No participant names or recordings leave the client's storage.
- Never claim full conformance; report what was tested.
- Do not promise to fix; remediation is out of scope ([[should-i-take-on-remediation-after-audits]]).
