---
title: "Logical depth"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Logical_depth"
wikipedia_categories: ["Computational complexity theory", "Information theory", "Measures of complexity", "Theoretical computer science stubs"]
related: ["[[Effective complexity]]", "[[Kolmogorov complexity]]", "[[Communication complexity]]", "[[Complexity class]]", "[[Compression theorem]]", "[[Generalized game]]", "[[Glossary of quantum computing]]", "[[Lempel–Ziv complexity]]", "[[Quantum capacity]]", "[[Quantum computing]]"]
---

# Logical depth

Logical depth is a measure of complexity for individual strings devised by Charles H. Bennett based on the computational complexity of an algorithm that can recreate a given piece of information. It differs from Kolmogorov complexity in that it considers the computation time of the algorithm with nearly minimal length, rather than the length of the minimal algorithm.
Informally, the logical depth of a string 
  
    
      
        x
      
    
    
  
 to a significance level 
  
    
      
        s
      
    
    
  
 is the time required to compute 
  
    
      
        x
      
    
    
  
 by a program no more than 
  
    
      
        s
      
    
    
  
 bits longer than the shortest program that computes 
  
    
      
        x
      
    
    
  
.
Formally, let 
  
    
      
        
          p
          
          
        
      
    
    
  
 be the shortest program that computes a string 
  
    
      
        x
      
    
    
  
 on some universal computer 
  
    
      
        U
      
    
    
  
. Then the logical depth of 
  
    
      
        x
      
    
    
  
 to the significance level 
  
    
      
        s
      
    
    
  
 is given by 
  
    
      
        
          min
        
        T
        p
        :
        
          |
        
        p
        
          |
        
        
          |
        
        
          p
          
          
        
        
          |
        
        s
        ∧
        U
        p
        =
        x
        }
        ,
      
    
    
  
 where 
  
    
      
        T
        p
      
    
    
  
 is the number of computation steps that 
  
    
      
        p
      
    
    
  
 made on 
  
    
      
        U
      
    
    
  
 to produce 
  
    
      
        x
      
    
    
  
 and halt.

## Related

- [[Effective complexity]]
- [[Kolmogorov complexity]]
- [[Communication complexity]]
- [[Complexity class]]
- [[Compression theorem]]
- [[Generalized game]]
- [[Glossary of quantum computing]]
- [[Lempel–Ziv complexity]]
- [[Quantum capacity]]
- [[Quantum computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Logical_depth