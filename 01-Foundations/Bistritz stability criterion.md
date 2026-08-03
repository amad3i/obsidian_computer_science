---
title: "Bistritz stability criterion"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bistritz_stability_criterion"
wikipedia_categories: ["Digital signal processing", "Stability theory", "Systems theory"]
related: ["[[Anticausal system]]", "[[BIBO stability]]", "[[Causal system]]", "[[Instability]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Active and passive transformation]]", "[[Activity cycle diagram]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]"]
---

# Bistritz stability criterion

In signal processing and control theory, the Bistritz criterion is a simple method to determine whether a discrete, linear, time-invariant (LTI) system is stable proposed by Yuval Bistritz. Stability of a discrete LTI system requires that its characteristic polynomial

  
    
      
        
          D
          
            n
          
        
        z
        =
        
          d
          
            0
          
        
        
          d
          
            1
          
        
        z
        
          d
          
            2
          
        
        
          z
          
            2
          
        
        ⋯
        
          d
          
            n
            1
          
        
        
          z
          
            n
            1
          
        
        
          d
          
            n
          
        
        
          z
          
            n
          
        
      
    
    
  

(obtained from its difference equation, its dynamic matrix, or appearing as the denominator of its transfer function) is a stable polynomial, where  
  
    
      
        
          d
          
            n
          
        
        0
      
    
    
  
 and 
  
    
      
        
          D
          
            n
          
        
        z
      
    
    
  
 is said to be stable if all its roots (zeros) are inside the unit circle, viz.

  
    
      
        
          |
        
        
          z
          
            k
          
        
        
          |
        
        1
        ,
        k
        1
        ,
        …
        ,
        n
      
    
    
  
,
where 
  
    
      
        
          D
          
            n
          
        
        z
        =
        
          d
          
            n
          
        
        
          ∏
          
            k
            1
          
          
            n
          
        
        z
        
          z
          
            k
          
        
      
    
    
  
. The test determines whether 
  
    
      
        
          D
          
            n
          
        
        z
      
    
    
  
 is stable algebraically (i.e. without numerical determination of the zeros). The method also solves the full zero location (ZL) problem. Namely, it can count the number of inside the unit-circle (IUC) zeros (
  
    
      
        
          |
        
        
          z
          
            k
          
        
        
          |
        
        1
      
    
    
  
), on the unit-circle zeros (UC) zeros (
  
    
      
        
          |
        
        
          z
          
            k
          
        
        
          |
        
        1
      
    
    
  
) and outside the unit-circle (OUC) zeros (
  
    
      
        
          |
        
        
          z
          
            k
          
        
        
          |
        
        1
      
    
    
  
) for any real or complex polynomial.
The  Bistritz test is the discrete equivalent of Routh criterion used to test stability of continuous LTI systems. This title was introduced soon after its presentation. It has been also recognized to be more efficient than previously available stability tests for discrete systems like the Schur–Cohn and the Jury test.
In the following, the focus is only on how to test stability of a real polynomial. However,  as long as the basic recursion needed to test stability remains valid, ZL rules are also brought.

## Related

- [[Anticausal system]]
- [[BIBO stability]]
- [[Causal system]]
- [[Instability]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Active and passive transformation]]
- [[Activity cycle diagram]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bistritz_stability_criterion