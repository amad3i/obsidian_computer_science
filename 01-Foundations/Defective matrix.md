---
title: "Defective matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Defective_matrix"
wikipedia_categories: ["Linear algebra", "Matrices (mathematics)"]
related: ["[[Centrosymmetric matrix]]", "[[Commutation matrix]]", "[[Conformable matrix]]", "[[Conjugate transpose]]", "[[Idempotent matrix]]", "[[Invertible matrix]]", "[[Kernel (linear algebra)]]", "[[Matrix analysis]]", "[[Matrix congruence]]", "[[Matrix difference equation]]"]
---

# Defective matrix

In linear algebra, a defective matrix is a square matrix that does not have a complete basis of eigenvectors, and is therefore not diagonalizable. In particular, an 
  
    
      
        n
        n
      
    
    
  
 matrix is defective if and only if it does not have 
  
    
      
        n
      
    
    
  
 linearly independent eigenvectors. A complete basis is formed by augmenting the eigenvectors with generalized eigenvectors, which are necessary for solving defective systems of ordinary differential equations and other problems.
An 
  
    
      
        n
        n
      
    
    
  
 defective matrix always has fewer than 
  
    
      
        n
      
    
    
  
 distinct eigenvalues, since distinct eigenvalues always have linearly independent eigenvectors. In particular, a defective matrix has one or more eigenvalues 
  
    
      
        λ
      
    
    
  
 with algebraic multiplicity 
  
    
      
        m
        1
      
    
    
  
 (that is, they are multiple roots of the characteristic polynomial), but fewer than 
  
    
      
        m
      
    
    
  
 linearly independent eigenvectors associated with 
  
    
      
        λ
      
    
    
  
. If the algebraic multiplicity of 
  
    
      
        λ
      
    
    
  
 exceeds its geometric multiplicity (that is, the number of linearly independent eigenvectors associated with 
  
    
      
        λ
      
    
    
  
), then 
  
    
      
        λ
      
    
    
  
 is said to be a defective eigenvalue. However, every eigenvalue with algebraic multiplicity 
  
    
      
        m
      
    
    
  
 always has 
  
    
      
        m
      
    
    
  
 linearly independent generalized eigenvectors.
A real symmetric matrix and more generally a Hermitian matrix, and a unitary matrix, is never defective; more generally, a normal matrix (which includes Hermitian and unitary matrices as special cases) is never defective.

## Related

- [[Centrosymmetric matrix]]
- [[Commutation matrix]]
- [[Conformable matrix]]
- [[Conjugate transpose]]
- [[Idempotent matrix]]
- [[Invertible matrix]]
- [[Kernel (linear algebra)]]
- [[Matrix analysis]]
- [[Matrix congruence]]
- [[Matrix difference equation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Defective_matrix