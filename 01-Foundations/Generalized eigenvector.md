---
title: "Generalized eigenvector"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Generalized_eigenvector"
wikipedia_categories: ["Linear algebra", "Matrix theory"]
related: ["[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Change of basis]]", "[[Computing the permanent]]", "[[Determinant]]", "[[Eigenoperator]]", "[[Eigenvalues and eigenvectors]]", "[[Faddeev–LeVerrier algorithm]]"]
---

# Generalized eigenvector

In linear algebra, a generalized eigenvector of an 
  
    
      
        n
        n
      
    
    
  
 matrix 
  
    
      
        A
      
    
    
  
 is a vector which satisfies certain criteria which are more relaxed than those for an (ordinary) eigenvector.
Let 
  
    
      
        V
      
    
    
  
 be an 
  
    
      
        n
      
    
    
  
-dimensional vector space and let 
  
    
      
        A
      
    
    
  
 be the matrix representation of a linear map from 
  
    
      
        V
      
    
    
  
 to 
  
    
      
        V
      
    
    
  
 with respect to some ordered basis.
There may not always exist a full set of 
  
    
      
        n
      
    
    
  
 linearly independent eigenvectors of 
  
    
      
        A
      
    
    
  
 that form a complete basis for 
  
    
      
        V
      
    
    
  
.  That is, the matrix 
  
    
      
        A
      
    
    
  
 may not be diagonalizable.  This happens when the algebraic multiplicity of at least one eigenvalue 
  
    
      
        
          λ
          
            i
          
        
      
    
    
  
 is greater than its geometric multiplicity (the nullity of the matrix 
  
    
      
        A
        
          λ
          
            i
          
        
        I
      
    
    
  
, or the dimension of its nullspace).  In this case, 
  
    
      
        
          λ
          
            i
          
        
      
    
    
  
 is called a defective eigenvalue and 
  
    
      
        A
      
    
    
  
 is called a defective matrix.
A generalized eigenvector 
  
    
      
        
          x
          
            i
          
        
      
    
    
  
 corresponding to 
  
    
      
        
          λ
          
            i
          
        
      
    
    
  
, together with the matrix 
  
    
      
        A
        
          λ
          
            i
          
        
        I
      
    
    
  
 generate a Jordan chain of linearly independent generalized eigenvectors which form a basis for an invariant subspace of 
  
    
      
        V
      
    
    
  
.
Using generalized eigenvectors, a set of linearly independent eigenvectors of 
  
    
      
        A
      
    
    
  
 can be extended, if necessary, to a complete basis for 
  
    
      
        V
      
    
    
  
.  This basis can be used to determine an "almost diagonal matrix" 
  
    
      
        J
      
    
    
  
 in Jordan normal form, similar to 
  
    
      
        A
      
    
    
  
, which is useful in computing certain matrix functions of 
  
    
      
        A
      
    
    
  
.  The matrix 
  
    
      
        J
      
    
    
  
 is also useful in solving the system of linear differential equations 
  
    
      
        
          
            x
          
          ′
        
        A
        
          x
        
        ,
      
    
    
  
 where 
  
    
      
        A
      
    
    
  
 need not be diagonalizable.
The dimension of the generalized eigenspace corresponding to a given eigenvalue 
  
    
      
        λ
      
    
    
  
 is the algebraic multiplicity of 
  
    
      
        λ
      
    
    
  
.

## Related

- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Change of basis]]
- [[Computing the permanent]]
- [[Determinant]]
- [[Eigenoperator]]
- [[Eigenvalues and eigenvectors]]
- [[Faddeev–LeVerrier algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Generalized_eigenvector