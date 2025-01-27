---
type: Concept
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[run-an-accessibility-audit]]"
  - "[[thistlewood-fix-list]]"
  - "[[accessibility]]"
_organized: true
---

# Audit Severity Levels

The four levels I give every finding in an accessibility or usability audit, so a client can sort a long list into a plan.

## The levels

- **Critical.** Blocks a task completely for some users with no workaround on the site. Example: Tallowmere's seat map cannot be operated by keyboard ([[tallowmere-seat-map-findings]]).
- **High.** Task possible but with serious difficulty, or a workaround exists only outside the site (phoning the box office). Example: unlabeled search facets at Thistlewood.
- **Medium.** Causes errors or slows people down; most users recover.
- **Low.** Annoyance or best-practice gap; fix when touching the page anyway.

Severity is about impact on people, not about which WCAG level a criterion has. A Level A failure on a rarely used page can be Medium; a AA failure on checkout can be Critical.

## Paired with who can fix it

Every finding also gets an owner tag: configuration, the client's own code or templates, or vendor only. Severity says how bad; the owner tag says how fast. Together they make the ranked list described in [[an-audit-needs-a-ranked-fix-list]]. I added the owner tag at Thistlewood after Samir Haddadin's first reaction to the draft ([[thistlewood-audit-lessons]]).
