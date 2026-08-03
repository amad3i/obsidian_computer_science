---
title: "Fast Walsh–Hadamard transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fast_Walsh–Hadamard_transform"
wikipedia_categories: ["Algorithms and data structures stubs", "Digital signal processing", "Signal processing stubs"]
related: ["[[Adjoint filter]]", "[[Delay equalization]]", "[[Encoding law]]", "[[High frequency content measure]]", "[[Polyphase quadrature filter]]", "[[Spectral flux]]", "[[Time-domain harmonic scaling]]", "[[Unity amplitude]]", "[[V-by-One US]]", "[[Warped linear predictive coding]]"]
---

# Fast Walsh–Hadamard transform

In computational mathematics, the Hadamard ordered fast Walsh–Hadamard transform (FWHTh) is an efficient algorithm to compute the Walsh–Hadamard transform (WHT).  A naive implementation of the WHT of order 
  
    
      
        n
        
          2
          
            m
          
        
      
    
    
  
 would have a computational complexity of O(
  
    
      
        
          n
          
            2
          
        
      
    
    
  
).  The FWHTh requires only 
  
    
      
        n
         
        n
      
    
    
  
 additions or subtractions.
The FWHTh is a divide-and-conquer algorithm that recursively breaks down a WHT of size 
  
    
      
        n
      
    
    
  
 into two smaller WHTs of size 
  
    
      
        n
        
          /
        
        2
      
    
    
  
.   This implementation follows the recursive definition of the 
  
    
      
        
          2
          
            m
          
        
        
          2
          
            m
          
        
      
    
    
  
 Hadamard matrix 
  
    
      
        
          H
          
            m
          
        
      
    
    
  
:

  
    
      
        
          H
          
            m
          
        
        
          
            1
            
              2
            
          
        
        
          
            
              
                
                  
                    H
                    
                      m
                      1
                    
                  
                
                
                  
                    H
                    
                      m
                      1
                    
                  
                
              
              
                
                  
                    H
                    
                      m
                      1
                    
                  
                
                
                  
                    H
                    
                      m
                      1
                    
                  
                
              
            
          
        
        .
      
    
    
  

The 
  
    
      
        1
        
          /
        
        
          
            2
          
        
      
    
    
  
 normalization factors for each stage may be grouped together or even omitted.
The sequency-ordered, also known as Walsh-ordered, fast Walsh–Hadamard transform, FWHTw, is obtained by computing the FWHTh as above, and then rearranging the outputs.
A simple fast nonrecursive implementation of the Walsh–Hadamard transform follows from decomposition of the Hadamard transform matrix as 
  
    
      
        
          H
          
            m
          
        
        
          A
          
            m
          
        
      
    
    
  
, where A is m-th root of 
  
    
      
        
          H
          
            m
          
        
      
    
    
  
.

## Related

- [[Adjoint filter]]
- [[Delay equalization]]
- [[Encoding law]]
- [[High frequency content measure]]
- [[Polyphase quadrature filter]]
- [[Spectral flux]]
- [[Time-domain harmonic scaling]]
- [[Unity amplitude]]
- [[V-by-One US]]
- [[Warped linear predictive coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fast_Walsh–Hadamard_transform