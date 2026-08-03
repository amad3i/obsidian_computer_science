---
title: "Sylvester equation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sylvester_equation"
wikipedia_categories: ["Control theory", "Matrices (mathematics)"]
related: ["[[Bartels–Stewart algorithm]]", "[[Cross Gramian]]", "[[Rosenbrock system matrix]]", "[[Transfer function matrix]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]"]
---

# Sylvester equation

In mathematics, in the field of control theory, a Sylvester equation  is a matrix equation of the form:

  
    
      
        A
        X
        X
        B
        C
        .
      
    
    
  

It is named after English mathematician James Joseph Sylvester. Then given matrices A, B, and C, the problem is to find the possible matrices X that obey this equation. All matrices are assumed to have coefficients in the complex numbers. For the equation to make sense, the matrices must have appropriate sizes, for example they could all be square matrices of the same size. But more generally, A and B must be square matrices of sizes n and m respectively, and then X and C both have n rows and m columns.
A Sylvester equation has a unique solution for X exactly when there are no common eigenvalues of A and −B.
More generally, the equation AX + XB = C has been considered as an equation of bounded operators on a (possibly infinite-dimensional) Banach space. In this case, the condition for the uniqueness of a solution X is almost the same: There exists a unique solution X exactly when the spectra of A and −B are disjoint.

## Related

- [[Bartels–Stewart algorithm]]
- [[Cross Gramian]]
- [[Rosenbrock system matrix]]
- [[Transfer function matrix]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sylvester_equation