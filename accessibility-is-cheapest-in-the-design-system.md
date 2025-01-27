---
type: Opinion
status: Active
confidence: High
belongs_to: "[[deliver-client-work]]"
related_to:
  - "[[accessibility]]"
  - "[[design-systems]]"
  - "[[copperline-design-foundations]]"
_organized: true
---

# Accessibility Is Cheapest In The Design System

## Stance

Accessibility costs least when it is decided once in tokens and components, and most when it is found screen by screen in an audit after launch.

## Scope

Product work where I build or extend a design system: Copperline, Lintel Kit, any client with more than a handful of screens. It applies less to small audits of vendor products, where the design system is not mine to change.

## Why I Think This

- Copperline: the two-teal decision was one meeting and one token change, and every later component inherited it ([[copperline-accessibility-review-2026-02-11]], [[copperline-token-set]]).
- Thistlewood: the same contrast and labeling problems appeared on nine templates and had to be fixed nine times, some of them only by the vendor ([[thistlewood-fix-list]]).
- Role-named tokens make a later correction a value change, not a rebuild.

## What Would Change My Mind

A project where the system-level fix turned out more expensive than per-screen fixes, for example a client with two screens and a brand system they cannot touch.

## Implications

Contrast-checked pairs and focus styles go into foundations before any flow is designed. Lintel Kit V2 ships them by default ([[lintel-kit-v2]]). In proposals, accessibility is part of the foundations line, never a separate optional item.
