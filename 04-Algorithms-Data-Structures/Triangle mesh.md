---
title: "Triangle mesh"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Triangle_mesh"
wikipedia_categories: ["3D computer graphics", "Computer graphics data structures", "Computer graphics stubs", "Geometry processing", "Mesh generation", "Triangulation (geometry)"]
related: ["[[Polygon mesh]]", "[[Mesh generation]]", "[[Nonobtuse mesh]]", "[[Polygon soup]]", "[[Volumetric mesh]]", "[[Geometry Engine]]", "[[Geometry instancing]]", "[[Geometry processing]]", "[[Image plane]]", "[[Image-based meshing]]"]
---

# Triangle mesh

In computer graphics, a triangle mesh is a type of polygon mesh.  It comprises a set of triangles (typically in three dimensions) that are connected by their common edges or vertices.
Many graphics software packages and hardware devices can operate more efficiently on triangles that are grouped into meshes than on a similar number of triangles that are presented individually. This is typically because computer graphics do operations on the vertices at the corners of triangles.  With individual triangles, the system has to operate on three vertices for every triangle.  In a large mesh, there could be eight or more triangles meeting at a single vertex - by processing those vertices just once, it is possible to do a fraction of the work and achieve an identical effect.
In many computer graphics applications it is necessary to manage a mesh of triangles. The mesh components are vertices, edges, and triangles. An application might require knowledge of the various connections between the mesh components. These connections can be managed independently of the actual vertex positions. This document describes a simple data structure that is convenient for managing the connections. This is not the only possible data structure. Many other types exist and have support for various queries about meshes.

## Related

- [[Polygon mesh]]
- [[Mesh generation]]
- [[Nonobtuse mesh]]
- [[Polygon soup]]
- [[Volumetric mesh]]
- [[Geometry Engine]]
- [[Geometry instancing]]
- [[Geometry processing]]
- [[Image plane]]
- [[Image-based meshing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Triangle_mesh