---
title: "Sphere function"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Sphere_function"
wikipedia_categories: ["Applied mathematics stubs", "Mathematical optimization", "Operations research", "Test functions for optimization"]
related: ["[[Bilinear program]]", "[[Binary constraint]]", "[[Continuous optimization]]", "[[Highly optimized tolerance]]", "[[Highway network optimization]]", "[[Knee of a curve]]", "[[Liner shipping network design and scheduling problem]]", "[[Mathematical optimization]]", "[[Mathematical programming with equilibrium constraints]]", "[[Mean field annealing]]"]
---

# Sphere function

In mathematical optimization, the sphere function is a convex function used as a performance test problem for optimization algorithms. The sphere function was proposed by Kenneth A. De Jong in 1975 as the first item of a series of computational test sets. Because of this, the sphere function is also collectively referred to as De Jong's function or De Jong's first function.
On a 
  
    
      
        n
      
    
    
  
-dimensional domain it is defined by

  
    
      
        f
        (
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
        )
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          x
          
            i
          
          
            2
          
        
        .
      
    
    
  

The function is typically evaluated on the domain 
  
    
      
        
          x
          
            i
          
        
        ∈
        −
        5.12
        ,
        5.12
      
    
    
  
 for all 
  
    
      
        1
        ≤
        i
        ≤
        n
      
    
    
  
.
It has a global minimum of zero at 
  
    
      
        
          x
          
            i
          
        
        0.
      
    
    
  
 It is a separable function; that is, it can be expressed as a product of functions in one variable.
The sphere function is used as a benchmark problem to measure algorithms' precision, convergence rate, and robustness, specifically over how well the algorithm handles the function's smooth nature. Several variants of the sphere function are also used, including the Rastrigin function.

## Related

- [[Bilinear program]]
- [[Binary constraint]]
- [[Continuous optimization]]
- [[Highly optimized tolerance]]
- [[Highway network optimization]]
- [[Knee of a curve]]
- [[Liner shipping network design and scheduling problem]]
- [[Mathematical optimization]]
- [[Mathematical programming with equilibrium constraints]]
- [[Mean field annealing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sphere_function