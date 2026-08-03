---
title: "Bidiagonal matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bidiagonal_matrix"
wikipedia_categories: ["Computer programming stubs", "Linear algebra", "Matrix stubs", "Sparse matrices"]
related: ["[[Conformable matrix]]", "[[Eigenoperator]]", "[[Reducing subspace]]", "[[Skew-Hamiltonian matrix]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Adjugate matrix]]", "[[Affine space]]"]
---

# Bidiagonal matrix

In mathematics, a bidiagonal matrix is a banded matrix with non-zero entries along the main diagonal and either the diagonal above or the diagonal below. This means there are exactly two non-zero diagonals in the matrix.
When the diagonal above the main diagonal has the non-zero entries the matrix is upper bidiagonal.  When the diagonal below the main diagonal has the non-zero entries the matrix is lower bidiagonal.
For example, the following matrix is upper bidiagonal:

  
    
      
        
          
            
              
                
                  1
                
                
                  4
                
                
                  0
                
                
                  0
                
              
              
                
                  0
                
                
                  4
                
                
                  1
                
                
                  0
                
              
              
                
                  0
                
                
                  0
                
                
                  3
                
                
                  4
                
              
              
                
                  0
                
                
                  0
                
                
                  0
                
                
                  3
                
              
            
          
        
      
    
    
  

and the following matrix is lower bidiagonal:

  
    
      
        
          
            
              
                
                  1
                
                
                  0
                
                
                  0
                
                
                  0
                
              
              
                
                  2
                
                
                  4
                
                
                  0
                
                
                  0
                
              
              
                
                  0
                
                
                  3
                
                
                  3
                
                
                  0
                
              
              
                
                  0
                
                
                  0
                
                
                  4
                
                
                  3
                
              
            
          
        
        .
      
    
    
  

The eigenvalues of a bidiagonal matrix (of either type) are given by the entries of the diagonal.
For a square bidiagonal matrix B, the determinant is simply the product of its diagonal elements:

  
    
      
        det
        B
        =
        
          ∏
          
            i
            1
          
          
            n
          
        
        
          b
          
            i
            i
          
        
      
    
    
  

Additionally, the inverse of a nonsingular upper bidiagonal matrix B is an upper triangular matrix whose entries can be computed explicitly without solving full systems of linear equations.

## Related

- [[Conformable matrix]]
- [[Eigenoperator]]
- [[Reducing subspace]]
- [[Skew-Hamiltonian matrix]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Adjugate matrix]]
- [[Affine space]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bidiagonal_matrix