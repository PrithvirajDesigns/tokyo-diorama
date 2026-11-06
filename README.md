# Tokyo Street Corner – Interactive Diorama

An interactive isometric diorama of a rainy Tokyo street corner at night, built with
Three.js in a single self-contained `index.html`. Everything is generated in code:
geometry, textures, animation and even the sound. There are no assets to download.

## Features
- Floating slab diorama with an orthographic isometric camera (orbit, zoom, pan)
- A simulated intersection with traffic, traffic lights, pedestrian crossings and an elevated train
- Convenience store with an interior, a tall neon-lit building with a rooftop ad, Tokyo Tower,
  vending machines, parked bikes and a food-stall street (ramen, taiyaki, karaage, udon, takoyaki, yakitori, dango)
- Articulated people, riders on bicycles, and cats that wander and take shelter when it rains
- Five seasons (summer, rain, winter, spring, autumn), each with day and night looks:
  falling rain with ripples, snow that settles on roofs, trees and roads, blossom, autumn leaves, fireflies
- Season- and time-aware ambient sound, synthesised live with the Web Audio API
- Bloom glow, flickering windows and neon, all driven by GPU shaders

## Tech
Three.js r160 (ES modules via import map), WebGL, EffectComposer / UnrealBloom,
custom GLSL shaders, instanced rendering, canvas-generated textures, Web Audio API.

## Run it
Open `index.html` in a modern browser (it loads Three.js from a CDN).
Controls: drag to orbit, scroll or pinch to zoom, keys 1–5 switch season, N toggles day/night.
