---
title: "Quadratically constrained quadratic program"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Quadratically_constrained_quadratic_program"
wikipedia_categories: ["Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Quadratically constrained quadratic program

In mathematical optimization, a quadratically constrained quadratic program (QCQP) is an optimization problem in which both the objective function and the constraints are quadratic functions. It has the form

  
    
      
        
          
            
              
              
                
                  minimize
                
              
              
              
                
                  
                    
                      1
                      2
                    
                  
                
                
                  x
                  
                    
                      T
                    
                  
                
                
                  P
                  
                    0
                  
                
                x
                
                  q
                  
                    0
                  
                  
                    
                      T
                    
                  
                
                x
              
            
            
              
              
                
                  subject to
                
              
              
              
                
                  
                    
                      1
                      2
                    
                  
                
                
                  x
                  
                    
                      T
                    
                  
                
                
                  P
                  
                    i
                  
                
                x
                
                  q
                  
                    i
                  
                  
                    
                      T
                    
                  
                
                x
                
                  r
                  
                    i
                  
                
                ≤
                0
                
                
                  for 
                
                i
                1
                ,
                …
                ,
                m
                ,
              
            
            
              
              
              
              
                A
                x
                b
                ,
              
            
          
        
      
    
    
  

where P0, ..., Pm are n-by-n matrices and x ∈ Rn is the optimization variable.
If P0, ..., Pm are all positive semidefinite, then the problem is convex. If these matrices are neither positive nor negative semidefinite, the problem is non-convex. If P1, ... ,Pm are all zero, then the constraints are in fact linear and the problem is a quadratic program.

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

- Wikipedia: https://en.wikipedia.org/wiki/Quadratically_constrained_quadratic_program