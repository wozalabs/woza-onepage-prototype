# Woza Labs — one-page prototype

Concept prototype for the Woza Labs one-page site.

**Live:** https://wozalabs.github.io/woza-onepage-prototype/

- `index.html`: the page. It has no dependencies or build step.
- `coral.html`: the reef variant. A ray-marched coral reef you move through by scrolling; Export renders stills (deck, A4, square) of the current view or a single coral, on the canvas or transparent.
- `fonts/NeueMontreal-Regular.woff2`: the web font, used under Woza Labs' commercial licence. Don't reuse it outside Woza projects.

Every load picks a random colour palette, checked against WCAG AAA before the first paint.
