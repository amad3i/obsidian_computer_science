---
title: "Cuthill–McKee algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Cuthill–McKee_algorithm"
wikipedia_categories: ["Graph algorithms", "Matrix theory", "Sparse matrices"]
related: ["[[A- search algorithm]]", "[[Adjugate matrix]]", "[[Alpha–beta pruning]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]"]
---

# Cuthill–McKee algorithm

In numerical linear algebra, the Cuthill–McKee algorithm (CM), named after Elizabeth Cuthill and James McKee, is an algorithm to permute a sparse matrix that has a symmetric sparsity pattern into a   band matrix form with a small bandwidth. The reverse Cuthill–McKee algorithm  (RCM)  due to Alan George and Joseph Liu is the same algorithm but with the resulting index numbers reversed. In practice this generally results in less fill-in  than the CM ordering when Gaussian elimination is applied.
The Cuthill McKee algorithm is a variant of the standard breadth-first search
algorithm used in graph algorithms. It starts with a peripheral node and then
generates levels 
  
    
      
        
          R
          
            i
          
        
      
    
    
  
 for 
  
    
      
        i
        1
        ,
        2
        ,
        .
        .
      
    
    
  
 until all nodes
are exhausted. The set 
  
    
      
        
          R
          
            i
            1
          
        
      
    
    
  
 is created from set 
  
    
      
        
          R
          
            i
          
        
      
    
    
  

by listing all vertices adjacent to all nodes in 
  
    
      
        
          R
          
            i
          
        
      
    
    
  
. These 
nodes are ordered according to predecessors and degree.

## Related

- [[A- search algorithm]]
- [[Adjugate matrix]]
- [[Alpha–beta pruning]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cuthill–McKee_algorithm