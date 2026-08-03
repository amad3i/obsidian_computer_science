---
title: "Euler filter"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Euler_filter"
wikipedia_categories: ["Computer animation", "Geometry stubs"]
related: ["[[A Glitch Is a Glitch]]", "[[Adam Powers, The Juggler]]", "[[Animusic]]", "[[Avar (animation variable)]]", "[[Ayotle]]", "[[Cel shading]]", "[[Centro Digital Pictures]]", "[[Character Technical Director]]", "[[Color cycling]]", "[[Computer animation]]"]
---

# Euler filter

In computer graphics, an Euler filter is a filter intended to prevent gimbal lock and related discontinuities in animation data sets in which rotation is expressed in terms of Euler angles.
These discontinuities are caused by the existence of many-to-one mappings between the Euler angle parameterization of the set of 3D rotations. This allows the data set to flip between different Euler angle combinations which correspond to a single 3D rotation, which, although remaining continuous in the space of rotation, are discontinuous in the Euler angle parameter space.
The Euler filter chooses on a sample-by-sample basis between the possible Euler angle representations of each 3D rotation in the data set in such a way as to preserve the continuity of the Euler angle time series, without changing the actual 3D rotations.
Euler filtering is available in a number of 3D animation packages.

## Related

- [[A Glitch Is a Glitch]]
- [[Adam Powers, The Juggler]]
- [[Animusic]]
- [[Avar (animation variable)]]
- [[Ayotle]]
- [[Cel shading]]
- [[Centro Digital Pictures]]
- [[Character Technical Director]]
- [[Color cycling]]
- [[Computer animation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Euler_filter