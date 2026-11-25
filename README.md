# Plastic Guy

A clay toy for the browser. Open `index.html`; there is no build step.

- **Toy**: a clay figure you can pull, press and pinch.
- **Create**: a blank board. Drag to lay down ropes and balls of white, grey or black clay; pieces stick where they touch and can be reshaped with the same tools.

How it works:

- Rendering: three.js (loaded from a CDN).
- Clay: a tetrahedral position-based soft body with plastic flow, volume preservation, gravity, collisions between pieces, and breakable welds where clay touches clay. Each piece has a smooth skin mesh bound to its tetrahedra.
