---
title: "Bounding volume hierarchy"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Bounding_volume_hierarchy"
wikipedia_categories: ["3D computer graphics", "Geometric data structures", "Hierarchy"]
related: ["[[Binary space partitioning]]", "[[Bounding interval hierarchy]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]"]
---

# Bounding volume hierarchy

A bounding volume hierarchy (BVH) is a tree structure on a set of geometric objects. All geometric objects, which form the leaf nodes of the tree, are wrapped in bounding volumes. These nodes are then grouped as small sets and enclosed within larger bounding volumes. These, in turn, are also grouped and enclosed within other larger bounding volumes in a recursive fashion, eventually resulting in a tree structure with a single bounding volume at the top of the tree. Bounding volume hierarchies are used to support several operations on sets of geometric objects efficiently, such as in collision detection and ray tracing.
Although wrapping objects in bounding volumes and performing collision tests on them before testing the object geometry itself simplifies the tests and can result in significant performance improvements, the same number of pairwise tests between bounding volumes are still being performed. By arranging the bounding volumes into a bounding volume hierarchy, the time complexity (the number of tests performed) can be reduced to logarithmic in the number of objects. With such a hierarchy in place, during collision testing, child volumes do not have to be examined if their parent volumes are not intersected (for example, if the bounding volumes of two bumper cars do not intersect, the bounding volumes of the bumpers themselves need not be checked for collision).

## Related

- [[Binary space partitioning]]
- [[Bounding interval hierarchy]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bounding_volume_hierarchy