---
title: "Precomputed Radiance Transfer"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Precomputed_Radiance_Transfer"
wikipedia_categories: ["3D computer graphics"]
related: ["[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[Adobe Fuse CC]]", "[[Binary space partitioning]]"]
---

# Precomputed Radiance Transfer

Precomputed Radiance Transfer (PRT) is a computer graphics technique used to render a scene in real time with complex light interactions being precomputed to save time.  Radiosity methods can be used to determine the diffuse lighting of the scene, however PRT offers a method to dynamically change the lighting environment.
In essence, PRT computes the illumination of a point as a linear combination of incident irradiance.  An efficient method must be used to encode this data, such as spherical harmonics.
When spherical harmonics are used to approximate the light transport function, only low-frequency effects can be handled with a reasonable number of parameters.  Ren Ng et al. extended this work to handle higher frequency shadows by replacing spherical harmonics with non-linear wavelets.

## Related

- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[Adobe Fuse CC]]
- [[Binary space partitioning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Precomputed_Radiance_Transfer