# Plastic Guy

A rubbery cartoon figure you can pull, press and pinch in the browser. Open `index.html`; there is no build step.

How it works:

- Rendering: three.js (loaded from a CDN) with flat toon shading, an ink outline and a face drawn in the shader, so nothing smears when the figure stretches.
- Body: a tetrahedral position-based soft body with plastic flow, volume preservation, gravity and floor friction. A smooth skin mesh is bound to the tetrahedra and relaxed every frame.
- A Create mode (laying down extra pieces of clay) exists in the code but is hidden for now.
