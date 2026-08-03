---
title: "Commutation matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Commutation_matrix"
wikipedia_categories: ["Linear algebra", "Matrices (mathematics)"]
related: ["[[Centrosymmetric matrix]]", "[[Conformable matrix]]", "[[Conjugate transpose]]", "[[Defective matrix]]", "[[Idempotent matrix]]", "[[Invertible matrix]]", "[[Kernel (linear algebra)]]", "[[Matrix analysis]]", "[[Matrix congruence]]", "[[Matrix difference equation]]"]
---

# Commutation matrix

In mathematics, especially in linear algebra and matrix theory, the commutation matrix is used for transforming the vectorized form of a matrix into the vectorized form of its transpose. Specifically, the commutation matrix K(m,n) is the nm × mn permutation matrix which, for any m × n matrix A, transforms vec(A) into vec(AT):

K(m,n) vec(A) = vec(AT) .
Here vec(A) is the mn × 1 column vector obtain by stacking the columns of A on top of one another:

  
    
      
        vec
         
        
          A
        
        =
        
          
            A
          
          
            1
            ,
            1
          
        
        ,
        …
        ,
        
          
            A
          
          
            m
            ,
            1
          
        
        ,
        
          
            A
          
          
            1
            ,
            2
          
        
        ,
        …
        ,
        
          
            A
          
          
            m
            ,
            2
          
        
        ,
        …
        ,
        
          
            A
          
          
            1
            ,
            n
          
        
        ,
        …
        ,
        
          
            A
          
          
            m
            ,
            n
          
        
        
          
            
              T
            
          
        
      
    
    
  

where A = [Ai,j]. In other words, vec(A) is the vector obtained by vectorizing A in column-major order. Similarly, vec(AT) is the vector obtaining by vectorizing A in row-major order.  The cycles and other properties of this permutation have been heavily studied for in-place matrix transposition algorithms.
In the context of quantum information theory, the commutation matrix is sometimes referred to as the swap matrix or swap operator

## Related

- [[Centrosymmetric matrix]]
- [[Conformable matrix]]
- [[Conjugate transpose]]
- [[Defective matrix]]
- [[Idempotent matrix]]
- [[Invertible matrix]]
- [[Kernel (linear algebra)]]
- [[Matrix analysis]]
- [[Matrix congruence]]
- [[Matrix difference equation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Commutation_matrix