---
title: "Edge loop"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Edge_loop"
wikipedia_categories: ["3D computer graphics", "Computer science stubs"]
related: ["[[Doo–Sabin subdivision surface]]", "[[Surfel]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]"]
---

# Edge loop

An edge loop, in computer graphics, can loosely be defined as a set of connected edges across a surface. (More specifically, the edges can form an edge ring and be one side of a face loop.) Usually, the last edge meets again with the first edge, thus forming a loop. The set or string of edges can, for example, be the outer edges of a flat surface or the edges surrounding a 'hole' in a surface.

In a stricter sense, an edge loop is defined as a set of edges where the loop follows the middle edge in every 'four way junction'. The loop will end when it encounters another type of junction (three or five way, for example). Take an edge on a mesh surface for example, say at one end of the edge it connects with three other edges, making a four way junction. If you follow the middle 'road' each time, you would either end up with a completed loop or the edge loop would end at another type of junction.
Edge loops are especially practical in organic models which need to be animated. In organic modeling, edge loops play a vital role in proper deformation of the mesh. A properly modeled mesh  will take into careful consideration the placement and termination of these edge loops. Generally, edge loops follow the structure and contour of the muscles that they mimic. For example, in modeling a human face, edge loops should follow the orbicularis oculi muscle around the eyes and the orbicularis oris muscle around the mouth. The hope is that by mimicking the way the muscles are formed, they also aid in the way the muscles are deformed by way of contractions and expansions. An edge loop closely mimics how real muscles work, and if built correctly, provides control over contour and silhouette in any position.
"Edge loop" was first coined as a modelling term in 1999 by 3D artist Bay Raitt, in an article called Digital sculpting techniques for 3D Design magazine.

## Related

- [[Doo–Sabin subdivision surface]]
- [[Surfel]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Edge_loop