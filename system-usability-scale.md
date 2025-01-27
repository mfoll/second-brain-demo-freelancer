---
type: Concept
maturity: Evergreen
belongs_to: "[[build-design-skills]]"
related_to:
  - "[[user-research-methods]]"
  - "[[copperline-usability-test-2026-05-21]]"
  - "[[copperline-research-report]]"
  - "[[wikipedia-system-usability-scale]]"
_organized: true
---

# System Usability Scale

A ten-item questionnaire that gives one usability score from 0 to 100 for a product or prototype, filled in by each participant at the end of a test session. I use it on every usability test now because it gives a client a number they can compare across rounds.

## Definition

> [!info]
> Ten statements, alternating positive and negative, each answered on a five-point scale from strongly disagree to strongly agree. The answers are converted to a single score from 0 to 100. The score is not a percentage, and 68 is roughly the average across many published studies.

The items ask about things like wanting to use the system often, finding it unnecessarily complex, needing a technical person's help, and feeling confident. Odd items are positive, even items negative, so people who tick the same column all the way down show up.

## Scoring

The steps are in [[score-a-sus-questionnaire]]. In short: for odd items subtract 1 from the answer, for even items subtract the answer from 5, add the ten contributions, multiply by 2.5. Average the participants' scores for the session's score.

## How I read the numbers

- Below about 50: people struggle; expect complaints.
- Around 68: average. Nothing to celebrate or panic about.
- Above about 80: people like it and say so.

Copperline is the example I quote. The [[copperline-research-report|discovery baseline]] in October 2025 scored 58 on the current online banking (12 participants), and only 5 of 12 completed a transfer unaided. The [[copperline-usability-test-2026-05-21|prototype test]] on 2026-05-21 scored 76 (10 participants, range 60 to 92), with 9 of 10 completing the transfer. That is a move from below average to clearly above it, on the same task wording.

## Why a small sample still helps

Ten or twelve participants give a wide range around the mean. On Copperline, a rough 90% interval is several points either side of each score, so 58 and 76 do not overlap, but 72 and 76 would not have proved anything. [[imani-clarke|Imani]] made me add that range to the report after the first circle review of it. The point of the number is the direction and size of the change, alongside task completion and what we saw in the sessions, not a precise score. My stance: [[small-samples-beat-no-samples]].

## Limits

- It says how usable something feels, not why. The why comes from watching sessions ([[think-aloud-testing]]).
- It needs the same task set across rounds to compare. Copperline worked because the transfer task wording was kept from 2025 to 2026.
- It is for one session's experience. I did not use it for the [[diary-study]] on Lintel Kit, and on the [[lintel-docs-unmoderated-test-2026-08-24|unmoderated docs test]] it was out of habit and of little use.
- Clients like the number too much. I always report it with completion rates and two or three observed problems; the payee search failure (3 of 10) mattered more than the 76.

## Sources

- [[wikipedia-system-usability-scale]] for the origin and scoring.
- Learned properly in [[research-methods-course-2026]]; first used at Orchard & Vane without really understanding the scoring.
