---
title: "HHL algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/HHL_algorithm"
wikipedia_categories: ["Integer factorization algorithms", "Quantum algorithms"]
related: ["[[Shor's algorithm]]", "[[Aharonov–Jones–Landau algorithm]]", "[[Amplitude amplification]]", "[[Bernstein–Vazirani algorithm]]", "[[BHT algorithm]]", "[[Boson sampling]]", "[[Continuous-time quantum walk]]", "[[Deutsch–Jozsa algorithm]]", "[[Feynman's algorithm]]", "[[Grover's algorithm]]"]
---

# HHL algorithm

The Harrow–Hassidim–Lloyd (HHL) algorithm is a quantum algorithm for obtaining certain limited information about the solution to a system of linear equations, introduced by Aram Harrow, Avinatan Hassidim, and Seth Lloyd. Specifically, the algorithm estimates quadratic functions of the solution vector to a given system.
The algorithm is one of the main fundamental algorithms expected to provide a speedup over their classical counterparts, along with Shor's factoring algorithm and Grover's search algorithm. Assuming the system is sparse, has a low condition number 
  
    
      
        κ
      
    
    
  
, and that the user is only interested in certain information about solution vector and not the entire vector itself, the algorithm has a runtime of 
  
    
      
        O
        log
         
        N
        
          κ
          
            2
          
        
      
    
    
  
, where 
  
    
      
        N
      
    
    
  
 is the number of variables. This offers an exponential speedup over the fastest classical algorithm, which runs in 
  
    
      
        O
        N
        κ
      
    
    
  
 (or 
  
    
      
        O
        N
        
          
            κ
          
        
      
    
    
  
 for positive semidefinite matrices).
An implementation of the HHL algorithm was first demonstrated in 2013 by three independent publications, consisting of simple systems on specially designed devices. The first demonstration of a general-purpose version of the algorithm appeared in 2018.

## Related

- [[Shor's algorithm]]
- [[Aharonov–Jones–Landau algorithm]]
- [[Amplitude amplification]]
- [[Bernstein–Vazirani algorithm]]
- [[BHT algorithm]]
- [[Boson sampling]]
- [[Continuous-time quantum walk]]
- [[Deutsch–Jozsa algorithm]]
- [[Feynman's algorithm]]
- [[Grover's algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HHL_algorithm