---
title: "Equitable partition"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Equitable_partition"
wikipedia_categories: ["Algebraic graph theory"]
related: ["[[Albertson index]]", "[[Centrality]]", "[[Continuous-time quantum walk]]", "[[Fibrations of graphs]]", "[[Group centrality]]", "[[Hafnian]]", "[[Hierarchical closeness]]", "[[Incidence matrix]]", "[[Spectral clustering]]"]
---

# Equitable partition

In graph theory, a branch of mathematics, an equitable partition of the vertex set V of a graph G = (V, E) is a partition of V such that, for any pair of vertices u and v in the same set of the partition and any set B of the partition, both u and v have the same number of neighbors in B.
More precisely, one represents 
  
    
      
        V
        
          V
          
            1
          
        
        ∪
        
          V
          
            2
          
        
        ∪
        ⋯
        ∪
        
          V
          
            r
          
        
      
    
    
  
 where every vertex is contained in exactly one "cell" 
  
    
      
        
          V
          
            i
          
        
      
    
    
  
, the edges within each cell form a regular graph, and for any two distinct cells 
  
    
      
        
          V
          
            i
          
        
      
    
    
  
 and 
  
    
      
        
          V
          
            j
          
        
      
    
    
  
 and every vertex 
  
    
      
        
          v
          
            i
          
        
        ∈
        
          V
          
            i
          
        
      
    
    
  
, the number of edges 
  
    
      
        
          v
          
            i
          
        
        
          v
          
            j
          
        
      
    
    
  
 such that 
  
    
      
        
          v
          
            j
          
        
        ∈
        
          V
          
            j
          
        
      
    
    
  
 is a constant 
  
    
      
        
          b
          
            i
            j
          
        
      
    
    
  
, independent of the choice of 
  
    
      
        
          v
          
            i
          
        
        ∈
        
          V
          
            i
          
        
      
    
    
  
.
The characteristic matrix 
  
    
      
        P
      
    
    
  
 of the partition has a row for each vertex and a column for each cell, with 1 in row 
  
    
      
        v
      
    
    
  
 and column 
  
    
      
        
          V
          
            i
          
        
      
    
    
  
 if 
  
    
      
        v
        ∈
        
          V
          
            i
          
        
      
    
    
  
, otherwise 0.
Equitable partitions are important for simplifying calculations involving adjacency and related matrices of large graphs.

## Related

- [[Albertson index]]
- [[Centrality]]
- [[Continuous-time quantum walk]]
- [[Fibrations of graphs]]
- [[Group centrality]]
- [[Hafnian]]
- [[Hierarchical closeness]]
- [[Incidence matrix]]
- [[Spectral clustering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Equitable_partition