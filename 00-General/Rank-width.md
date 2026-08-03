---
title: "Rank-width"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Rank-width"
wikipedia_categories: ["Graph minor theory"]
related: ["[[Courcelle's theorem]]", "[[Forbidden graph characterization]]"]
---

# Rank-width

Rank-width is a graph width parameter used in graph theory and parameterized complexity, and defined using linear algebra.
It is defined from hierarchical clusterings of the vertices of a given graph, which can be visualized as ternary trees having the vertices as their leaves. Removing any edge from such a tree disconnects it into two subtrees and partitions the vertices into two subsets. The graph edges that cross from one side of the partition to the other can be described by a biadjacency matrix; for the purposes of rank-width, this matrix is defined over the finite field GF(2) rather than using real numbers. The rank-width of a graph is the maximum of the ranks of the biadjacency matrices, for a clustering chosen to minimize this maximum.
Rank-width is closely related to clique-width: 
  
    
      
        k
        ≤
        c
        ≤
        
          2
          
            k
            1
          
        
        1
      
    
    
  
, where 
  
    
      
        c
      
    
    
  
 is the clique-width and 
  
    
      
        k
      
    
    
  
 the rank-width. However, clique-width is NP-hard to compute, for graphs of large clique-width, and its parameterized complexity is unknown. In contrast, testing whether the rank-width is at most a constant 
  
    
      
        k
      
    
    
  
 takes polynomial time, and even when the rank-width is not constant it can be approximated, with a constant approximation ratio, in polynomial time. For this reason, rank-width can be used as a more easily computed substitute for clique-width.
An example of a family of graphs with high rank-width is provided by the square grid graphs. For an 
  
    
      
        n
        n
      
    
    
  
 grid graph, the rank-width is exactly 
  
    
      
        n
        1
      
    
    
  
.
Trees have rank-width at most 1, and the graphs with rank-width at most 1 are precisely distance-hereditary graphs. Graphs of small rank-width are precisely pivot-minors of graphs of small tree-width. A connected graph G with 
  
    
      
        n
      
    
    
  
 vertices and 
  
    
      
        m
      
    
    
  
 edges has a rank-width of at most 
  
    
      
        m
        n
        2
      
    
    
  
. A simple proof is to consider a spanning tree and note that trees have rank-width 1. Adding an edge to a graph increases the cut-rank function by at most 1 which increases the rank-width by at most 1, so adding the 
  
    
      
        m
        n
        1
      
    
    
  
 extra edges to the spanning tree increases the rank-width by at most 
  
    
      
        m
        n
        1
      
    
    
  
.

## Related

- [[Courcelle's theorem]]
- [[Forbidden graph characterization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rank-width