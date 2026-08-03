---
title: "Pseudorandom graph"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Pseudorandom_graph"
wikipedia_categories: ["Graph theory"]
related: ["[[Albertson index]]", "[[Bicircular matroid]]", "[[Bristol Bridges Walk]]", "[[Capacitated arc routing problem]]", "[[Centrality]]", "[[Chip-firing game]]", "[[Complex network]]", "[[Consensus dynamics]]", "[[Convex subgraph]]", "[[Copying mechanism]]"]
---

# Pseudorandom graph

In graph theory, a graph is said to be a pseudorandom graph if it obeys certain properties that random graphs obey with high probability. There is no concrete definition of graph pseudorandomness, but there are many reasonable characterizations of pseudorandomness one can consider.
Pseudorandom properties were first formally considered by Andrew Thomason in 1987. He defined a condition called "jumbledness": a graph 
  
    
      
        G
        (
        V
        ,
        E
      
    
    
  
 is said to be 
  
    
      
        p
        ,
        α
      
    
    
  
-jumbled for real 
  
    
      
        p
      
    
    
  
 and 
  
    
      
        α
      
    
    
  
 with 
  
    
      
        0
        p
        1
        ≤
        α
      
    
    
  
 if

  
    
      
        
          |
          
            e
            U
            −
            p
            
              
                
                
                
                  
                    
                      |
                    
                    U
                    
                      |
                    
                  
                  2
                
                
                
              
            
          
          |
        
        ≤
        α
        
          |
        
        U
        
          |
        
      
    
    
  

for every subset 
  
    
      
        U
      
    
    
  
 of the vertex set 
  
    
      
        V
      
    
    
  
, where 
  
    
      
        e
        U
      
    
    
  
 is the number of edges among 
  
    
      
        U
      
    
    
  
 (equivalently, the number of edges in the subgraph induced by the vertex set 
  
    
      
        U
      
    
    
  
). It can be shown that the Erdős–Rényi random graph 
  
    
      
        G
        n
        ,
        p
      
    
    
  
 is almost surely 
  
    
      
        p
        ,
        O
        
          
            n
            p
          
        
        )
      
    
    
  
-jumbled. However, graphs with less uniformly distributed edges, for example a graph on 
  
    
      
        2
        n
      
    
    
  
 vertices consisting of an 
  
    
      
        n
      
    
    
  
-vertex complete graph and 
  
    
      
        n
      
    
    
  
 completely independent vertices, are not 
  
    
      
        p
        ,
        α
      
    
    
  
-jumbled for any small 
  
    
      
        α
      
    
    
  
, making jumbledness a reasonable quantifier for "random-like" properties of a graph's edge distribution.

## Related

- [[Albertson index]]
- [[Bicircular matroid]]
- [[Bristol Bridges Walk]]
- [[Capacitated arc routing problem]]
- [[Centrality]]
- [[Chip-firing game]]
- [[Complex network]]
- [[Consensus dynamics]]
- [[Convex subgraph]]
- [[Copying mechanism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pseudorandom_graph