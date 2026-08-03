---
title: "Rayleigh quotient"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rayleigh_quotient"
wikipedia_categories: ["Linear algebra"]
related: ["[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]", "[[Antiunitary operator]]", "[[Asymmetric norm]]"]
---

# Rayleigh quotient

In mathematics, the Rayleigh quotient () for a given complex Hermitian matrix 
  
    
      
        M
      
    
    
  
 and nonzero vector 
  
    
      
        x
      
    
    
  
 is defined as:
  
    
      
        R
        M
        ,
        x
        =
        
          
            
              
                x
                
                
              
              M
              x
            
            
              
                x
                
                
              
              x
            
          
        
        .
      
    
    
  
For real matrices and vectors, the condition of being Hermitian reduces to that of being symmetric, and the conjugate transpose 
  
    
      
        
          x
          
          
        
      
    
    
  
 to the usual transpose 
  
    
      
        
          x
          ′
        
      
    
    
  
. Note that 
  
    
      
        R
        M
        ,
        c
        x
        =
        R
        M
        ,
        x
      
    
    
  
 for any non-zero scalar 
  
    
      
        c
      
    
    
  
. Recall that a Hermitian (or real symmetric) matrix is diagonalizable with only real eigenvalues. It can be shown that, for a given matrix, the Rayleigh quotient reaches its minimum value 
  
    
      
        
          λ
          
            min
          
        
      
    
    
  
 (the smallest eigenvalue of 
  
    
      
        M
      
    
    
  
) when 
  
    
      
        x
      
    
    
  
 is 
  
    
      
        
          v
          
            min
          
        
      
    
    
  
 (the corresponding eigenvector). Similarly, 
  
    
      
        R
        M
        ,
        x
        ≤
        
          λ
          
            max
          
        
      
    
    
  
 and 
  
    
      
        R
        M
        ,
        
          v
          
            max
          
        
        =
        
          λ
          
            max
          
        
      
    
    
  
.
The Rayleigh quotient is used in the min-max theorem to get exact values of all eigenvalues. It is also used in eigenvalue algorithms (such as Rayleigh quotient iteration) to obtain an eigenvalue approximation from an eigenvector approximation.
The range of the Rayleigh quotient (for any matrix, not necessarily Hermitian) is called a numerical range and contains its spectrum. When the matrix is Hermitian, the numerical radius is equal to the spectral norm. Still in functional analysis, 
  
    
      
        
          λ
          
            max
          
        
      
    
    
  
 is known as the spectral radius. In the context of 
  
    
      
        
          C
          
            ⋆
          
        
      
    
    
  
-algebras or algebraic quantum mechanics, the function that to 
  
    
      
        M
      
    
    
  
 associates the Rayleigh–Ritz quotient  
  
    
      
        R
        M
        ,
        x
      
    
    
  
 for a fixed 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        M
      
    
    
  
 varying through the algebra would be referred to as vector state of the algebra.
In quantum mechanics, the Rayleigh quotient gives the expectation value of the observable corresponding to the operator 
  
    
      
        M
      
    
    
  
 for a system whose state is given by 
  
    
      
        x
      
    
    
  
.
If we fix the complex matrix 
  
    
      
        M
      
    
    
  
, then the resulting Rayleigh quotient map (considered as a function of 
  
    
      
        x
      
    
    
  
) completely determines 
  
    
      
        M
      
    
    
  
 via the polarization identity; indeed, this remains true even if we allow 
  
    
      
        M
      
    
    
  
 to be non-Hermitian. However, if we restrict the field of scalars to the real numbers, then the Rayleigh quotient only determines the symmetric part of 
  
    
      
        M
      
    
    
  
.

## Related

- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]
- [[Antilinear map]]
- [[Antiunitary operator]]
- [[Asymmetric norm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rayleigh_quotient