---
title: "Singular matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Singular_matrix"
wikipedia_categories: ["Linear algebra", "Matrices (mathematics)"]
related: ["[[Centrosymmetric matrix]]", "[[Commutation matrix]]", "[[Conformable matrix]]", "[[Conjugate transpose]]", "[[Defective matrix]]", "[[Idempotent matrix]]", "[[Invertible matrix]]", "[[Kernel (linear algebra)]]", "[[Matrix analysis]]", "[[Matrix congruence]]"]
---

# Singular matrix

A singular matrix is a square matrix that is not invertible, unlike non-singular matrices which are invertible. Equivalently, an 
  
    
      
        n
      
    
    
  
-by-
  
    
      
        n
      
    
    
  
 matrix 
  
    
      
        A
      
    
    
  
 is singular if and only if determinant, 
  
    
      
        det
        A
        =
        0
      
    
    
  
. In classical linear algebra, a matrix is called non-singular (or invertible) when it has an inverse; by definition, a matrix that fails this criterion is singular. In more algebraic terms, an 
  
    
      
        n
      
    
    
  
-by-
  
    
      
        n
      
    
    
  
 matrix A is singular exactly when its columns (and rows) are linearly dependent, so that the linear map 
  
    
      
        x
        ↦
        A
        x
      
    
    
  
 is not one-to-one.
In this case the kernel (null space) of A is non-trivial (has dimension ≥1), and the homogeneous system 
  
    
      
        A
        x
        0
      
    
    
  
 admits non-zero solutions. These characterizations follow from standard rank-nullity and invertibility theorems: for a square matrix A, 
  
    
      
        det
        A
        ≠
        0
      
    
    
  
 if and only if 
  
    
      
        rank
         
        A
        =
        n
      
    
    
  
, and 
  
    
      
        det
        A
        =
        0
      
    
    
  
 if and only if 
  
    
      
        rank
         
        A
        <
        n
      
    
    
  
.

## Related

- [[Centrosymmetric matrix]]
- [[Commutation matrix]]
- [[Conformable matrix]]
- [[Conjugate transpose]]
- [[Defective matrix]]
- [[Idempotent matrix]]
- [[Invertible matrix]]
- [[Kernel (linear algebra)]]
- [[Matrix analysis]]
- [[Matrix congruence]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Singular_matrix