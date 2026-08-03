---
title: "Seidel's algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Seidel's_algorithm"
wikipedia_categories: ["Computational problems in graph theory", "Graph algorithms", "Graph distance", "Polynomial-time problems"]
related: ["[[Bellman–Ford algorithm]]", "[[Floyd–Warshall algorithm]]", "[[K shortest path routing]]", "[[Longest path problem]]", "[[Network simplex algorithm]]", "[[Widest path problem]]", "[[A- search algorithm]]", "[[Centrality]]", "[[Dijkstra's algorithm]]", "[[Graph edit distance]]"]
---

# Seidel's algorithm

Seidel's algorithm is an algorithm designed by Raimund Seidel in 1992 for the all-pairs-shortest-path problem for undirected, unweighted, connected graphs. It solves the problem in 
  
    
      
        O
        
          V
          
            ω
          
        
         
        V
      
    
    
  
 expected time for a graph with 
  
    
      
        V
      
    
    
  
 vertices, where 
  
    
      
        ω
        2.373
      
    
    
  
 is the exponent in the complexity 
  
    
      
        O
        
          n
          
            ω
          
        
      
    
    
  
 of 
  
    
      
        n
        n
      
    
    
  
 matrix multiplication. If only the distances between each pair of vertices are sought, the same time bound can be achieved in the worst case. Even though the algorithm is designed for connected graphs, it can be applied individually to each connected component of a graph with the same running time overall. There is an exception to the expected running time given above for computing the paths: if 
  
    
      
        ω
        2
      
    
    
  
 the expected running time becomes 
  
    
      
        O
        
          V
          
            2
          
        
        
          
            2
          
        
         
        V
      
    
    
  
.

## Related

- [[Bellman–Ford algorithm]]
- [[Floyd–Warshall algorithm]]
- [[K shortest path routing]]
- [[Longest path problem]]
- [[Network simplex algorithm]]
- [[Widest path problem]]
- [[A- search algorithm]]
- [[Centrality]]
- [[Dijkstra's algorithm]]
- [[Graph edit distance]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Seidel's_algorithm