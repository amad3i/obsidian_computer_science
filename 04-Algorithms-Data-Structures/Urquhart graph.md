---
title: "Urquhart graph"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Urquhart_graph"
wikipedia_categories: ["Computational geometry", "Geometric graphs"]
related: ["[[Beta skeleton]]", "[[Rectilinear minimum spanning tree]]", "[[Semi-Yao graph]]", "[[Visibility graph]]", "[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]"]
---

# Urquhart graph

In computational geometry, the Urquhart graph of a set of points in the plane, named after Roderick B. Urquhart, is obtained by removing the longest edge from each triangle in the Delaunay triangulation.
The Urquhart graph was described by Urquhart (1980), who suggested that removing the longest edge from each Delaunay triangle would be a fast way of constructing the relative neighborhood graph (the graph connecting pairs of points 
  
    
      
        p
      
    
    
  
 and 
  
    
      
        q
      
    
    
  
 when there does not exist any third point 
  
    
      
        r
      
    
    
  
 that is closer to both 
  
    
      
        p
      
    
    
  
 and 
  
    
      
        q
      
    
    
  
 than they are to each other). Since Delaunay triangulations can be constructed in time 
  
    
      
        O
        n
         
        n
      
    
    
  
, the same time bound holds for the Urquhart graph as well. Although it was later shown that the Urquhart graph is not exactly the same as the relative neighborhood graph, it can be used as a good approximation to it. The problem of constructing relative neighborhood graphs in 
  
    
      
        O
        n
         
        n
      
    
    
  
 time, left open by the mismatch between the Urquhart graph and the relative neighborhood graph, was solved by Supowit (1983).
Like the relative neighborhood graph, the Urquhart graph of a set of points in general position contains the Euclidean minimum spanning tree of its points, from which it follows that it is a connected graph.

## Related

- [[Beta skeleton]]
- [[Rectilinear minimum spanning tree]]
- [[Semi-Yao graph]]
- [[Visibility graph]]
- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Urquhart_graph