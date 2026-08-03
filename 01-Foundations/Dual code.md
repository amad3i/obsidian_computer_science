---
title: "Dual code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dual_code"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Dual code

In coding theory, the dual code of a linear code

  
    
      
        C
        ⊂
        
          
            F
          
          
            q
          
          
            n
          
        
      
    
    
  

is the linear code defined by

  
    
      
        
          C
          
            ⊥
          
        
        {
        x
        ∈
        
          
            F
          
          
            q
          
          
            n
          
        
        ∣
        ⟨
        x
        ,
        c
        ⟩
        0
        
        ∀
        c
        ∈
        C
      
    
    
  

where

  
    
      
        ⟨
        x
        ,
        c
        ⟩
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          x
          
            i
          
        
        
          c
          
            i
          
        
      
    
    
  

is a scalar product.  In linear algebra terms, the dual code is the annihilator of C with respect to the bilinear form 
  
    
      
        ⟨
        ⋅
        ⟩
      
    
    
  
. The dimension of C and its dual always add up to the length n:

  
    
      
        dim
         
        C
        dim
         
        
          C
          
            ⊥
          
        
        n
        .
      
    
    
  

A generator matrix for the dual code is the parity-check matrix for the original code and vice versa.  The dual of the dual code is always the original code.

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]
- [[Berlekamp switching game]]
- [[Berlekamp–Welch algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dual_code