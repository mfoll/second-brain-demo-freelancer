---
type: Source
source_type: Internal document
date_accessed: 2026-10-21
belongs_to: "[[tallowmere-ticketing-audit]]"
related_to:
  - "[[wcag-target-size-minimum-docs]]"
  - "[[wcag-timing-adjustable-docs]]"
  - "[[teo-barros]]"
_organized: true
---

# Tallowmere Seat Map Findings

Draft findings on Tallowmere's seat selection, as of 2026-10-21. Will go into the report on 2026-10-30.

## Key Details

- **Critical.** The seat map is a canvas with no keyboard or screen reader access. There is no list alternative. A blind patron cannot choose a seat at all.
- **Critical.** Companion seats and wheelchair spaces cannot be booked online; the seat map shows them as unavailable. Teo Barros's logs: 23% of companion seat bookings and most wheelchair space bookings went by phone last season.
- **High.** Seats are 16 by 16 pixels with 2 pixels between them at default zoom on a phone, well under 24 pixels with no spacing exception ([[wcag-target-size-minimum-docs]]).
- **High.** The 8-minute seat hold ends with no warning and no way to extend; the basket empties ([[wcag-timing-adjustable-docs]]).
- **Medium.** Available and selected seats differ only in a light and dark gray at 2.1:1 ([[wcag-non-text-contrast-docs]]).
- Patron session P2, a wheelchair user, needed 11 minutes and a phone call to book two seats.

## Why It Matters

The likely recommendation: a "best available" and list-based seat picker alongside the map, which the vendor already supports but Tallowmere never switched on. A configuration fix, which a nonprofit can afford.

## Source Location

Clients / Tallowmere / Working / findings-draft.
