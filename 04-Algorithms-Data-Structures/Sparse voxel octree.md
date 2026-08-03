---
title: "Sparse voxel octree"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Sparse_voxel_octree"
wikipedia_categories: ["3D computer graphics", "Computing stubs"]
related: ["[[Loop subdivision surface]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[Adobe Fuse CC]]"]
---

# Sparse voxel octree

A sparse voxel octree (SVO) is a hierarchical octree data structure in which voxels recursively subdivide space into octants, storing only occupied or surface-intersecting regions, making it compact for raycasting and sometimes ray tracing in 3D computer graphics rendering.
The technique generally relies on generating and processing the hull of points (sparse voxels) which are visible, or may be visible, given the resolution and size of the screen. There are two main advantages to the technique. The first is that only pixels that will be displayed are computed, with the screen resolution limiting the level of detail required; this limits computational cost during rendering. The second is that interior voxels (those fully enclosed by other voxels) need not be included in the 3D data set; this limits the amount of 3D voxel data (and thus storage space) required for realistic, high-resolution digital models and/or environments.
The basic advantage of octrees is that, as a hierarchical data structure, they need not be explored to their full depth. This means that a system can extract a small subset of voxels as they are needed. In addition, octrees permit smoothing of the underlying data, to help with antialiasing.
It is, however, a generally less well developed technique than standard polygon-based rasterisation schemes. As scenes grow in geometric complexity, SVOs have been proposed to facilitate a transition from traditional triangle-based pipelines to voxel-based rendering.

## Related

- [[Loop subdivision surface]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[Adobe Fuse CC]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sparse_voxel_octree