---
title: "Retained mode"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Retained_mode"
wikipedia_categories: ["3D computer graphics", "Computer graphics"]
related: ["[[3D computer graphics]]", "[[Fiducial marker]]", "[[Function representation]]", "[[Joint constraints]]", "[[Kinematic chain]]", "[[Per-pixel lighting]]", "[[Rasterisation]]", "[[Ray tracing (graphics)]]", "[[Reflection (computer graphics)]]", "[[Screen space directional occlusion]]"]
---

# Retained mode

Retained mode in computer graphics is a major pattern of API design in graphics libraries, in which

the graphics library, instead of the client, retains the scene (complete object model of the rendering primitives) to be rendered and
the client calls into the graphics library do not directly cause actual rendering, but make use of extensive indirection to resources, managed –  thus retained –  by the graphics library. It does not preclude the use of double-buffering.
Immediate mode is an alternative approach. Historically, retained mode has been the dominant style in GUI libraries; however, both can coexist in the same library and are not necessarily exclusionary in practice.

## Related

- [[3D computer graphics]]
- [[Fiducial marker]]
- [[Function representation]]
- [[Joint constraints]]
- [[Kinematic chain]]
- [[Per-pixel lighting]]
- [[Rasterisation]]
- [[Ray tracing (graphics)]]
- [[Reflection (computer graphics)]]
- [[Screen space directional occlusion]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Retained_mode