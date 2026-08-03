---
title: "Proximal operator"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Proximal_operator"
wikipedia_categories: ["Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Proximal operator

In mathematical optimization, the proximal operator is an operator associated with a proper, lower semi-continuous convex function 
  
    
      
        f
      
    
    
  
 from a Hilbert space 
  
    
      
        
          
            X
          
        
      
    
    
  

to 
  
    
      
        −
        ∞
        ,
        ∞
      
    
    
  
, and is defined by:

  
    
      
        
          prox
          
            f
          
        
         
        v
        =
        arg
         
        
          min
          
            x
            ∈
            
              
                X
              
            
          
        
        
          
            f
            x
            +
            
              
                1
                2
              
            
            ‖
            x
            v
            
              ‖
              
                
                  X
                
              
              
                2
              
            
          
        
        .
      
    
    
  

For any function in this class, the minimizer of the right-hand side above is unique, hence making the proximal operator well-defined. The proximal operator  is used in proximal gradient methods, which is frequently used in optimization algorithms associated with non-differentiable optimization problems such as total variation denoising.

## Related

- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]
- [[Bayesian efficiency]]
- [[Bilinear program]]
- [[Binary constraint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Proximal_operator