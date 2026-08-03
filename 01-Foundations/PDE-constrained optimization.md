---
title: "PDE-constrained optimization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/PDE-constrained_optimization"
wikipedia_categories: ["Mathematical optimization", "Optimal control", "Partial differential equations"]
related: ["[[Hydrological optimization]]", "[[Optimal control]]", "[[Shape optimization]]", "[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]"]
---

# PDE-constrained optimization

PDE-constrained optimization is a subset of mathematical optimization where at least one of the constraints may be expressed as a partial differential equation. Typical domains where these problems arise include aerodynamics, computational fluid dynamics, image segmentation, and inverse problems. A standard formulation of PDE-constrained optimization encountered in a number of disciplines is given by:
  
    
      
        
          min
          
            y
            ,
            u
          
        
        
        
          
            1
            2
          
        
        ‖
        y
        
          
            
              y
              ^
            
          
        
        
          ‖
          
            
              L
              
                2
              
            
            Ω
          
          
            2
          
        
        
          
            β
            2
          
        
        ‖
        u
        
          ‖
          
            
              L
              
                2
              
            
            Ω
          
          
            2
          
        
        ,
        
        
          s.t.
        
        
        
          
            D
          
        
        y
        u
      
    
    
  
where 
  
    
      
        u
      
    
    
  
 is the control variable and 
  
    
      
        ‖
        ⋅
        
          ‖
          
            
              L
              
                2
              
            
            Ω
          
          
            2
          
        
      
    
    
  
 is the squared Euclidean norm and is not a norm itself. Closed-form solutions are generally unavailable for PDE-constrained optimization problems, necessitating the development of numerical methods.

## Related

- [[Hydrological optimization]]
- [[Optimal control]]
- [[Shape optimization]]
- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/PDE-constrained_optimization