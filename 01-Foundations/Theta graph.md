---
title: "Theta graph"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Theta_graph"
wikipedia_categories: ["Computational geometry", "Geometric graph theory"]
related: ["[[Yao graph]]", "[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]", "[[Barrier resilience]]", "[[Bentley–Ottmann algorithm]]"]
---

# Theta graph

In computational geometry, the Theta graph, or 
  
    
      
        Θ
      
    
    
  
-graph, is a type of geometric spanner similar to a Yao graph.  The basic method of construction involves partitioning the space around each vertex into a set of cones, which themselves partition the remaining vertices of the graph. Like Yao Graphs, a 
  
    
      
        Θ
      
    
    
  
-graph contains at most one edge per cone; where they differ is how that edge is selected. Whereas Yao Graphs will select the nearest vertex according to the metric space of the graph, the 
  
    
      
        Θ
      
    
    
  
-graph defines a fixed ray contained within each cone (conventionally the bisector of the cone) and selects the nearest neighbor with respect to orthogonal projections to that ray. The resulting graph exhibits several good spanner properties.

  
    
      
        Θ
      
    
    
  
-graphs were first described by Clarkson in 1987 and independently by Keil in 1988.

## Related

- [[Yao graph]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Theta_graph