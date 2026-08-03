---
title: "Yao graph"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Yao_graph"
wikipedia_categories: ["Computational geometry", "Geometric graph theory"]
related: ["[[Theta graph]]", "[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]", "[[Barrier resilience]]", "[[Bentley–Ottmann algorithm]]"]
---

# Yao graph

In computational geometry, the Yao graph, named after Andrew Yao, is a kind of geometric spanner, a weighted undirected graph connecting a set of geometric points with the property that, for every pair of points in the graph, their shortest path has a length that is within a constant factor of their Euclidean distance.
The basic idea underlying the two-dimensional Yao graph is to surround each of the given points by equally spaced rays, partitioning the plane into sectors with equal angles, and to connect each point to its nearest neighbor in each of these sectors. Associated with a Yao graph is an integer parameter k ≥ 6 which is the number of rays and sectors described above; larger values of k produce closer approximations to the Euclidean distance. The stretch factor is at most 
  
    
      
        1
        
          /
        
        cos
         
        θ
        sin
         
        θ
      
    
    
  
, where 
  
    
      
        θ
      
    
    
  
 is the angle of the sectors. The same idea can be extended to point sets in more than two dimensions, but the number of sectors required grows exponentially with the dimension.
Andrew Yao used these graphs to construct high-dimensional Euclidean minimum spanning trees.

## Related

- [[Theta graph]]
- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Badouel intersection algorithm]]
- [[Barrier resilience]]
- [[Bentley–Ottmann algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Yao_graph