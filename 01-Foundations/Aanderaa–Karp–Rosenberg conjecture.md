---
title: "Aanderaa–Karp–Rosenberg conjecture"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Aanderaa–Karp–Rosenberg_conjecture"
wikipedia_categories: ["Combinatorics", "Computational complexity theory", "Conjectures", "Statements in graph theory", "Unsolved problems in computer science"]
related: ["[[Unique games conjecture]]", "[[Computational complexity of mathematical operations]]", "[[Computational complexity of matrix multiplication]]", "[[Dittert conjecture]]", "[[Erdős conjecture on arithmetic progressions]]", "[[Graph isomorphism problem]]", "[[No-three-in-line problem]]", "[[P versus NP problem]]", "[[Rudin's conjecture]]", "[[Singmaster's conjecture]]"]
---

# Aanderaa–Karp–Rosenberg conjecture

In theoretical computer science, the Aanderaa–Karp–Rosenberg conjecture (also known as the Aanderaa–Rosenberg conjecture or the evasiveness conjecture) is a group of related conjectures about the number of questions of the form "Is there an edge between vertex 
  
    
      
        u
      
    
    
  
 and vertex 
  
    
      
        v
      
    
    
  
?" that have to be answered to determine whether or not an undirected graph has a particular property such as planarity or bipartiteness. They are named after Stål Aanderaa, Richard M. Karp, and Arnold L. Rosenberg. According to the conjecture, for a wide class of properties, no algorithm can guarantee that it will be able to skip any questions: any algorithm for determining whether the graph has the property, no matter how clever, might need to examine every pair of vertices before it can give its answer. A property satisfying this conjecture is called evasive.
More precisely, the Aanderaa–Rosenberg conjecture states that any deterministic algorithm must test at least a constant fraction of all possible pairs of vertices, in the worst case, to determine any non-trivial monotone graph property. In this context, a property is monotone if it remains true when edges are added; for example, planarity is not monotone, but non-planarity is monotone. A stronger version of this conjecture, called the evasiveness conjecture or the Aanderaa–Karp–Rosenberg conjecture, states that exactly 
  
    
      
        
          
            
              
              
              
                n
                2
              
              
              
            
          
        
        n
        n
        1
        
          /
        
        2
      
    
    
  
 tests are needed for a graph with 
  
    
      
        n
      
    
    
  
 vertices. Versions of the problem for randomized algorithms and quantum algorithms have also been formulated and studied.
The deterministic Aanderaa–Rosenberg conjecture was proven by Rivest & Vuillemin (1975), but the stronger Aanderaa–Karp–Rosenberg conjecture remains unproven. Additionally, there is a large gap between the conjectured lower bound and the best proven lower bound for randomized and quantum query complexity.

## Related

- [[Unique games conjecture]]
- [[Computational complexity of mathematical operations]]
- [[Computational complexity of matrix multiplication]]
- [[Dittert conjecture]]
- [[Erdős conjecture on arithmetic progressions]]
- [[Graph isomorphism problem]]
- [[No-three-in-line problem]]
- [[P versus NP problem]]
- [[Rudin's conjecture]]
- [[Singmaster's conjecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Aanderaa–Karp–Rosenberg_conjecture