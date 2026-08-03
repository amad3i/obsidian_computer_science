---
title: "Ackermann function"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Ackermann_function"
wikipedia_categories: ["Arithmetic", "Computability theory", "Large integers", "Special functions", "Theory of computation"]
related: ["[[Sudan function]]", "[[Busy beaver]]", "[[Admissible numbering]]", "[[Chain rule for Kolmogorov complexity]]", "[[Church–Turing thesis]]", "[[Church–Turing–Deutsch principle]]", "[[Computability]]", "[[Computable function]]", "[[Computable number]]", "[[Computable set]]"]
---

# Ackermann function

In computability theory, the Ackermann function, named after Wilhelm Ackermann, is one of the simplest and earliest-discovered examples of a total computable function that is not primitive recursive. All primitive recursive functions are total and computable, but the Ackermann function illustrates that not all total computable functions are primitive recursive. It is essentially constructed by diagonalizing a sequence of primitive recursive functions 
  
    
      
        
          f
          
            1
          
        
        ,
        
          f
          
            2
          
        
        ,
        …
      
    
    
  
 selected from the Grzegorczyk hierarchy. This makes the Ackermann function the first limit point 
  
    
      
        
          f
          
            ω
          
        
      
    
    
  
 of the fast-growing hierarchy.
After Ackermann's publication of his function (which had three non-negative integer arguments), many authors modified it to suit various purposes, so that today "the Ackermann function" may refer to any of numerous variants of the original function. One common version is the two-argument Ackermann–Péter function developed by Rózsa Péter and Raphael Robinson. This function is defined from the recurrence relation 
  
    
      
        A
         
        m
        1
        ,
        n
        1
        =
        A
         
        m
        ,
        A
         
        m
        1
        ,
        n
        )
      
    
    
  
 with appropriate base cases. Its value grows very rapidly; for example, 
  
    
      
        A
         
        4
        ,
        2
      
    
    
  
 results in 
  
    
      
        
          2
          
            65536
          
        
        3
      
    
    
  
, an integer with 19,729 decimal digits.

## Related

- [[Sudan function]]
- [[Busy beaver]]
- [[Admissible numbering]]
- [[Chain rule for Kolmogorov complexity]]
- [[Church–Turing thesis]]
- [[Church–Turing–Deutsch principle]]
- [[Computability]]
- [[Computable function]]
- [[Computable number]]
- [[Computable set]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ackermann_function