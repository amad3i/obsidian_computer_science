---
title: "McCarthy 91 function"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/McCarthy_91_function"
wikipedia_categories: ["Formal methods", "Recurrence relations"]
related: ["[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]", "[[Applicative universal grammar]]", "[[Assertion (software development)]]", "[[Asynchronous system]]"]
---

# McCarthy 91 function

The McCarthy 91 function is a recursive function, defined by the computer scientist John McCarthy as a test case for formal verification within computer science.
The McCarthy 91 function is defined as

  
    
      
        M
        n
        =
        
          
            
              
                
                  n
                  10
                  ,
                
                
                  
                    
                      if 
                    
                  
                  n
                  100
                  
                    
                       
                    
                  
                
              
              
                
                  M
                  M
                  n
                  11
                  )
                  ,
                
                
                  
                    
                      if 
                    
                  
                  n
                  ≤
                  100
                  
                    
                       
                    
                  
                
              
            
            
          
        
      
    
    
  

The results of evaluating the function are given by M(n) = 91 for all integer arguments n ≤ 100, and M(n) = n − 10 for n > 100. Indeed, the result of M(101) is also 91 (101 - 10 = 91). All results of M(n) after n = 101 are continually increasing by 1, e.g. M(102) = 92, M(103) = 93.

## Related

- [[1-in-3-SAT]]
- [[Abstract state machine]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Algebraic specification]]
- [[Algorithm characterizations]]
- [[And-inverter graph]]
- [[Applicative universal grammar]]
- [[Assertion (software development)]]
- [[Asynchronous system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/McCarthy_91_function