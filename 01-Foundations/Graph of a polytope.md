---
title: "Graph of a polytope"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_of_a_polytope"
wikipedia_categories: ["Convex geometry", "Discrete geometry", "Graph families", "Graph theory"]
related: ["[[Forbidden graph characterization]]", "[[Absolutely convex set]]", "[[Albertson index]]", "[[Algorithmic problems on convex sets]]", "[[Antimatroid]]", "[[Aperiodic graph]]", "[[Arrangement (space partition)]]", "[[Arrangement of hyperplanes]]", "[[Asymptotic geometry]]", "[[Bicircular matroid]]"]
---

# Graph of a polytope

In polytope theory, the edge graph (also known as vertex-edge graph or just graph) of a polytope is a combinatorial graph whose vertices and edges correspond directly to the vertices and edges of the polytope.
As a purely combinatorial object, the edge graph encodes incidence information, capturing which vertices are connected by edges, but it does not retain geometric data such as vertex positions or edge lengths. 
Further common names for the edge graph are skeleton and 1-skeleton, though some authors reserve these terms for the geometric embedding formed by the vertices and edges in the polytope's ambient space.
There is no universally agreed upon notation for the edge graph of a polytope 
  
    
      
        P
      
    
    
  
. Common notations include 
  
    
      
        
          G
          
            P
          
        
      
    
    
  
, 
  
    
      
        G
        P
      
    
    
  
 or 
  
    
      
        skel
         
        P
      
    
    
  
.
Not all graphs are realizable as edge graphs of polytopes; those that are realizable in this manner are called polytopal graphs.
Edge graphs of 3-dimensional polytopes are also called polyhedral graphs. 
The problem of deciding whether a given graph is polytopal or not is known as the realization problem and is NP hard in general dimension. In dimension three the problem is also called the Steinitz problem in recognition of its resolution by Ernst Steinitz.
Information about the polytope's faces of dimension two or higher is not immediately accessible from the edge graph, and often cannot be reconstruction from it at all.
To capture the full combinatorial structure of a polytope, including the number of faces of each dimension and the incidence relations between them, one needs to work with the polytope's face lattice.
In analogy to the term "1-skeleton", the part of the face lattice that contains the information about the combinatorics of faces up to dimension 
  
    
      
        k
      
    
    
  
 is called the 
  
    
      
        k
      
    
    
  
-skeleton of the polytope.

## Related

- [[Forbidden graph characterization]]
- [[Absolutely convex set]]
- [[Albertson index]]
- [[Algorithmic problems on convex sets]]
- [[Antimatroid]]
- [[Aperiodic graph]]
- [[Arrangement (space partition)]]
- [[Arrangement of hyperplanes]]
- [[Asymptotic geometry]]
- [[Bicircular matroid]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_of_a_polytope