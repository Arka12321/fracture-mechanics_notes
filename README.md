# K-Dominance: Why K Controls the Crack Tip

An interactive, single-file HTML explainer on **K-dominance** in linear elastic fracture mechanics (LEFM) — how the stress intensity factor *K* fully characterizes the crack-tip stress field within an annular "K-dominated zone," even though the governing formula breaks down right at the tip.

Based on Chapter 2 of Lawn's *Fracture of Brittle Solids* (2nd Ed.).

## What's inside

- **Three zones around a crack tip** — nonlinear zone, K-dominated zone, and outer boundary zone, with click-to-expand explanations of why the Irwin formula only holds in the middle annulus.
- **The "funnel" idea** — an SVG diagram showing how all external inputs (crack size, load, geometry) get condensed into the single parameter K before reaching the process zone.
- **Similitude principle** — a side-by-side comparison showing why two very different specimens with matching K values present identical crack-tip conditions.
- **The governing equation** — σᵢⱼ(r, θ) = K / √(2πr) × fᵢⱼ(θ), with annotations.
- **Interactive stress-field visualizer** — a canvas-rendered Mode I stress field around the crack tip; drag the K slider to see the field intensity change while its shape stays fixed.
- **Small-scale yielding condition** — when K-dominance holds vs. breaks down, and why it works especially well for brittle solids.

## Viewing it

To view the notes, click the link below:

**https://arka12321.github.io/fracture-mechanics_notes/**

No installation is needed. The page opens directly in your browser. To run it locally instead, download `index.html` and open it in a browser (an internet connection is needed for the fonts).


## Notes

- Fonts are pulled from Google Fonts (Inter, JetBrains Mono) via CDN — an internet connection is needed for the intended typography, but the page still renders (with fallback fonts) offline.
- All visuals (SVG diagrams, canvas field plot) are generated client-side; nothing is precomputed or fetched from an API.
