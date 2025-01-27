---
type: Procedure
belongs_to: "[[build-design-skills]]"
related_to:
  - "[[system-usability-scale]]"
  - "[[wikipedia-likert-scale]]"
  - "[[small-samples-beat-no-samples]]"
_organized: true
---

# Score A SUS Questionnaire

How I score and report the [[system-usability-scale|System Usability Scale]] after a usability test. Used on Copperline in 2025 and 2026 and on the Lintel docs test.

## Inputs

- One completed ten-item SUS questionnaire per participant, answers 1 (strongly disagree) to 5 (strongly agree), standard item wording.
- The scoring sheet template in my Templates folder, research/sus-scoring.

## Steps

1. Check each form is complete. A form with a missing item is excluded, and the exclusion is reported.
2. Odd items (1, 3, 5, 7, 9): contribution = answer minus 1.
3. Even items (2, 4, 6, 8, 10): contribution = 5 minus answer.
4. Sum the ten contributions (0 to 40) and multiply by 2.5. That is the participant's score (0 to 100).
5. Session score = mean of participants' scores. Also note minimum and maximum.
6. With fewer than 20 participants, add a rough confidence range from the sheet and say it is rough.
7. Report with completion rates for the core tasks and two or three observed problems. Never the number alone.

## Guardrails

- Same item wording and same tasks across rounds, or the comparison is meaningless. Copperline's 58 and 76 compare because the transfer task was kept word for word.
- For client tests, the scoring sheet lives in the client's workspace with the data.
- Do not call the score a percentage.

## Verification

Recalculate one participant by hand. For Copperline's round on 2026-05-21, the mean was 76 with a range of 60 to 92 ([[copperline-usability-test-2026-05-21]]).
