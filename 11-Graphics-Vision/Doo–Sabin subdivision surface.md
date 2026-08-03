---
title: "Doo–Sabin subdivision surface"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Doo–Sabin_subdivision_surface"
wikipedia_categories: ["3D computer graphics", "Computer science stubs", "Multivariate interpolation"]
related: ["[[Catmull–Clark subdivision surface]]", "[[Edge loop]]", "[[Loop subdivision surface]]", "[[Non-uniform rational B-spline]]", "[[Subdivision surface]]", "[[Surfel]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]"]
---

# Doo–Sabin subdivision surface

In 3D computer graphics, a Doo–Sabin subdivision surface is a type of subdivision surface based on a generalization of bi-quadratic uniform B-splines, whereas Catmull-Clark was based on generalized bi-cubic uniform B-splines. The subdivision refinement algorithm was developed in 1978 by Daniel Doo and Malcolm Sabin.
The Doo-Sabin process generates one new face at each original vertex, ⁠
  
    
      
        n
      
    
    
  
⁠ new faces along each original edge, and ⁠
  
    
      
        
          n
          
            2
          
        
      
    
    
  
⁠ new faces at each original face. A primary characteristic of the Doo–Sabin subdivision method is the creation of four faces and four edges (valence 4) around every new vertex in the refined mesh. A drawback is that the faces created at the original vertices  may be triangles or n-gons that are not necessarily coplanar.

## Related

- [[Catmull–Clark subdivision surface]]
- [[Edge loop]]
- [[Loop subdivision surface]]
- [[Non-uniform rational B-spline]]
- [[Subdivision surface]]
- [[Surfel]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Doo–Sabin_subdivision_surface