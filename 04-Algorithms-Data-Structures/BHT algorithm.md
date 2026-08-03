---
title: "BHT algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/BHT_algorithm"
wikipedia_categories: ["Quantum algorithms"]
related: ["[[Aharonov–Jones–Landau algorithm]]", "[[Amplitude amplification]]", "[[Bernstein–Vazirani algorithm]]", "[[Boson sampling]]", "[[Continuous-time quantum walk]]", "[[Deutsch–Jozsa algorithm]]", "[[Feynman's algorithm]]", "[[Grover's algorithm]]", "[[Hadamard test]]", "[[Hadamard transform]]"]
---

# BHT algorithm

In quantum computing, the Brassard–Høyer–Tapp (BHT) algorithm is a quantum algorithm that solves the collision problem.  In this problem, one is given n and an 2-to-1 function 
  
    
      
        f
        :
        
        1
        ,
        …
        ,
        n
        →
        1
        ,
        …
        ,
        n
      
    
    
  
 and needs to find two inputs that f maps to the same output.  The BHT algorithm only makes 
  
    
      
        O
        
          n
          
            1
            
              /
            
            3
          
        
      
    
    
  
 queries to f, which matches the lower bound of 
  
    
      
        Ω
        
          n
          
            1
            
              /
            
            3
          
        
      
    
    
  
 in the black box model. The algorithm can be generalized to r-to-1 function with a complexity of 
  
    
      
        O
        
          
            
              
                
                  n
                  r
                
              
            
            
              1
              
                /
              
              3
            
          
        
      
    
    
  
.
The algorithm was discovered by Gilles Brassard, Peter Høyer, and Alain Tapp in 1997.  It uses Grover's algorithm, which was discovered the year before.

## Related

- [[Aharonov–Jones–Landau algorithm]]
- [[Amplitude amplification]]
- [[Bernstein–Vazirani algorithm]]
- [[Boson sampling]]
- [[Continuous-time quantum walk]]
- [[Deutsch–Jozsa algorithm]]
- [[Feynman's algorithm]]
- [[Grover's algorithm]]
- [[Hadamard test]]
- [[Hadamard transform]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/BHT_algorithm