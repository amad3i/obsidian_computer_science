---
title: "Bartels–Stewart algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bartels–Stewart_algorithm"
wikipedia_categories: ["Algorithms", "Control theory", "Matrices (mathematics)", "Numerical linear algebra"]
related: ["[[Birkhoff algorithm]]", "[[Cross Gramian]]", "[[Hall circles]]", "[[Kernel (linear algebra)]]", "[[Least-squares spectral analysis]]", "[[Rosenbrock system matrix]]", "[[Sylvester equation]]", "[[Transfer function matrix]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]"]
---

# Bartels–Stewart algorithm

In numerical linear algebra, the Bartels–Stewart algorithm is used to numerically solve the Sylvester matrix equation 
  
    
      
        A
        X
        X
        B
        C
      
    
    
  
. Developed by R.H. Bartels and G.W. Stewart in 1971, it was the first numerically stable method that could be systematically applied to solve such equations. The algorithm works by using the real Schur decompositions of 
  
    
      
        A
      
    
    
  
 and 
  
    
      
        B
      
    
    
  
 to transform 
  
    
      
        A
        X
        X
        B
        C
      
    
    
  
 into a triangular system that can then be solved using forward or backward substitution. In 1979, G. Golub, C. Van Loan and S. Nash introduced an improved version of the algorithm, known as the Hessenberg–Schur algorithm. It remains a standard approach for solving  Sylvester equations when 
  
    
      
        X
      
    
    
  
 is of small to moderate size.

## Related

- [[Birkhoff algorithm]]
- [[Cross Gramian]]
- [[Hall circles]]
- [[Kernel (linear algebra)]]
- [[Least-squares spectral analysis]]
- [[Rosenbrock system matrix]]
- [[Sylvester equation]]
- [[Transfer function matrix]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bartels–Stewart_algorithm