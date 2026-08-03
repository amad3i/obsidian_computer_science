---
title: "Simulation noise"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Simulation_noise"
wikipedia_categories: ["Computer graphics", "Noise (electronics)"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Simulation noise

Simulation noise is a function that creates a divergence-free vector field.  This signal can be used in artistic simulations for the purpose of increasing the perception of extra detail.
The function can be calculated in three dimensions by dividing the space into a regular lattice grid.  With each edge is associated a random value, indicating a rotational component of material revolving around the edge. By following rotating material into and out of faces, one can quickly sum the flux passing through each face of the lattice.  Flux values at lattice faces are then interpolated to create a field value for all positions.
Perlin noise is the earliest form of lattice noise, which has become very popular in computer graphics.  Perlin Noise is not suited for simulation because it is not divergence-free.
Noises based on lattices, such as simulation noise and Perlin noise, are often calculated at different frequencies and summed together to form band-limited fractal signals. 
Other approaches developed later that use vector calculus identities to produce divergence free fields, such as "Curl-Noise" as suggested by Rook Bridson, and "Divergence-Free Noise" due to Ivan DeWolf.  These often require calculation of lattice noise gradients, which sometimes are not readily available.  A naive implementation would call a lattice noise function several times to calculate its gradient, resulting in more computation than is strictly necessary.  Unlike these noises, simulation noise has a geometric rationale in addition to its mathematical properties.  It simulates vortices scattered in space, to produce its pleasing aesthetic.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simulation_noise