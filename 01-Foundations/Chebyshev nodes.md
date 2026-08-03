---
title: "Chebyshev nodes"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Chebyshev_nodes"
wikipedia_categories: ["Algebraic numbers", "Numerical analysis"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Chebyshev nodes

In numerical analysis, Chebyshev nodes (also called Chebyshev points or a Chebyshev grid) are a set of specific algebraic numbers used as nodes for polynomial interpolation and numerical integration. They are the projection of a set of equispaced points on the unit circle onto the real interval 
  
    
      
        −
        1
        ,
        1
      
    
    
  
, the circle's diameter.
There are two kinds of Chebyshev nodes. The ⁠
  
    
      
        n
      
    
    
  
⁠ Chebyshev nodes of the first kind, also called the Chebyshev–Gauss nodes or Chebyshev zeros, are the zeros of a Chebyshev polynomial of the first kind, ⁠
  
    
      
        
          T
          
            n
          
        
      
    
    
  
⁠. The corresponding ⁠
  
    
      
        n
        1
      
    
    
  
⁠ Chebyshev nodes of the second kind, also called the Chebyshev–Lobatto nodes or Chebyshev extrema, are the extrema of ⁠
  
    
      
        
          T
          
            n
          
        
      
    
    
  
⁠, which are also the zeros of a Chebyshev polynomial of the second kind, ⁠
  
    
      
        
          U
          
            n
            1
          
        
      
    
    
  
⁠, along with the two endpoints of the interval. Both types of numbers are commonly referred to as Chebyshev nodes or Chebyshev points in literature. They are named after 19th century Russian mathematician Pafnuty Chebyshev, who first introduced Chebyshev polynomials.
Unlike some other interpolation nodes, the Chebyshev nodes "nest": the existing nodes are retained when doubling the number of nodes, reducing computation for each grid refinement by half. Polynomial interpolants constructed from Chebyshev nodes minimize the effect of Runge's phenomenon. They can be easily converted to a representation as a weighted sum of Chebyshev polynomials using the fast Fourier transform.

## Related

- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]
- [[Arc-length method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Chebyshev_nodes