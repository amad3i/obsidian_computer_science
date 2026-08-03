---
title: "Catalytic computing"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Catalytic_computing"
wikipedia_categories: ["Algorithms", "Complexity classes", "Computer science"]
related: ["[[Adaptive algorithm]]", "[[Agnostic (data)]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]"]
---

# Catalytic computing

Catalytic computing is a technique in computer science, relevant to complexity theory, that uses full memory, as well as empty memory space, to perform computations. Full memory is memory that begins in an arbitrary state and must be returned to that state at the end of the computation, for example important data. It can sometimes be used to reduce the memory needs of certain algorithms, for example the tree evaluation problem. It was defined by Buhrman, Cleve, Koucký, Loff, and Speelman in 2014 and was named after catalysts in chemistry, based on the metaphorically viewing the full memory as a "catalyst", a non-consumed factor critical for the computational "reaction" to succeed.
The complexity class CSPACE(s(n)) is the class of sets computable by catalytic Turing machines whose work tape is bounded by s(n) tape cells and whose auxiliary full memory space is bounded by 
  
    
      
        
          2
          
            s
            n
          
        
      
    
    
  
 tape cells. It has been shown that CSPACE(log(n)), or catalytic logspace, is contained within ZPP and, importantly, contains TC1.

## Related

- [[Adaptive algorithm]]
- [[Agnostic (data)]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Catalytic_computing