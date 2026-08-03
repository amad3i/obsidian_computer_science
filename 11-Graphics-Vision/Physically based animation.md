---
title: "Physically based animation"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Physically_based_animation"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Physically based animation

Physically based animation is an area of interest within computer graphics concerned with the simulation of physically plausible behaviors at interactive rates. Advances in physically based animation are often motivated by the need to include complex, physically inspired behaviors in video games, interactive simulations, and movies. Although off-line simulation methods exist to solve most all of the problems studied in physically-based animation, these methods are intended for applications that necessitate physical accuracy and slow, detailed computations. In contrast to methods common in offline simulation, techniques in physically based animation are concerned with physical plausibility, numerical stability, and visual appeal over physical accuracy. Physically based animation is often limited to loose approximations of physical behaviors because of the strict time constraints imposed by interactive applications. The target frame rate for interactive applications such as games and simulations is often 25-60 hertz, with only a small fraction of the time allotted to an individual frame remaining for physical simulation. Simplified models of physical behaviors are generally preferred if they are more efficient, easier to accelerate (through pre-computation, clever data structures, or SIMD/GPGPU), or satisfy desirable mathematical properties (such as unconditional stability or volume conservation when a soft body undergoes deformation). Fine details are not important when the overriding goal of a visualization is aesthetic appeal or the maintenance of player immersion since these details are often difficult for humans to notice or are otherwise impossible to distinguish at human scales.

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

- Wikipedia: https://en.wikipedia.org/wiki/Physically_based_animation