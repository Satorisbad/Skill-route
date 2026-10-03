# UI/UX domain

Load for interface design, screenshot recreation, UX review, visual systems, interaction design, and front-end visual implementation. Also load coding when implementation is required.

## Inspect first
Before redesigning, inspect the existing product/interface, hierarchy, interactions, keyboard shortcuts, workflows, real references, assets, design systems, and components. Determine what must be preserved.

## End-to-end human testing
Simulate the complete workflow from start to finish for:
- a beginner,
- a regular user,
- a power user,
- an unusual/edge-case user.

For each, check:
- every click/path makes sense,
- discoverability,
- hierarchy and human scanning,
- cognitive load,
- missing controls,
- redundant/overdone controls,
- accessibility,
- icon-vs-text appropriateness,
- undo/recovery,
- actual workflow completion,
- whether shortcuts fit real human hands.

Shortcuts should be practical and configurable where appropriate.

## Icons and assets
- Never invent icons by default.
- Use real icons from the chosen library; prefer Tabler when applicable.
- If no suitable icon exists, surface that fact before substituting/generating.
- Use real project assets/references where available.
- Verify licensing when bringing in third-party assets.

## Verification
For screenshot/interface recreation:
implement -> render/run -> visually inspect -> compare with reference -> correct alignment/spacing/hierarchy/behavior/details -> rerun/reinspect.

Do not declare a UI correct because its code merely looks plausible.

## Exact technical visuals
Graphs, geometry, and mathematical visuals encoding exact values must use deterministic/proper rendering, not approximate AI imagery.
