---
title: "Parameterized approximation algorithm"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Parameterized_approximation_algorithm"
wikipedia_categories: ["Algorithms", "Approximation algorithms", "Parameterized complexity"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]"]
---

# Parameterized approximation algorithm

A parameterized approximation algorithm is a type of algorithm that aims to find approximate solutions to NP-hard optimization problems in polynomial time in the input size and a function of a specific parameter. These algorithms are designed to combine the best aspects of both traditional approximation algorithms and fixed-parameter tractability.
In traditional approximation algorithms, the goal is to find solutions that are at most a certain factor α away from the optimal solution, known as an α-approximation, in polynomial time. On the other hand, parameterized algorithms are designed to find exact solutions to problems, but with the constraint that the running time of the algorithm is polynomial in the input size and a function of a specific parameter k. The parameter describes some property of the input and is small in typical applications. The problem is said to be fixed-parameter tractable (FPT) if there is an algorithm that can find the optimum solution in 
  
    
      
        f
        k
        
          n
          
            O
            1
          
        
      
    
    
  
 time, where 
  
    
      
        f
        k
      
    
    
  
 is a function independent of the input size n.
A parameterized approximation algorithm aims to find a balance between these two approaches by finding approximate solutions in FPT time: the algorithm computes an α-approximation in 
  
    
      
        f
        k
        
          n
          
            O
            1
          
        
      
    
    
  
 time, where 
  
    
      
        f
        k
      
    
    
  
 is a function independent of the input size n. This approach aims to overcome the limitations of both traditional approaches by having stronger guarantees on the solution quality compared to traditional approximations while still having efficient running times as in FPT algorithms. An overview of the research area studying parameterized approximation algorithms can be found in the survey of Marx and the more recent survey by Feldmann et al.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Parameterized_approximation_algorithm