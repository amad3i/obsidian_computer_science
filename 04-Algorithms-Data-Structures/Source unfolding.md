---
title: "Source unfolding"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Source_unfolding"
wikipedia_categories: ["Computational geometry", "Polygons", "Polyhedra"]
related: ["[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Geometric Folding Algorithms]]", "[[Polygon covering]]", "[[Polygon partition]]", "[[Polygonalization]]", "[[Polyhedral terrain]]", "[[Polymake]]", "[[Vertex enumeration problem]]", "[[3SUM]]"]
---

# Source unfolding

In computational geometry, the source unfolding of a convex polyhedron is a net obtained by cutting the polyhedron along the cut locus of a point on the surface of the polyhedron. The cut locus of a point 
  
    
      
        p
      
    
    
  
 consists of all points on the surface that have two or more shortest geodesics to 
  
    
      
        p
      
    
    
  
. For every convex polyhedron, and every choice of the point 
  
    
      
        p
      
    
    
  
 on its surface, cutting the polyhedron on the cut locus will produce a result that can be unfolded into a flat plane, producing the source unfolding. The resulting net may, however, cut across some of the faces of the polyhedron rather than only cutting along its edges.
The source unfolding can also be continuously transformed from the polyhedron to its flat net, keeping flat the parts of the net that do not lie along edges of the polyhedron, as a blooming of the polyhedron. The unfolded shape of the source unfolding is always a star-shaped polygon, with all of its points visible by straight line segments from the image of 
  
    
      
        p
      
    
    
  
; this is in contrast to the star unfolding, a different method for producing nets that does not always produce star-shaped polygons.
An analogous unfolding method can be applied to any higher-dimensional convex polytope, cutting the surface of the polytope into a net that can be unfolded into a flat hyperplane.

## Related

- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Geometric Folding Algorithms]]
- [[Polygon covering]]
- [[Polygon partition]]
- [[Polygonalization]]
- [[Polyhedral terrain]]
- [[Polymake]]
- [[Vertex enumeration problem]]
- [[3SUM]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Source_unfolding