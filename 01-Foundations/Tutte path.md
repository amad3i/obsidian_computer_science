---
title: "Tutte path"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Tutte_path"
wikipedia_categories: ["Graph algorithms", "Graph theory", "Planar graphs"]
related: ["[[Capacitated arc routing problem]]", "[[Centrality]]", "[[FKT algorithm]]", "[[Graph edit distance]]", "[[Graph isomorphism]]", "[[Group centrality]]", "[[Hierarchical closeness]]", "[[Laminar set family]]", "[[Semantic Brand Score]]", "[[Transitive reduction]]"]
---

# Tutte path

In graph theory, a Tutte path is a path 
  
    
      
        P
      
    
    
  
 within a graph 
  
    
      
        G
      
    
    
  
 such that every connected component that remains after removing the vertices of 
  
    
      
        P
      
    
    
  
 from 
  
    
      
        G
      
    
    
  
 is connected back to 
  
    
      
        P
      
    
    
  
 at a limited number of vertices.
The precise definition relies on the following terms:

  
    
      
        P
      
    
    
  
-bridge: For a given path 
  
    
      
        P
      
    
    
  
 in a graph 
  
    
      
        G
      
    
    
  
, a 
  
    
      
        P
      
    
    
  
-bridge is either a single edge not in 
  
    
      
        P
      
    
    
  
 that connects two vertices of 
  
    
      
        P
      
    
    
  
, or it is a connected component of the graph remaining after deleting the vertices of 
  
    
      
        P
      
    
    
  
, along with all the edges that connect this component to 
  
    
      
        P
      
    
    
  
.
Attachment point: The attachment points of a 
  
    
      
        P
      
    
    
  
-bridge are the vertices of the path 
  
    
      
        P
      
    
    
  
 that are connected by an edge to a vertex within the 
  
    
      
        P
      
    
    
  
-bridge.
A Tutte path then is a path 
  
    
      
        P
      
    
    
  
 in 
  
    
      
        G
      
    
    
  
 such that every 
  
    
      
        P
      
    
    
  
-bridge that remains after removing the vertices of 
  
    
      
        P
      
    
    
  
 from 
  
    
      
        G
      
    
    
  
 has at most three points of attachment to the path 
  
    
      
        P
      
    
    
  
. Furthermore, if a 
  
    
      
        P
      
    
    
  
-bridge contains edges from the outer face of the graph (in the context of planar graphs), it is restricted to having at most two attachment points.

## Related

- [[Capacitated arc routing problem]]
- [[Centrality]]
- [[FKT algorithm]]
- [[Graph edit distance]]
- [[Graph isomorphism]]
- [[Group centrality]]
- [[Hierarchical closeness]]
- [[Laminar set family]]
- [[Semantic Brand Score]]
- [[Transitive reduction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tutte_path