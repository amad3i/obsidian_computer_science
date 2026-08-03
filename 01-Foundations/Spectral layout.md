---
title: "Spectral layout"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Spectral_layout"
wikipedia_categories: ["Applied mathematics stubs", "Graph algorithms", "Graph drawing"]
related: ["[[Force-directed graph drawing]]", "[[Journal of Graph Algorithms and Applications]]", "[[A- search algorithm]]", "[[Adjoint state method]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[Artificial precision]]", "[[Artstein's theorem]]", "[[B-]]", "[[Barabási–Albert model]]"]
---

# Spectral layout

Spectral layout is a class of algorithm for drawing graphs. The layout uses the eigenvectors of a matrix, such as the Laplace matrix of the graph, as Cartesian coordinates of the graph's vertices.
The idea of the layout is to compute the two largest (or smallest) eigenvalues and corresponding eigenvectors of the Laplacian matrix of the graph and then use those for actually placing the nodes.
Usually nodes are placed in the 2 dimensional plane. An embedding into more dimensions can be found by using more eigenvectors.
In the 2-dimensional case, for a given node which corresponds to the row/column 
  
    
      
        i
      
    
    
  
 in the (symmetric) Laplacian matrix 
  
    
      
        L
      
    
    
  
 of the graph, the 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
-coordinates are the 
  
    
      
        i
      
    
    
  
-th entries of the first and second eigenvectors of 
  
    
      
        L
      
    
    
  
, respectively.

## Related

- [[Force-directed graph drawing]]
- [[Journal of Graph Algorithms and Applications]]
- [[A- search algorithm]]
- [[Adjoint state method]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[Artificial precision]]
- [[Artstein's theorem]]
- [[B-]]
- [[Barabási–Albert model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spectral_layout