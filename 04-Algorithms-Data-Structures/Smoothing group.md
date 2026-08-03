---
title: "Smoothing group"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Smoothing_group"
wikipedia_categories: ["3D computer graphics", "Computer graphics data structures"]
related: ["[[Nonobtuse mesh]]", "[[Polygon mesh]]", "[[Polygon soup]]", "[[Triangle mesh]]", "[[Viewport]]", "[[Volumetric mesh]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]"]
---

# Smoothing group

In 3D computer graphics, a smoothing group is a group of polygons in a polygon mesh which should appear to form a smooth surface.  Smoothing groups are useful for describing shapes where some polygons are connected smoothly to their neighbors, and some are not.  For example, in a mesh representing a cylinder, all of the polygons are smoothly connected except along the edges of the end caps.  One could make a smoothing group containing all of the polygons in one end cap, another containing the polygons in the other end cap, and a last group containing the polygons in the tube shape between the end caps.
By identifying the polygons in a mesh that should appear to be smoothly connected, smoothing groups allow 3D modeling software to estimate the surface normal at any point on the mesh, by averaging the surface normals or vertex normals in the mesh data that describes the mesh.  The software can use this data to determine how light interacts with the model.  If each polygon lies in a plane, the software could calculate a polygon's surface normal by calculating the normal of the polygon's plane, meaning this data would not have to be stored in the mesh.  Thus, early 3D modeling software like 3D Studio Max DOS used smoothing groups as a way to avoid having to store accurate vertex normals for each vertex of the mesh, as a strategy for computer representation of surfaces.

## Related

- [[Nonobtuse mesh]]
- [[Polygon mesh]]
- [[Polygon soup]]
- [[Triangle mesh]]
- [[Viewport]]
- [[Volumetric mesh]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Smoothing_group