---
type: Concept
belongs_to: "[[accessibility-deep-dive-2025]]"
related_to:
  - "[[accessibility]]"
  - "[[screen-reader-commands-cheat-sheet]]"
  - "[[wikipedia-screen-reader]]"
_organized: true
---

# Screen Reader Testing

Checking a page or flow by using it with a screen reader, as a blind user would, rather than only reading the code or running an automated checker. Part of every audit since 2025.

## My routine

1. Navigate by headings, then by landmarks. Does the outline make sense alone?
2. Tab through every interactive element. Does each announce a name, role and state?
3. Do each core task end to end, without looking at the screen for the second pass.
4. After every action, listen: was the result announced? (Added after the [[sablewing-final-assessment-2025-08-22|Sablewing final]], where I missed three dynamic issues.)
5. Repeat on a phone screen reader for anything mobile.

## Limits

- I am a sighted user with a screen reader, not a screen reader user. I am slower and I miss what experienced users would route around. On Copperline and Tallowmere at least one participant or tester is a daily screen reader user.
- Automated checkers find perhaps a third of what this routine finds, on my audits so far.

Commands: [[screen-reader-commands-cheat-sheet]]. Background: [[wikipedia-screen-reader]].
