---
title: "Euler operator (digital geometry)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Euler_operator_(digital_geometry)"
wikipedia_categories: ["3D computer graphics", "Digital geometry"]
related: ["[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[Adobe Fuse CC]]", "[[Binary image]]"]
---

# Euler operator (digital geometry)

In solid modeling and computer-aided design, the Euler operators modify the graph of connections to add or remove details of a mesh while preserving its topology.  They are named by Baumgart  after the Euler–Poincaré characteristic.  He chose a set of operators sufficient to create useful meshes, some lose information and so are not invertible.
The boundary representation for a solid object, its surface, is a polygon mesh of vertices, edges and faces. Its topology is captured by the graph of the connections between faces. A given mesh may actually contain multiple unconnected shells (or bodies); each body may be partitioned into multiple connected components each defined by their edge loop boundary. To represent a hollow object, the inside and outside surfaces are separate shells.
Let the number of vertices be V, edges be E, faces be F, components H, shells S, and let the genus be G (S and G correspond to the b0 and b2 Betti numbers respectively). Then, to denote a meaningful geometric object, the mesh must satisfy the generalized Euler–Poincaré formula

 V – E + F = H + 2 * (S – G)

The Euler operators preserve this characteristic. The Eastman paper lists the following basic operators, and their effects on the various terms:

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
- [[Binary image]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Euler_operator_(digital_geometry)