# Plastic Guy

A clay figure you can pull, press and pinch in the browser. Open `index.html`; there is no build step.

How it works:

- Rendering: three.js (loaded from a CDN), matte clay shading on a white background, fixed camera. The face is drawn in the shader, so nothing smears when the clay stretches.
- Clay: a cage of tetrahedra around the figure, solved with position-based dynamics. Each cell remembers its own rest shape and lets it flow toward the current shape while keeping its volume, which is what makes it model like clay instead of springing back. The clay follows the finger at a limited speed.
- Skin: a smooth mesh carried inside the cage and relaxed every frame.
- A Create mode (laying down extra pieces of clay) exists in the code but is hidden for now.
