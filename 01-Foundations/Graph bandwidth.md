---
title: "Graph bandwidth"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_bandwidth"
wikipedia_categories: ["Combinatorial optimization", "Graph algorithms", "Graph invariants", "NP-hard problems"]
related: ["[[Travelling salesman problem]]", "[[A- search algorithm]]", "[[B-]]", "[[Bottleneck traveling salesman problem]]", "[[Capacitated arc routing problem]]", "[[Closure problem]]", "[[Degeneracy (graph theory)]]", "[[Dijkstra's algorithm]]", "[[Gomory–Hu tree]]", "[[Network flow problem]]"]
---

# Graph bandwidth

In graph theory, the graph bandwidth problem may be visualized as placing the vertices of a given graph at distinct integer positions along the number line so that the length of the longest edge is minimized. Such placement is called linear graph arrangement, linear graph layout or linear graph placement.
It may be formalized as labeling the 
  
    
      
        n
      
    
    
  
 vertices 
  
    
      
        
          v
          
            i
          
        
      
    
    
  
 of a graph 
  
    
      
        G
      
    
    
  
 with distinct integers 
  
    
      
        f
        
          v
          
            i
          
        
      
    
    
  
 so that the quantity 
  
    
      
        max
        
        
          |
        
        f
        
          v
          
            i
          
        
        −
        f
        
          v
          
            j
          
        
        
          |
        
        :
        
          v
          
            i
          
        
        
          v
          
            j
          
        
        ∈
        E
        
      
    
    
  
 is minimized, where 
  
    
      
        E
      
    
    
  
 is the edge set of 
  
    
      
        G
      
    
    
  
.
The weighted graph bandwidth problem is a generalization wherein the edges are assigned weights 
  
    
      
        
          w
          
            i
            j
          
        
      
    
    
  
 and the cost function to be minimized is the product of weight with length, 
  
    
      
        max
        
        
          w
          
            i
            j
          
        
        
          |
        
        f
        
          v
          
            i
          
        
        −
        f
        
          v
          
            j
          
        
        
          |
        
        :
        
          v
          
            i
          
        
        
          v
          
            j
          
        
        ∈
        E
        
      
    
    
  
.
In terms of matrices, the (unweighted) graph bandwidth is the minimal bandwidth of a symmetric matrix which is an adjacency matrix of the graph.
The bandwidth may also be defined as one less than the maximum clique size in a proper interval supergraph of the given graph, chosen to minimize its clique size.

## Related

- [[Travelling salesman problem]]
- [[A- search algorithm]]
- [[B-]]
- [[Bottleneck traveling salesman problem]]
- [[Capacitated arc routing problem]]
- [[Closure problem]]
- [[Degeneracy (graph theory)]]
- [[Dijkstra's algorithm]]
- [[Gomory–Hu tree]]
- [[Network flow problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_bandwidth