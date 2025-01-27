---
type: Procedure
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[design-handoff]]"
  - "[[hollis-dunmore]]"
  - "[[callum-reyes]]"
_organized: true
---

# Hand Off Designs To Developers

My checklist for handing a design phase to a client's developers. Written after the Crumbhollow handoff needed a second round of fixes; refined with Callum Reyes at Ledgerleaf and Hollis Dunmore at Copperline. Background in [[design-handoff]].

## Before handoff day

1. Developers have attended at least one design review of the flow.
2. Every frame marked final or open; open ones listed with an owner and a date.
3. Edge cases drawn and annotated in the file: empty, loading, error, long names and amounts, zero results, permissions, timeouts.
4. Components and tokens used are from the published library; no detached instances.
5. Accessibility notes per screen: focus order, labels and announcements, target sizes, contrast pairs used.
6. Copy final and approved by the client, including error messages.

## On the day

7. Walkthrough with developers, 60 to 90 minutes, recorded.
8. Agree how questions come in (Figma comments, one channel) and the response time.
9. Short written summary: what is handed off, what is open, what support is included and until when.

## After

10. Answer questions within the agreed support window. Log hours; anything beyond the window is a [[change-order]].
11. Review the first staging build against the design and file differences as comments, ranked.
12. Final invoice on handoff, not on launch.

## Guardrails

Never hand off from my own Figma account; files live in the client's workspace ([[copperline-figma-workspace]]).
