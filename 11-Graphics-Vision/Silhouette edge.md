---
title: "Silhouette edge"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Silhouette_edge"
wikipedia_categories: ["3D computer graphics"]
related: ["[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[Adobe Fuse CC]]", "[[Binary space partitioning]]"]
---

# Silhouette edge

In computer graphics, a silhouette edge of a 3D body projected onto a 2D plane (display plane) is the collection of points whose outwards surface normal is perpendicular to the view vector.
Due to discontinuities in the surface normal, a silhouette edge is also an edge which separates a front facing face from a back facing face.
Without loss of generality, this edge is usually chosen to be the closest one on a face, so that in parallel view this edge corresponds to the same one in a perspective view.
Hence, if there is an edge between a front facing face and a side facing face, and another edge between a side facing face and back facing face, the closer one is chosen.
The easy example is looking at a cube in the direction where the face normal is collinear with the view vector.
The first type of silhouette edge is sometimes troublesome to handle because it does not necessarily correspond to a physical edge in the CAD model.  The reason that this can be an issue is that a programmer might corrupt the original model by introducing the new silhouette edge into the problem.  Also, given that the edge strongly depends upon the orientation of the model and view vector, this can introduce numerical instabilities into the algorithm (such as when a trick like dilution of precision is considered).

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

- Wikipedia: https://en.wikipedia.org/wiki/Silhouette_edge