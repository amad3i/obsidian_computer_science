---
title: "Contraction hierarchies"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Contraction_hierarchies"
wikipedia_categories: ["Graph algorithms", "Routing algorithms", "Search algorithms"]
related: ["[[A- search algorithm]]", "[[B-]]", "[[Dijkstra's algorithm]]", "[[Iterative deepening A-]]", "[[SMA-]]", "[[Alpha–beta pruning]]", "[[Bidirectional search]]", "[[Breadth-first search]]", "[[D-]]", "[[Depth-first search]]"]
---

# Contraction hierarchies

In computer science, the method of contraction hierarchies is a speed-up technique for finding the shortest path in a graph. The most intuitive applications are car-navigation systems: a user wants to drive from 
  
    
      
        A
      
    
    
  
 to 
  
    
      
        B
      
    
    
  
 using the quickest possible route. The metric optimized here is the travel time. Intersections are represented by vertices, the road sections connecting them by edges. The edge weights represent the time it takes to drive along this segment of the road. A path from 
  
    
      
        A
      
    
    
  
 to 
  
    
      
        B
      
    
    
  
 is a sequence of edges (road sections); the shortest path is the one with the minimal sum of edge weights among all possible paths. The shortest path in a graph can be computed using Dijkstra's algorithm but, given that road networks consist of tens of millions of vertices, this is impractical. Contraction hierarchies is a speed-up method optimized to exploit properties of graphs representing road networks. The speed-up is achieved by creating shortcuts in a preprocessing phase which are then used during a shortest-path query to skip over "unimportant" vertices. This is based on the observation that road networks are highly hierarchical. Some intersections, for example highway junctions, are "more important" and higher up in the hierarchy than for example a junction leading into a dead end. Shortcuts can be used to save the precomputed distance between two important junctions such that the algorithm doesn't have to consider the full path between these junctions at query time. Contraction hierarchies do not know about which roads humans consider "important" (e.g. highways), but they are provided with the graph as input and are able to assign importance to vertices using heuristics.
Contraction hierarchies are not only applied to speed-up algorithms in car-navigation systems but also in web-based route planners, traffic simulation, and logistics optimization. Implementations of the algorithm are publicly available as open source software.

## Related

- [[A- search algorithm]]
- [[B-]]
- [[Dijkstra's algorithm]]
- [[Iterative deepening A-]]
- [[SMA-]]
- [[Alpha–beta pruning]]
- [[Bidirectional search]]
- [[Breadth-first search]]
- [[D-]]
- [[Depth-first search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Contraction_hierarchies