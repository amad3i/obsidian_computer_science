---
title: "Convex layers"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Convex_layers"
wikipedia_categories: ["Computational geometry", "Convex hulls", "Robust statistics"]
related: ["[[Alpha shape]]", "[[Convex hull]]", "[[Potato peeling]]", "[[Simplicial depth]]", "[[3SUM]]", "[[Algorithmic Geometry]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]"]
---

# Convex layers

In computational geometry, the convex layers of a set of points in the Euclidean plane are a sequence of nested convex polygons having the points as their vertices. The outermost one is the convex hull of the points and the rest are formed in the same way recursively. The innermost layer may be degenerate, consisting only of one or two points.
The problem of constructing convex layers has also been called onion peeling or onion decomposition.
Although constructing the convex layers by repeatedly finding convex hulls would be slower, it is possible to partition any set of 
  
    
      
        n
      
    
    
  
 points into its convex layers in time 
  
    
      
        O
        n
         
        n
      
    
    
  
.
Furthermore, the first 
  
    
      
        k
      
    
    
  
 convex layers can be computed in  output-sensitive time 
  
    
      
        O
        n
         
        
          H
          
            k
          
        
      
    
    
  
 where 
  
    
      
        
          H
          
            k
          
        
      
    
    
  
 denotes the number of points on the first 
  
    
      
        k
      
    
    
  
 convex layers.
An early application of the convex layers was in robust statistics, as a way of identifying outliers and measuring the central tendency of a set of sample points. In this context, the number of convex layers surrounding a given point is called its convex hull peeling depth, and the convex layers themselves are the depth contours for this notion of data depth.
Convex layers may be used as part of an efficient range reporting data structure for listing all of the points in a query half-plane. The points in the half-plane from each successive layer may be found by a binary search to find the most extreme point in the direction of the half-plane, and then searching sequentially from there. Fractional cascading can be used to speed up the binary searches, giving total query time 
  
    
      
        O
        log
         
        n
        k
      
    
    
  
 to find 
  
    
      
        k
      
    
    
  
 points out of a set of 
  
    
      
        n
      
    
    
  
.
The points of an 
  
    
      
        n
        n
      
    
    
  
 grid have 
  
    
      
        Θ
        
          n
          
            4
            
              /
            
            3
          
        
      
    
    
  
 convex layers, as do the same number of uniformly random points within any convex shape.

## Related

- [[Alpha shape]]
- [[Convex hull]]
- [[Potato peeling]]
- [[Simplicial depth]]
- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Badouel intersection algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Convex_layers