---
title: "Nonobtuse mesh"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Nonobtuse_mesh"
wikipedia_categories: ["3D computer graphics", "Computer graphics data structures", "Triangulation (geometry)"]
related: ["[[Triangle mesh]]", "[[Mesh generation]]", "[[Polygon mesh]]", "[[Polygon soup]]", "[[Smoothing group]]", "[[Viewport]]", "[[Volumetric mesh]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]"]
---

# Nonobtuse mesh

In computer graphics, a nonobtuse triangle mesh is a polygon mesh composed of a set of triangles in which no angle is obtuse, i.e. greater than 90°. If each (triangle) face angle is strictly less than 90°, then the triangle mesh is said to be acute. Every polygon with 
  
    
      
        n
      
    
    
  
 sides has a nonobtuse triangulation with 
  
    
      
        O
        n
      
    
    
  
 triangles (expressed in big O notation), allowing some triangle vertices to be added to the sides and interior of the polygon. These nonobtuse triangulations can be further refined to produce acute triangulations with 
  
    
      
        O
        n
      
    
    
  
 triangles.
Nonobtuse meshes avoid certain problems of nonconvergence or of convergence to the wrong numerical solution as demonstrated by the Schwarz lantern. The immediate benefits of a nonobtuse or acute mesh include more efficient and more accurate geodesic computation using fast marching, and guaranteed validity for planar mesh embeddings via discrete harmonic maps.

## Related

- [[Triangle mesh]]
- [[Mesh generation]]
- [[Polygon mesh]]
- [[Polygon soup]]
- [[Smoothing group]]
- [[Viewport]]
- [[Volumetric mesh]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nonobtuse_mesh