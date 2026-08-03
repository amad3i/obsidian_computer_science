---
title: "Orthonormal basis"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Orthonormal_basis"
wikipedia_categories: ["Fourier analysis", "Functional analysis", "Linear algebra"]
related: ["[[Antiunitary operator]]", "[[Basis function]]", "[[Convolution]]", "[[Cyclical monotonicity]]", "[[Dual norm]]", "[[Dual space]]", "[[Gap metric]]", "[[Gram–Schmidt process]]", "[[Hilbert space]]", "[[Kernel (linear algebra)]]"]
---

# Orthonormal basis

In mathematics, particularly linear algebra, an orthonormal basis for an inner product space 
  
    
      
        V
      
    
    
  
 with finite dimension is a basis for 
  
    
      
        V
      
    
    
  
 whose vectors are orthonormal, that is, they are all unit vectors and orthogonal to each other. For example, the standard basis for a Euclidean space 
  
    
      
        
          
            R
          
          
            n
          
        
      
    
    
  
 is an orthonormal basis, where the relevant inner product is the dot product of vectors. The image of the standard basis under a rotation or reflection (or any orthogonal transformation) is also orthonormal, and every orthonormal basis for 
  
    
      
        
          
            R
          
          
            n
          
        
      
    
    
  
 arises in this fashion.
An orthonormal basis can be derived from an orthogonal basis via normalization.
The choice of an origin and an orthonormal basis forms a coordinate frame known as an orthonormal frame.
For a general inner product space 
  
    
      
        V
        ,
      
    
    
  
 an orthonormal basis can be used to define normalized orthogonal coordinates on 
  
    
      
        V
        .
      
    
    
  
 Under these coordinates, the inner product becomes a dot product of vectors. Thus the presence of an orthonormal basis reduces the study of a finite-dimensional inner product space to the study of 
  
    
      
        
          
            R
          
          
            n
          
        
      
    
    
  
 under the dot product. Every finite-dimensional inner product space has an orthonormal basis, which may be obtained from an arbitrary basis using the Gram–Schmidt process.
In functional analysis, the concept of an orthonormal basis can be generalized to arbitrary (infinite-dimensional) inner product spaces. Given a pre-Hilbert space 
  
    
      
        H
        ,
      
    
    
  
 an orthonormal basis for 
  
    
      
        H
      
    
    
  
 is an orthonormal set of vectors with the property that every vector in 
  
    
      
        H
      
    
    
  
 can be written as an infinite linear combination of the vectors in the basis. In this case, the orthonormal basis is sometimes called a Hilbert basis for 
  
    
      
        H
        .
      
    
    
  
 Note that an orthonormal basis in this sense is not generally a Hamel basis, since infinite linear combinations are required. Specifically, the linear span of the basis must be dense in 
  
    
      
        H
        ,
      
    
    
  
 although not necessarily the entire space.
If we go on to Hilbert spaces, a non-orthonormal set of vectors having the same linear span as an orthonormal basis may not be a basis at all. For instance, any square-integrable function on the interval 
  
    
      
        −
        1
        ,
        1
      
    
    
  
 can be expressed (almost everywhere) as an infinite sum of Legendre polynomials (an orthonormal basis), but not necessarily as an infinite sum of the monomials 
  
    
      
        
          x
          
            n
          
        
        .
      
    
    
  

A different generalisation is to pseudo-inner product spaces, finite-dimensional vector spaces 
  
    
      
        M
      
    
    
  
 equipped with a non-degenerate symmetric bilinear form known as the metric tensor. In such a basis, the metric takes the form 
  
    
      
        
          diag
        
        +
        1
        ,
        ⋯
        ,
        1
        ,
        1
        ,
        ⋯
        ,
        1
      
    
    
  
 with 
  
    
      
        p
      
    
    
  
 positive ones and 
  
    
      
        q
      
    
    
  
 negative ones.

## Related

- [[Antiunitary operator]]
- [[Basis function]]
- [[Convolution]]
- [[Cyclical monotonicity]]
- [[Dual norm]]
- [[Dual space]]
- [[Gap metric]]
- [[Gram–Schmidt process]]
- [[Hilbert space]]
- [[Kernel (linear algebra)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Orthonormal_basis