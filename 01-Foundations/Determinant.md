---
title: "Determinant"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Determinant"
wikipedia_categories: ["Determinants", "Homogeneous polynomials", "Linear algebra", "Matrix theory"]
related: ["[[Faddeev–LeVerrier algorithm]]", "[[Invertible matrix]]", "[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Annihilating polynomial]]", "[[Bendixson's inequality]]", "[[Change of basis]]", "[[Computing the permanent]]", "[[Dieudonné determinant]]", "[[Eigenoperator]]"]
---

# Determinant

In mathematics, the determinant is a scalar-valued function of the entries of a square matrix. The determinant of a matrix A is commonly denoted det(A), det A, or |A|. Its value characterizes some properties of the matrix and the linear map represented, on a given basis, by the matrix. In particular, the determinant is nonzero if and only if the matrix is invertible and the corresponding linear map is an isomorphism. However, if the determinant is zero, the matrix is referred to as singular, meaning it does not have an inverse.
The determinant is completely determined by the two following properties: the determinant of a product of matrices is the product of their determinants, and the determinant of a triangular matrix is the product of its diagonal entries.
The determinant of a 2 × 2 matrix is

  
    
      
        
          
            |
            
              
                
                  a
                
                
                  b
                
              
              
                
                  c
                
                
                  d
                
              
            
            |
          
        
        a
        d
        b
        c
        ,
      
    
    
  

and the determinant of a 3 × 3 matrix is

  
    
      
        
          
            |
            
              
                
                  a
                
                
                  b
                
                
                  c
                
              
              
                
                  d
                
                
                  e
                
                
                  f
                
              
              
                
                  g
                
                
                  h
                
                
                  i
                
              
            
            |
          
        
        a
        e
        i
        b
        f
        g
        c
        d
        h
        c
        e
        g
        b
        d
        i
        a
        f
        h
        .
      
    
    
  

The determinant of an n × n matrix can be defined in several equivalent ways, the most common being the Leibniz formula, which expresses the determinant as a sum of 
  
    
      
        n
        !
      
    
    
  
 (the factorial of n) signed products of matrix entries. It can be computed by the Laplace expansion, which expresses the determinant as a linear combination of determinants of submatrices, or with Gaussian elimination, which allows computing a row echelon form with the same determinant, equal to the product of the diagonal entries of the row echelon form.
Determinants can also be defined by some of their properties. Namely, the determinant is the unique function defined on the n × n matrices that has the four following properties: 

The determinant of the identity matrix is 1.
The exchange of two rows multiplies the determinant by −1.
Multiplying a row by a number multiplies the determinant by this number.
Adding a multiple of one row to another row does not change the determinant.
The above properties relating to rows (properties 2–4) may be replaced by the corresponding statements with respect to columns.
The determinant is invariant under matrix similarity. This implies that, given a linear endomorphism of a finite-dimensional vector space, the determinant of the matrix that represents it on a basis does not depend on the chosen basis. This allows defining the determinant of a linear endomorphism, which does not depend on the choice of a coordinate system. For endomorphisms of real vector spaces, the value of the determinant is the scale factor by which the endomorphism alters any volume in the space (positive if the orientation is preserved, negative if the orientation is reversed). This is used in calculus with exterior differential forms and the Jacobian determinant, in particular for changes of variables in multiple integrals.
Determinants occur throughout mathematics. For example, a matrix is often used to represent the coefficients in a system of linear equations, and determinants can be used to solve these equations (Cramer's rule), although other methods of solution are computationally much more efficient. Determinants are used for defining the characteristic polynomial of a square matrix, whose roots are the eigenvalues.

## Related

- [[Faddeev–LeVerrier algorithm]]
- [[Invertible matrix]]
- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Annihilating polynomial]]
- [[Bendixson's inequality]]
- [[Change of basis]]
- [[Computing the permanent]]
- [[Dieudonné determinant]]
- [[Eigenoperator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Determinant