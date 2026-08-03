---
title: "Nyström method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Nyström_method"
wikipedia_categories: ["Integral equations", "Numerical analysis", "Numerical integration"]
related: ["[[Boole's rule]]", "[[Local linearization method]]", "[[Numerical integration]]", "[[Simpson's rule]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]"]
---

# Nyström method

In mathematics numerical analysis, the Nyström method or quadrature method seeks the numerical solution of an integral equation by replacing the integral with a representative weighted sum.  The continuous problem is broken into 
  
    
      
        n
      
    
    
  
 discrete intervals; quadrature or numerical integration determines the weights and locations of representative points for the integral.
The problem becomes a system of linear equations with 
  
    
      
        n
      
    
    
  
 equations and 
  
    
      
        n
      
    
    
  
 unknowns, and the underlying function is implicitly represented by an interpolation using the chosen quadrature rule.  This discrete problem may be ill-conditioned, depending on the original problem and the chosen quadrature rule. 
Since the linear equations require 
  
    
      
        O
        
          n
          
            3
          
        
      
    
    
  
 operations to solve, high-order quadrature rules perform better because low-order quadrature rules require large 
  
    
      
        n
      
    
    
  
 for a given accuracy.  Gaussian quadrature is normally a good choice for smooth, non-singular problems.

## Related

- [[Boole's rule]]
- [[Local linearization method]]
- [[Numerical integration]]
- [[Simpson's rule]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nyström_method