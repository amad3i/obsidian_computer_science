---
title: "Basis pursuit denoising"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Basis_pursuit_denoising"
wikipedia_categories: ["Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]", "[[Cake number]]"]
---

# Basis pursuit denoising

In applied mathematics and statistics, basis pursuit denoising (BPDN) refers to a mathematical optimization problem of the form

  
    
      
        
          min
          
            x
          
        
        
          
            
              
                1
                2
              
            
            ‖
            y
            A
            x
            
              ‖
              
                2
              
              
                2
              
            
            λ
            ‖
            x
            
              ‖
              
                1
              
            
          
        
        ,
      
    
    
  

where 
  
    
      
        λ
      
    
    
  
 is a parameter that controls the trade-off between sparsity and reconstruction fidelity, 
  
    
      
        x
      
    
    
  
 is an 
  
    
      
        N
        1
      
    
    
  
 solution vector, 
  
    
      
        y
      
    
    
  
 is an 
  
    
      
        M
        1
      
    
    
  
 vector of observations, 
  
    
      
        A
      
    
    
  
 is an 
  
    
      
        M
        N
      
    
    
  
 transform matrix and 
  
    
      
        M
        N
      
    
    
  
. This is an instance of convex optimization.
Some authors refer to basis pursuit denoising as the following closely related problem:

  
    
      
        
          min
          
            x
          
        
        ‖
        x
        
          ‖
          
            1
          
        
        
           subject to 
        
        ‖
        y
        A
        x
        
          ‖
          
            2
          
          
            2
          
        
        ≤
        δ
        ,
      
    
    
  

which, for any given 
  
    
      
        λ
      
    
    
  
, is equivalent to the unconstrained formulation for some (usually unknown a priori) value of 
  
    
      
        δ
      
    
    
  
. The two problems are quite similar. In practice, the unconstrained formulation, for which most specialized and efficient computational algorithms are developed, is usually preferred.  The unconstrained formulation is NP-hard. 
Either types of basis pursuit denoising solve a regularization problem with a trade-off between having a small residual (making 
  
    
      
        y
      
    
    
  
 close to 
  
    
      
        A
        x
      
    
    
  
 in terms of the squared error) and making 
  
    
      
        x
      
    
    
  
 simple in the 
  
    
      
        
          ℓ
          
            1
          
        
      
    
    
  
-norm sense. It can be thought of as a mathematical statement of Occam's razor, finding the simplest possible explanation (i.e. one that yields 
  
    
      
        
          min
          
            x
          
        
        ‖
        x
        
          ‖
          
            1
          
        
      
    
    
  
) capable of accounting for the observations 
  
    
      
        y
      
    
    
  
.
Exact solutions to basis pursuit denoising are often the best computationally tractable approximation of an underdetermined system of equations.  Basis pursuit denoising has potential applications in statistics (see the LASSO method of regularization), image compression and compressed sensing.
When 
  
    
      
        δ
        0
      
    
    
  
, this problem becomes basis pursuit.
Basis pursuit denoising was introduced by Chen and Donoho in 1994, in the field of signal processing. In statistics, it is well known under the name LASSO, after being introduced by Tibshirani in 1996.

## Related

- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Bauer maximum principle]]
- [[Bayesian efficiency]]
- [[Bilinear program]]
- [[Binary constraint]]
- [[Cake number]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Basis_pursuit_denoising