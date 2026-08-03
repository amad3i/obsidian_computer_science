---
title: "Descent direction"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Descent_direction"
wikipedia_categories: ["Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Descent direction

In optimization, a descent direction is a vector 
  
    
      
        
          p
        
        ∈
        
          
            R
          
          
            n
          
        
      
    
    
  
 that points towards a local minimum 
  
    
      
        
          
            x
          
          
          
        
      
    
    
  
 of an objective function 
  
    
      
        f
        :
        
          
            R
          
          
            n
          
        
        →
        
          R
        
      
    
    
  
.
Computing 
  
    
      
        
          
            x
          
          
          
        
      
    
    
  
 by an iterative method, such as line search defines a descent direction 
  
    
      
        
          
            p
          
          
            k
          
        
        ∈
        
          
            R
          
          
            n
          
        
      
    
    
  
 at the 
  
    
      
        k
      
    
    
  
th iterate to be any 
  
    
      
        
          
            p
          
          
            k
          
        
      
    
    
  
 such that 
  
    
      
        ⟨
        
          
            p
          
          
            k
          
        
        ,
        ∇
        f
        
          
            x
          
          
            k
          
        
        ⟩
        0
      
    
    
  
, where 
  
    
      
        ⟨
        ,
        ⟩
      
    
    
  
 denotes the inner product. The motivation for such an approach is that small steps along 
  
    
      
        
          
            p
          
          
            k
          
        
      
    
    
  
 guarantee that 
  
    
      
        
          f
        
      
    
    
  
 is reduced, by Taylor's theorem.
Using this definition, the negative of a non-zero gradient is always a
descent direction, as 
  
    
      
        ⟨
        ∇
        f
        
          
            x
          
          
            k
          
        
        ,
        ∇
        f
        
          
            x
          
          
            k
          
        
        ⟩
        −
        ⟨
        ∇
        f
        
          
            x
          
          
            k
          
        
        ,
        ∇
        f
        
          
            x
          
          
            k
          
        
        ⟩
        0
      
    
    
  
.
Numerous methods exist to compute descent directions, all with differing merits, such as gradient descent or the conjugate gradient method.
More generally, if 
  
    
      
        P
      
    
    
  
 is a positive definite matrix, then

  
    
      
        
          p
          
            k
          
        
        −
        P
        ∇
        f
        
          x
          
            k
          
        
      
    
    
  
 is a descent direction at 
  
    
      
        
          x
          
            k
          
        
      
    
    
  
. This generality is used in preconditioned gradient descent methods.

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

- Wikipedia: https://en.wikipedia.org/wiki/Descent_direction