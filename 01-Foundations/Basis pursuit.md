---
title: "Basis pursuit"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Basis_pursuit"
wikipedia_categories: ["Constraint programming", "Mathematical optimization"]
related: ["[[Binary constraint]]", "[[Constrained optimization]]", "[[Constraint (mathematics)]]", "[[Distributed constraint optimization]]", "[[Algorithm selection]]", "[[Algorithmic problems on convex sets]]", "[[Allen's interval algebra]]", "[[Analysis of Boolean functions]]", "[[Backjumping]]", "[[Backtracking line search]]"]
---

# Basis pursuit

Basis pursuit is the mathematical optimization problem of the form

  
    
      
        
          min
          
            x
          
        
        ‖
        x
        
          ‖
          
            1
          
        
        
        
          subject to
        
        
        y
        A
        x
        ,
      
    
    
  

where x is a N-dimensional solution vector (signal), y is a M-dimensional vector of observations (measurements), A is a M × N transform matrix (usually measurement matrix) and M < N.  The version of basis pursuit that seeks to minimize the L0 norm is NP-hard.
It is usually applied in cases where there is an underdetermined system of linear equations y = Ax that must be exactly satisfied, and the sparsest solution in the L1 sense is desired.
When it is desirable to trade off exact equality of Ax and y in exchange for a sparser x, basis pursuit denoising is preferred.
Basis pursuit problems can be converted to linear programming problems in polynomial time and vice versa, making the two types of problems polynomially equivalent.

## Related

- [[Binary constraint]]
- [[Constrained optimization]]
- [[Constraint (mathematics)]]
- [[Distributed constraint optimization]]
- [[Algorithm selection]]
- [[Algorithmic problems on convex sets]]
- [[Allen's interval algebra]]
- [[Analysis of Boolean functions]]
- [[Backjumping]]
- [[Backtracking line search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Basis_pursuit