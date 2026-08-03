---
title: "Iterative method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Iterative_method"
wikipedia_categories: ["Iterative methods", "Numerical analysis"]
related: ["[[Discretization]]", "[[Least-squares spectral analysis]]", "[[Local convergence]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]"]
---

# Iterative method

In computational mathematics, an iterative method is a mathematical procedure that uses an initial value to generate a sequence of improving approximate solutions for a class of problems, in which the i-th approximation (called an "iterate") is derived from the previous ones.
A specific implementation with termination criteria for a given iterative method like gradient descent, hill climbing, Newton's method, or quasi-Newton methods like BFGS, is an algorithm of an iterative method or a method of successive approximation. An iterative method is called convergent if the corresponding sequence converges for given initial approximations. A mathematically rigorous convergence analysis of an iterative method is usually performed; however, heuristic-based iterative methods are also common.
In contrast, direct methods attempt to solve the problem by a finite sequence of operations. In the absence of rounding errors, direct methods would deliver an exact solution (for example, solving a linear system of equations 
  
    
      
        A
        
          x
        
        
          b
        
      
    
    
  
 by Gaussian elimination). Iterative methods are often the only choice for nonlinear equations. However, iterative methods are often useful even for linear problems involving many variables (sometimes on the order of millions), where direct methods would be prohibitively expensive (and in some cases impossible) even with the best available computing power.

## Related

- [[Discretization]]
- [[Least-squares spectral analysis]]
- [[Local convergence]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Iterative_method