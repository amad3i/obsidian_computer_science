---
title: "Jenkins–Traub algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Jenkins–Traub_algorithm"
wikipedia_categories: ["Numerical analysis", "Polynomial factorization algorithms"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Jenkins–Traub algorithm

The Jenkins–Traub algorithm for polynomial zeros is a fast globally convergent iterative polynomial root-finding method published in 1970 by Michael A. Jenkins and Joseph F. Traub. They gave two variants, one for general polynomials with complex coefficients, commonly known as the "CPOLY" algorithm, and a more complicated variant for the special case of polynomials with real coefficients, commonly known as the "RPOLY" algorithm. The latter is "practically a standard in black-box polynomial root-finders".
This article describes the complex variant. Given a polynomial P,

  
    
      
        P
        z
        =
        
          ∑
          
            i
            0
          
          
            n
          
        
        
          a
          
            i
          
        
        
          z
          
            n
            i
          
        
        ,
        
        
          a
          
            0
          
        
        1
        ,
        
        
          a
          
            n
          
        
        ≠
        0
      
    
    
  

with complex coefficients it computes approximations to the n zeros 
  
    
      
        
          α
          
            1
          
        
        ,
        
          α
          
            2
          
        
        ,
        …
        ,
        
          α
          
            n
          
        
      
    
    
  
 of P(z), one at a time in roughly increasing order of magnitude. After each root is computed, its linear factor is removed from the polynomial. Using this deflation guarantees that each root is computed only once and that all roots are found.
The real variant follows the same pattern, but computes two roots at a time, either two real roots or a pair of conjugate complex roots. By avoiding complex arithmetic, the real variant can be faster (by a factor of 4) than the complex variant. The Jenkins–Traub algorithm has stimulated considerable research on theory and software for methods of this type.

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

- Wikipedia: https://en.wikipedia.org/wiki/Jenkins–Traub_algorithm