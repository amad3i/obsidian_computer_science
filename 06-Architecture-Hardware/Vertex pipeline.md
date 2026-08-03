---
title: "Vertex pipeline"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Vertex_pipeline"
wikipedia_categories: ["3D computer graphics", "Graphics standards"]
related: ["[[OpenFlight]]", "[[Web3D]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]"]
---

# Vertex pipeline

The function of the vertex pipeline in any GPU is to take geometry data (usually supplied as vector points), work with it if needed with either fixed function processes (earlier DirectX), or a vertex shader program (later DirectX), and create all of the 3D data points in a scene to a 2D plane for display on a computer monitor. 
It is possible to eliminate unneeded data from going through the rendering pipeline to cut out extraneous work (called view volume clipping and backface culling). After the vertex engine is done working with the geometry, all the 2D calculated data is sent to the pixel engine for further processing such as texturing and fragment shading.
As of DirectX 9c, the vertex processor is able to do the following by programming the vertex processing under the Direct X API:

Displacement mapping
Geometry blending
Higher-order primitives
Point sprites
Matrix stacks

## Related

- [[OpenFlight]]
- [[Web3D]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vertex_pipeline