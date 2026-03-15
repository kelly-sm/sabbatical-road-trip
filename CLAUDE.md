# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Purpose

Road trip planning repository for a 3-week camper van trip (April 6–26, 2026): Seattle → Oregon Coast → California Coast → Grand Canyon → Utah → Seattle. The repo stores brainstorming context, itineraries, campsite research, and trip notes so planning can continue across multiple sessions.

## Travelers & Vehicle

- Two people (couple)
- Converted Ford Transit van: self-contained with solar, water system, sink, refrigerator, propane stove — no hookups needed, can do dispersed BLM camping
- Style: scenic drives, moderate hikes, beautiful van camping spots with great views
- Budget: flexible, willing to pay for quality campsites and dining
- **Dietary restriction: one traveler has Celiac disease** — strictly gluten-free, not just a preference. Cross-contamination matters.

## Dining Approach for Celiac

When recommending restaurants or food stops:
- **Flag** any bakeries, sandwich shops, pizza places, or pasta-heavy spots that aren't Celiac-safe
- **Prioritize** naturally GF-friendly cuisines: seafood, Mexican (corn tortillas), farm-to-table California cuisine, steak/BBQ
- **Avoid recommending** places famous for bread, sandwiches, or pastries unless they have a credible dedicated GF menu
- **Seafood shacks and oyster bars** along the coast are often ideal — naturally GF, fresh, and local
- Van cooking is a great fallback — having GF staples on board reduces pressure at every stop

## File Structure

```
overview.md           # Master trip summary — route, dates, anchor campsites, planning status
night-by-night.md     # Single-file itinerary: every night in order with drive times and reservation status
reservations.md       # All bookings with confirmation numbers and status
legs/
  01-california-coast.md   # Oregon Coast → Redwoods → SF/Marin → Monterey → Big Sur → LA → Joshua Tree
  02-grand-canyon.md
  03-utah.md
  04-return.md             # Created if needed
```

## night-by-night.md Is the Source of Truth for the Schedule

**Any time a leg file changes in a way that affects dates, campsites, drive times, or nightly stops, `night-by-night.md` must be updated in the same session.** This includes:

- A campsite being swapped for an alternative
- Drive time or routing changed
- A night added, removed, or reordered
- Reservation status updated (e.g., 🔲 → ✅ when a booking is confirmed)

When updating `night-by-night.md`, also check whether `overview.md` or `reservations.md` need corresponding updates.

## Brainstorming Session Approach

When the user starts a session on a specific leg:
1. Read `overview.md` and `night-by-night.md` first for current trip state
2. Read the relevant leg file
3. Build out or update the leg file with: day-by-day plan, campsite options (prioritizing spots with great views or unique character), driving logistics, and highlights — not exhaustive lists
4. Update `night-by-night.md` to reflect any changes to the schedule
5. Flag any new reservations needed and add them to `reservations.md`

When the user asks questions during the trip:
- Read `night-by-night.md` and the relevant leg file before answering
- Prioritize practical, actionable answers (hours, access, conditions)

## Key Trip Facts

- **Dates:** April 6–26, 2026
- **Nights on road:** ~20
- **Utah parks target:** Zion, Bryce Canyon, Moab/Arches area (5 nights total)
- **California must-sees:** Redwoods, San Francisco, Monterey, Big Sur, Los Angeles
- **Campsite reservation platforms:** recreation.gov, reservecalifornia.com, reserveamerica.com, utahstateparks.reserveamerica.com
- **Free camping research tools:** Campendium, iOverlander, FreeCampsites.net
