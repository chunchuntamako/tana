# TANABECKHAM — Character-first rebuild

## Approved visual reference (2026-10-10)
- Realistic likeness based on user's stadium portrait: short dark hair, black rectangular glasses, mature face.
- Blue Japan-inspired #10 shirt, white shorts, blue socks.
- Approved concept sheet: front, rear, side, portrait and football actions.
- IMPORTANT: concept sheet is a 2D rendered image, **not** a game-ready 3D model.

## Quality gate
Do not claim the game is upgraded until the real asset loads and is visible in Safari.
Do not replace the approved design with primitive spheres/cylinders and call it photorealistic.

## Build pipeline
1. Produce an original, riggable character mesh in GLB/GLTF with face, hair, glasses, shirt/shorts/socks/shoes and UV textures; optimize for iPhone.
2. Review an interactive 360-degree viewer with zoom and side-by-side reference.
3. Rig and test idle, run, dribble, pass, shoot and turning animations.
4. Integrate in the current Three.js game using GLTFLoader and AnimationMixer.
5. Improve lighting, stadium and camera only after character passes visual review.
6. Test Safari landscape and portrait and confirm GitHub Pages deployment.

## Current state
The published index.html is a primitive-based playable prototype, NOT the approved character.
Do not suggest it is the final visual quality.

## Asset rights
Use original character artwork and licensed third-party animation/models only; avoid reusing eFootball or other proprietary game assets.
