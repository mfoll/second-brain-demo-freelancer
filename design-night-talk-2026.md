---
type: Project
status: Completed
start: 2026-02-02
end: 2026-03-19
belongs_to: "[[portfolio-and-marketing]]"
related_to:
  - "[[felipe-aranda]]"
  - "[[accessibility]]"
  - "[[color-contrast-for-text]]"
has:
  - "[[design-night-talk-2026-03-19]]"
  - "[[design-night-talk-slides]]"
  - "[[design-night-talk-speaker-notes]]"
  - "[[design-night-feedback-form-2026-03]]"
_organized: true
---

# Design Night Talk 2026

A 25-minute talk, "Two teals: accessible color tokens without a brand fight", given at Design Night at Tidewell on 2026-03-19 to about 60 people. It turned the Copperline palette problem into something I could talk about without naming Copperline.

## Outcome

Talk on accessible color tokens given at Design Night at Tidewell on 2026-03-19, about 60 attendees. Reached.

## Current State

- Completed. Slides and speaker notes kept ([[design-night-talk-slides]], [[design-night-talk-speaker-notes]]); feedback summarised ([[design-night-feedback-form-2026-03]]).
- Two direct results: 11 Lintel Kit sales in the following week (normal is 2 or 3), and one lead, a product manager who later asked for an audit quote that did not go ahead ([[client-pipeline-tracker]]).
- The contrast-checked color pairs I showed became a Lintel Kit V2 feature ([[lintel-kit-v2]]).

## Scope and Boundaries

The talk only. The Copperline palette decision itself belongs to the client project ([[copperline-accessibility-review-2026-02-11]], [[copperline-design-foundations]]). In the talk I called the client "a regional financial client", used my own made-up brand color and never showed Copperline screens. I asked [[priyanka-venkat]] before submitting the abstract anyway; she was fine with it on those terms.

## Working Context

[[felipe-aranda]] asked me on 2026-02-02, after I complained at the January Design Night that every token talk skips accessibility. I said yes the same evening, which is how I always get into talks.

The argument, in four steps:

1. A brand color can pass for interface components and large type and still fail for body text and button labels. The thresholds are 4.5:1 for normal text and 3:1 for large text and non-text components ([[color-contrast-for-text]], [[w3c-understanding-non-text-contrast-docs]]).
2. So a single "primary" token is the bug. Split it into a decorative brand token and a text-safe token.
3. Name tokens by role (text-accent, fill-accent, decoration-accent), not by hue, so that nobody picks "teal-500" for a button label.
4. Expect a brand fight, and bring the compliance person to it. At the real review, the compliance officer settled it, not me.

I rehearsed twice at the circle (2026-02-19 and a dry run at Tidewell on 2026-03-12) and cut it from 34 to 25 minutes. Rosalind's note: lead with the failing button, not with the theory.

What I would change: the live contrast-checker demo took four minutes and half the room could not read the projector. Next time, a screenshot.

## Important Notes

- [[design-night-talk-2026-03-19]]
- [[design-night-feedback-form-2026-03]]
- [[talks-are-worth-the-prep]]
- [[talk-ideas-backlog]]

## Maintenance Log

- 2026-03-26: Feedback form summarised; project closed.
- 2026-03-19: Talk given.
- 2026-03-12: Dry run at Tidewell.
- 2026-02-02: Felipe's invitation accepted.
