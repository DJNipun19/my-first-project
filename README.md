# Smart Escape

Interactive evacuation route simulator (AI DevFest practice challenge). Educational simulation only.

- **Name / Registration no.:** <your name> / <registration-number>
- **Live link:** <your https deployment URL>

## Run
Open `index.html` in Chrome (no build, no backend). Click **Load sample** or import a `building.json`.

## Implemented
- JSON import + validation (clear errors), SVG map at supplied coordinates, node types, edge costs
- Dijkstra routing by summed cost; ties: smallest exit ID, then smallest node-ID sequence
- Block/unblock rooms, junctions, corridors; close/reopen exits; live recalculation; Reset to file's `initial_state`
- "No route available" / "Starting location blocked"
- English / Bangla toggle; subtle animations (reduced-motion respected)

## Bonus
Keyboard-accessible nodes, high-contrast patterns for hazard states.

## Known issues
<list any>

## AI tools & most useful prompt
<tool name> — <paste your best prompt>

## Screenshots
See `screenshots/` (baseline route, rerouting after C2 blocked).
