---
title: "Log-rank conjecture"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Log-rank_conjecture"
wikipedia_categories: ["Communication"]
related: ["[[Communication]]", "[[Communication source]]", "[[Information]]", "[[Recording format]]", "[[Shannon–Weaver model]]", "[[Tangible symbol systems]]", "[[Transderivational search]]"]
---

# Log-rank conjecture

In theoretical computer science, the log-rank conjecture states that the deterministic communication complexity of a two-party Boolean function is polynomially related to the logarithm of the rank of its input matrix.
Let 
  
    
      
        D
        f
      
    
    
  
 denote the deterministic communication complexity of a function, and let 
  
    
      
        rank
         
        f
      
    
    
  
 denote the rank of its input matrix 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
 (over the reals). Since every protocol using up to 
  
    
      
        c
      
    
    
  
 bits partitions 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
 into at most 
  
    
      
        
          2
          
            c
          
        
      
    
    
  
 monochromatic rectangles, and each of these has rank at most 1,

  
    
      
        D
        f
        ≥
        
          
            2
          
        
         
        rank
         
        f
        .
      
    
    
  

The log-rank conjecture states that 
  
    
      
        D
        f
      
    
    
  
 is also upper-bounded by a polynomial in the log-rank: for some constant 
  
    
      
        C
      
    
    
  
,

  
    
      
        D
        f
        =
        O
        (
         
        rank
         
        f
        
          
            C
          
        
        .
      
    
    
  

Lovett

proved the upper bound

  
    
      
        D
        f
        =
        O
        
          
            
              
                rank
                 
                f
              
            
             
            rank
             
            f
          
        
        .
      
    
    
  

This was improved by Sudakov and Tomon, who removed the logarithmic factor, showing that

  
    
      
        D
        f
        =
        O
        
          
            
              rank
               
              f
            
          
        
        .
      
    
    
  

This is the best currently known upper bound.
The best known lower bound, due to Göös, Pitassi and Watson, states that 
  
    
      
        C
        ≥
        2
      
    
    
  
. In other words, there exists a sequence of functions 
  
    
      
        
          f
          
            n
          
        
      
    
    
  
, whose log-rank goes to infinity, such that

  
    
      
        D
        
          f
          
            n
          
        
        =
        
          
            
              Ω
              ~
            
          
        
        (
         
        rank
         
        
          f
          
            n
          
        
        
          
            2
          
        
        .
      
    
    
  

In 2019, an approximate version of the conjecture for randomised communication has been disproved.

## Related

- [[Communication]]
- [[Communication source]]
- [[Information]]
- [[Recording format]]
- [[Shannon–Weaver model]]
- [[Tangible symbol systems]]
- [[Transderivational search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Log-rank_conjecture