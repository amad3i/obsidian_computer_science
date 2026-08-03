---
title: "Wolfe conditions"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Wolfe_conditions"
wikipedia_categories: ["Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Wolfe conditions

In the unconstrained minimization problem, the Wolfe conditions (also known as  the Armijo-Wolfe conditions in some books) are a set of inequalities for performing inexact line search, especially in quasi-Newton methods, first published by Philip Wolfe in 1969 (also named after Larry Armijo).
In these methods the idea is to find

  
    
      
        
          min
          
            x
          
        
        f
        
          x
        
      
    
    
  

for some smooth 
  
    
      
        f
        :
        
          
            R
          
          
            n
          
        
        →
        
          R
        
      
    
    
  
. Each step often involves approximately solving the subproblem

  
    
      
        
          min
          
            α
          
        
        f
        
          
            x
          
          
            k
          
        
        α
        
          
            p
          
          
            k
          
        
      
    
    
  

where 
  
    
      
        
          
            x
          
          
            k
          
        
      
    
    
  
 is the current best guess, 
  
    
      
        
          
            p
          
          
            k
          
        
        ∈
        
          
            R
          
          
            n
          
        
      
    
    
  
 is a search direction, and 
  
    
      
        α
        ∈
        
          R
        
      
    
    
  
 is the step length.
The inexact line searches provide an efficient way of computing an acceptable step length 
  
    
      
        α
      
    
    
  
 that reduces the objective function 'sufficiently', rather than minimizing the objective function over 
  
    
      
        α
        ∈
        
          
            R
          
          
          
        
      
    
    
  
 exactly. A line search algorithm can use Wolfe conditions as a requirement for any guessed 
  
    
      
        α
      
    
    
  
, before finding a new search direction 
  
    
      
        
          
            p
          
          
            k
          
        
      
    
    
  
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

- Wikipedia: https://en.wikipedia.org/wiki/Wolfe_conditions