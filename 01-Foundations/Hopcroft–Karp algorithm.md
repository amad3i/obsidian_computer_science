---
title: "Hopcroft–Karp algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hopcroft–Karp_algorithm"
wikipedia_categories: ["Graph algorithms", "Matching (graph theory)"]
related: ["[[Blossom algorithm]]", "[[Dulmage–Mendelsohn decomposition]]", "[[Gallai–Edmonds decomposition]]", "[[Hall-type theorems for hypergraphs]]", "[[3-dimensional matching]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]"]
---

# Hopcroft–Karp algorithm

In computer science, the Hopcroft–Karp algorithm (sometimes more accurately called the Hopcroft–Karp–Karzanov algorithm) is an algorithm that takes a bipartite graph as input and produces a maximum-cardinality matching as output — a set of as many edges as possible with the property that no two edges share an endpoint. It runs in 
  
    
      
        O
        
          |
        
        E
        
          |
        
        
          
            
              |
            
            V
            
              |
            
          
        
      
    
    
  
 time in the worst case, where 
  
    
      
        E
      
    
    
  
 is set of edges in the graph, 
  
    
      
        V
      
    
    
  
 is set of vertices of the graph, and it is assumed that 
  
    
      
        
          |
        
        E
        
          |
        
        Ω
        
          |
        
        V
        
          |
        
      
    
    
  
. In the case of dense graphs the time bound becomes 
  
    
      
        O
        
          |
        
        V
        
          
            |
          
          
            2.5
          
        
      
    
    
  
, and for sparse random graphs it runs in time 
  
    
      
        O
        
          |
        
        E
        
          |
        
         
        
          |
        
        V
        
          |
        
      
    
    
  
 with high probability.
The algorithm was discovered by John Hopcroft and Richard Karp (1973) and independently by Alexander Karzanov (1973). As in previous methods for matching such as the Hungarian algorithm and the work of Edmonds (1965), the Hopcroft–Karp algorithm repeatedly increases the size of a partial matching by finding augmenting paths. These paths are sequences of edges of the graph, which alternate between edges in the matching and edges out of the partial matching, and where the initial and final edge are not in the partial matching. Finding an augmenting path allows us to increment the size of the partial matching, by simply toggling the edges of the augmenting path (putting in the partial matching those that were not, and vice versa). Simpler algorithms for bipartite matching, such as the Ford–Fulkerson algorithm‚ find one augmenting path per iteration: the Hopcroft-Karp algorithm instead finds a maximal set of shortest augmenting paths, so as to ensure that only 
  
    
      
        O
        
          
            
              |
            
            V
            
              |
            
          
        
      
    
    
  
 iterations are needed instead of 
  
    
      
        O
        
          |
        
        V
        
          |
        
      
    
    
  
 iterations. The same performance of 
  
    
      
        O
        
          |
        
        E
        
          |
        
        
          
            
              |
            
            V
            
              |
            
          
        
      
    
    
  
 can be achieved to find maximum-cardinality matchings in arbitrary graphs, with the more complicated algorithm of Micali and Vazirani.
The Hopcroft–Karp algorithm can be seen as a special case of Dinic's algorithm for the maximum-flow problem.

## Related

- [[Blossom algorithm]]
- [[Dulmage–Mendelsohn decomposition]]
- [[Gallai–Edmonds decomposition]]
- [[Hall-type theorems for hypergraphs]]
- [[3-dimensional matching]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hopcroft–Karp_algorithm