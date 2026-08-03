---
title: "Misra & Gries edge-coloring algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Misra_&_Gries_edge-coloring_algorithm"
wikipedia_categories: ["Graph algorithms", "Graph coloring"]
related: ["[[DSatur]]", "[[Recursive largest first algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]"]
---

# Misra & Gries edge-coloring algorithm

The Misra & Gries edge-coloring algorithm is a polynomial-time algorithm in graph theory that finds an edge coloring of any simple graph. The coloring produced uses at most 
  
    
      
        Δ
        1
      
    
    
  
 colors, where 
  
    
      
        Δ
      
    
    
  
 is the maximum degree of the graph. This is optimal for some graphs, and it uses at most one color more than optimal for all others. The existence of such a coloring is guaranteed by Vizing's theorem.
It was first published by Jayadev Misra and David Gries in 1992. It is a simplification of a prior algorithm by Béla Bollobás.
For many years this algorithm was the fastest published almost-optimal algorithm for edge coloring, executing in 
  
    
      
        O
        
          |
        
        E
        
          |
        
        
          |
        
        V
        
          |
        
      
    
    
  
 time. A faster time bound of 
  
    
      
        O
        
          
            
              |
            
            E
            
              |
            
            
              
                
                  |
                
                V
                
                  |
                
                 
                
                  |
                
                V
                
                  |
                
              
            
          
        
      
    
    
  
 was claimed in a 1985 technical report by Gabow et al., but was never published. In 2025 a group of researchers published a faster algorithm for the same problem, with runtime 
  
    
      
        O
        
          |
        
        E
        
          |
        
         
        Δ
      
    
    
  
.
In general, optimal edge coloring is NP-complete, so it is very unlikely that a polynomial time algorithm exists. There are, however, exponential-time exact edge-coloring algorithms that give an optimal solution.

## Related

- [[DSatur]]
- [[Recursive largest first algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Misra_&_Gries_edge-coloring_algorithm