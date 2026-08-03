---
title: "Moreau envelope"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Moreau_envelope"
wikipedia_categories: ["Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Moreau envelope

The Moreau envelope (or the Moreau-Yosida regularization) 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
 of a proper lower semi-continuous convex function 
  
    
      
        f
      
    
    
  
 is a smoothed version of 
  
    
      
        f
      
    
    
  
. It was proposed by Jean-Jacques Moreau in 1965.
The Moreau envelope has important applications in mathematical optimization: minimizing over 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
 and minimizing over 
  
    
      
        f
      
    
    
  
 are equivalent problems in the sense that the sets of minimizers of 
  
    
      
        f
      
    
    
  
  and 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
 are the same. However, first-order optimization algorithms can be directly applied to 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
, since 
  
    
      
        f
      
    
    
  
 may be non-differentiable while 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
 is always continuously differentiable. Indeed, many proximal gradient methods can be interpreted as a gradient descent method over 
  
    
      
        
          M
          
            f
          
        
      
    
    
  
.

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

- Wikipedia: https://en.wikipedia.org/wiki/Moreau_envelope