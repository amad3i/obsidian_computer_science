---
title: "Graph embedding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_embedding"
wikipedia_categories: ["Graph algorithms", "Topological graph theory"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]", "[[Blossom algorithm]]"]
---

# Graph embedding

In topological graph theory, an embedding (also spelled imbedding) of a graph 
  
    
      
        G
      
    
    
  
 on a surface 
  
    
      
        Σ
      
    
    
  
 is a representation of 
  
    
      
        G
      
    
    
  
 on 
  
    
      
        Σ
      
    
    
  
 in which points of 
  
    
      
        Σ
      
    
    
  
 are associated with vertices and simple arcs (homeomorphic images of 
  
    
      
        0
        ,
        1
      
    
    
  
) are associated with edges in such a way that:

the endpoints of the arc associated with an edge 
  
    
      
        e
      
    
    
  
 are the points associated with the end vertices of 
  
    
      
        e
        ,
      
    
    
  

no arcs include points associated with other vertices,
two arcs never intersect at a point which is interior to either of the arcs.
Here a surface is a connected 
  
    
      
        2
      
    
    
  
-manifold.
Informally, an embedding of a graph into a surface is a drawing of the graph on the surface in such a way that its edges may intersect only at their endpoints. It is well known that any finite graph can be embedded in 3-dimensional Euclidean space 
  
    
      
        
          
            R
          
          
            3
          
        
      
    
    
  
. A planar graph is one that can be embedded in 2-dimensional Euclidean space 
  
    
      
        
          
            R
          
          
            2
          
        
        .
      
    
    
  

Often, an embedding is regarded as an equivalence class (under homeomorphisms of 
  
    
      
        Σ
      
    
    
  
) of representations of the kind just described.
Some authors define a weaker version of the definition of "graph embedding" by omitting the non-intersection condition for edges. In such contexts the stricter definition is described as "non-crossing graph embedding".
This article deals only with the strict definition of graph embedding. The weaker definition is discussed in the articles  "graph drawing" and "crossing number".

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]
- [[Bidirectional search]]
- [[Blossom algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_embedding