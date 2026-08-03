---
title: "Mesh generation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Mesh_generation"
wikipedia_categories: ["3D computer graphics", "Computational fluid dynamics", "Computer-aided design", "Geometric algorithms", "Mesh generation", "Mesh generation people", "Mesh generators", "Numerical analysis"]
related: ["[[3D Content Retrieval]]", "[[Avizo (software)]]", "[[Bounding volume]]", "[[Class A surface]]", "[[Constructive solid geometry]]", "[[Digital materialization]]", "[[Explicit algebraic stress model]]", "[[Finite volume method]]", "[[Fluid animation]]", "[[Freeform surface modelling]]"]
---

# Mesh generation

Mesh generation is the practice of creating a mesh, a subdivision of a continuous geometric space into discrete geometric and topological cells.
Often these cells form a simplicial complex.
Usually the cells partition the geometric input domain.
Mesh cells are used as discrete local approximations of the larger domain. Meshes are created by computer algorithms, often with human guidance through a GUI, depending on the complexity of the domain and the type of mesh desired.
A typical goal is to create a mesh that accurately captures the input domain geometry, with high-quality (well-shaped) cells, and without so many cells as to make subsequent calculations intractable.
The mesh should also be fine (have small elements) in areas that are important for the subsequent calculations.
Meshes are used for rendering to a computer screen and for physical simulation such as finite element analysis or computational fluid dynamics. Meshes are composed of simple cells like triangles because, e.g., we know how to perform operations such as finite element calculations (engineering) or ray tracing (computer graphics) on triangles, but we do not know how to perform these operations directly on complicated spaces and shapes such as a roadway bridge. We can simulate the strength of the bridge, or draw it on a computer screen, by performing calculations on each triangle and calculating the interactions between triangles.
A major distinction is between structured and unstructured meshing. In structured meshing the mesh is a regular lattice, such as an array, with implied connectivity between elements. In unstructured meshing, elements may be connected to each other in irregular patterns, and more complicated domains can be captured. This page is primarily about unstructured meshes.
While a mesh may be a triangulation, the process of meshing is distinguished from point set triangulation in that meshing includes the freedom to add vertices not present in the input. "Facetting" (triangulating) CAD models for drafting has the same freedom to add vertices, but the goal is to represent the shape accurately using as few triangles as possible and the shape of individual triangles is not important. Computer graphics renderings of textures and realistic lighting conditions use meshes instead.
Many mesh generation software is coupled to a CAD system defining its input, and simulation software for taking its output. The input can vary greatly but common forms are Solid modeling, Geometric modeling, NURBS, B-rep, STL or a point cloud.

## Related

- [[3D Content Retrieval]]
- [[Avizo (software)]]
- [[Bounding volume]]
- [[Class A surface]]
- [[Constructive solid geometry]]
- [[Digital materialization]]
- [[Explicit algebraic stress model]]
- [[Finite volume method]]
- [[Fluid animation]]
- [[Freeform surface modelling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mesh_generation