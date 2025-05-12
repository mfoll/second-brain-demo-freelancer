---
type: Project
status: Completed
start: 2025-05-12
end: 2025-07-11
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[odette-fairweather]]"
  - "[[accessibility]]"
  - "[[accessibility-deep-dive-2025]]"
has:
  - "[[thistlewood-audit-report]]"
  - "[[thistlewood-fix-list]]"
  - "[[thistlewood-audit-readout-2025-07-09]]"
_organized: true
---

# Thistlewood Catalog Audit

WCAG 2.2 AA audit of Thistlewood Libraries' online catalog: search, the record page and the patron account pages. My first full accessibility audit, run halfway through the Sablewing course, and the one that taught me an audit is only as good as its fix list.

## Outcome

WCAG 2.2 AA audit of the library catalog's search, record and account pages, with a prioritised fix list; fixed fee $9,200. Reached on 2025-07-11.

## Current State

- Completed. Report ([[thistlewood-audit-report]]) and fix list ([[thistlewood-fix-list]]) delivered; readout on 2025-07-09 ([[thistlewood-audit-readout-2025-07-09]]).
- Odette Fairweather told me in March 2026 that 19 of the 31 high and critical issues were fixed by their catalog vendor. The rest wait for a vendor upgrade.
- Paid on time, within net 15. The first client on the new [[standard-services-agreement]].

## Scope and Boundaries

Nine templates across three areas, tested with keyboard, NVDA on Windows, VoiceOver on macOS and iOS, 200% and 400% zoom, and automated checks. Not the library's main website, not the e-book lending app (a third-party product). Five patrons who use assistive technology joined short sessions, recruited by [[odette-fairweather]]; they are referred to as P1 to P5.

## Working Context

The catalog is a vendor product ([[wikipedia-online-public-access-catalog]]) configured by [[samir-haddadin]]'s IT team. That shaped the fix list: every issue is tagged as fixable by configuration, by Thistlewood's own templates, or only by the vendor. Without that tag the report would have been a list nobody could act on ([[an-audit-needs-a-ranked-fix-list]]).

Worst findings: search facets were checkboxes without labels; the "place hold" button was an image link; session timeout on the account pages logged patrons out after 10 minutes with no warning ([[wcag-timing-adjustable-docs]]). Screen reader findings are logged in [[thistlewood-screen-reader-test-log]].

Method reused for Tallowmere: [[run-an-accessibility-audit]]. Severity scheme: [[audit-severity-levels]]. Lessons: [[thistlewood-audit-lessons]].

## Important Notes

- [[thistlewood-audit-report]]
- [[thistlewood-fix-list]]
- [[thistlewood-audit-lessons]]
- [[should-audits-include-a-retest]]

## Maintenance Log

- 2026-03-09: Odette reported 19 of 31 high and critical issues fixed.
- 2025-07-11: Closed; final invoice paid.
- 2025-07-09: Readout to Odette, Samir and the head of digital services.
- 2025-05-12: Started.
