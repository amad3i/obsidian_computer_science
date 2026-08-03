---
title: "Horizon mapping"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Horizon_mapping"
wikipedia_categories: ["3D computer graphics", "Geographic data and information", "Shading", "Texture mapping", "Virtual reality"]
related: ["[[Ray tracing (graphics)]]", "[[3D city model]]", "[[Bump mapping]]", "[[Draw distance]]", "[[Gouraud shading]]", "[[Inverse kinematics]]", "[[Kinematic chain]]", "[[Normal mapping]]", "[[OpenFlight]]", "[[Particle system]]"]
---

# Horizon mapping

Horizon mapping is a texture mapping technique in 3D computer graphics used to simulate realistic self-shadowing on surfaces with displaced details, such as bump maps or other digital elevation models (DEMs). It achieves this by pre-recording the shape of the surrounding terrain for every point on a surface, allowing the graphics engine to quickly check if a light source is blocked by these features. This results in the illusion of bumps casting shadows on one another, greatly enhancing depth perception without the performance cost of modifying the underlying 3D geometry. Horizon mapping was introduced by Nelson L. Max in 1988.
Modern implementations of horizon mapping are often compressed to save memory and are frequently used for rendering massive, tile-based environments like planetary terrains.

## Related

- [[Ray tracing (graphics)]]
- [[3D city model]]
- [[Bump mapping]]
- [[Draw distance]]
- [[Gouraud shading]]
- [[Inverse kinematics]]
- [[Kinematic chain]]
- [[Normal mapping]]
- [[OpenFlight]]
- [[Particle system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Horizon_mapping