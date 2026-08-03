---
title: "Orthogonal transformation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Orthogonal_transformation"
wikipedia_categories: ["Linear algebra"]
related: ["[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]", "[[Antiunitary operator]]", "[[Asymmetric norm]]"]
---

# Orthogonal transformation

In linear algebra, an orthogonal transformation is a linear transformation T : V → V on a real inner product space V, that preserves the inner product. That is, for each pair u, v of elements of V, we have

  
    
      
        ⟨
        u
        ,
        v
        ⟩
        ⟨
        T
        u
        ,
        T
        v
        ⟩
        
        .
      
    
    
  

Since the lengths of vectors and the angles between them are defined through the inner product, orthogonal transformations preserve lengths of vectors and angles between them. In particular, orthogonal transformations map orthonormal bases to orthonormal bases.
Orthogonal transformations are injective: if 
  
    
      
        T
        v
        0
      
    
    
  
 then 
  
    
      
        0
        ⟨
        T
        v
        ,
        T
        v
        ⟩
        ⟨
        v
        ,
        v
        ⟩
      
    
    
  
, hence 
  
    
      
        v
        0
      
    
    
  
, so the kernel of 
  
    
      
        T
      
    
    
  
 is trivial.
Orthogonal transformations in two- or three-dimensional Euclidean space are stiff rotations, reflections, or combinations of a rotation and a reflection (also known as improper rotations). Reflections are transformations that reverse the direction front to back, orthogonal to the mirror plane, like (real-world) mirrors do. The matrices corresponding to proper rotations (without reflection) have a determinant of +1. Transformations with reflection are represented by matrices with a determinant of −1. This allows the concept of rotation and reflection to be generalized to higher dimensions.
In finite-dimensional spaces, the matrix representation (with respect to an orthonormal basis) of an orthogonal transformation is an orthogonal matrix. Its rows are mutually orthogonal vectors with unit norm, so that the rows constitute an orthonormal basis of V. The columns of the matrix form another orthonormal basis of V.
If an orthogonal transformation is invertible (which is always the case when V is finite-dimensional) then its inverse 
  
    
      
        
          T
          
            1
          
        
      
    
    
  
 is another orthogonal transformation identical to the transpose or adjoint of 
  
    
      
        T
      
    
    
  
: 
  
    
      
        
          T
          
            1
          
        
        
          T
          
            
              T
            
          
        
      
    
    
  
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

- Wikipedia: https://en.wikipedia.org/wiki/Orthogonal_transformation