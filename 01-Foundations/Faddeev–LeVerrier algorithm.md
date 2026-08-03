---
title: "Faddeev–LeVerrier algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Faddeev–LeVerrier_algorithm"
wikipedia_categories: ["Determinants", "Homogeneous polynomials", "Linear algebra", "Mathematical physics", "Matrix theory", "Polynomials"]
related: ["[[Determinant]]", "[[Annihilating polynomial]]", "[[Eigenvalues and eigenvectors]]", "[[Invertible matrix]]", "[[Adjugate matrix]]", "[[Amitsur–Levitzki theorem]]", "[[Bendixson's inequality]]", "[[Change of basis]]", "[[Characteristic polynomial]]", "[[Computing the permanent]]"]
---

# Faddeev–LeVerrier algorithm

In mathematics (linear algebra), the Faddeev–LeVerrier algorithm is a recursive method to calculate the coefficients of the  characteristic polynomial 
  
    
      
        
          p
          
            A
          
        
        λ
        =
        det
        λ
        
          I
          
            n
          
        
        A
      
    
    
  
 of a square matrix, A, named after Dmitry Konstantinovich Faddeev and Urbain Le Verrier. Calculation of this polynomial yields the eigenvalues of A as its roots; as a matrix polynomial in the matrix A itself, it vanishes by the Cayley–Hamilton theorem. Computing the characteristic polynomial directly from the definition of the determinant is computationally cumbersome insofar as it introduces a new symbolic quantity 
  
    
      
        λ
      
    
    
  
; by contrast, the Faddeev-Le Verrier algorithm works directly with coefficients of matrix 
  
    
      
        A
      
    
    
  
.
The algorithm has been independently rediscovered several times in different forms. It was first published in 1840 by Urbain Le Verrier, subsequently redeveloped by P. Horst, Jean-Marie Souriau, in its present form here by Faddeev and Sominsky, and further by  J. S. Frame, and others. (For historical points, see Householder. An elegant shortcut to the proof, bypassing Newton polynomials, was introduced by Hou. The bulk of the presentation here follows Gantmacher, p. 88.)

## Related

- [[Determinant]]
- [[Annihilating polynomial]]
- [[Eigenvalues and eigenvectors]]
- [[Invertible matrix]]
- [[Adjugate matrix]]
- [[Amitsur–Levitzki theorem]]
- [[Bendixson's inequality]]
- [[Change of basis]]
- [[Characteristic polynomial]]
- [[Computing the permanent]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Faddeev–LeVerrier_algorithm