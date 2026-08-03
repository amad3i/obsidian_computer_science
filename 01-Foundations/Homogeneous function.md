---
title: "Homogeneous function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Homogeneous_function"
wikipedia_categories: ["Differential operators", "Leonhard Euler", "Linear algebra", "Types of functions"]
related: ["[[Antilinear map]]", "[[Basis function]]", "[[Graded structure]]", "[[Sublinear function]]", "[[Vector-valued function]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Almost periodic function]]"]
---

# Homogeneous function

In mathematics, a homogeneous function is a function of several variables such that the following holds: If each of the function's arguments is multiplied by the same scalar, then the function's value is multiplied by some power of this scalar; the power is called the degree of homogeneity, or simply the degree. That is, if k is an integer, a function f of n variables is homogeneous of degree k if

  
    
      
        f
        s
        
          x
          
            1
          
        
        ,
        …
        ,
        s
        
          x
          
            n
          
        
        =
        
          s
          
            k
          
        
        f
        
          x
          
            1
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
      
    
    
  

for every 
  
    
      
        
          x
          
            1
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
        ,
      
    
    
  
 and 
  
    
      
        s
        ≠
        0.
      
    
    
  
 This is also referred to a kth-degree or kth-order homogeneous function.
For example, a homogeneous polynomial of degree k defines a homogeneous function of degree k.
The above definition extends to functions whose domain and codomain are vector spaces over a field F: a function 
  
    
      
        f
        :
        V
        →
        W
      
    
    
  
 between two F-vector spaces is homogeneous of degree 
  
    
      
        k
      
    
    
  
 if

for all nonzero 
  
    
      
        s
        ∈
        F
      
    
    
  
 and 
  
    
      
        v
        ∈
        V
        .
      
    
    
  
 This definition is often further generalized to functions whose domain is not V, but a cone in V, that is, a subset C of V such that 
  
    
      
        
          v
        
        ∈
        C
      
    
    
  
 implies 
  
    
      
        s
        
          v
        
        ∈
        C
      
    
    
  
 for every nonzero scalar s.
In the case of functions of several real variables and real vector spaces, a slightly more general form of homogeneity called positive homogeneity is often considered, by requiring only that the above identities hold for 
  
    
      
        s
        0
        ,
      
    
    
  
 and allowing any real number k as a degree of homogeneity. Every homogeneous real function is positively homogeneous. The converse is not true, but is locally true in the sense that (for integer degrees) the two kinds of homogeneity cannot be distinguished by considering the behavior of a function near a given point.
A norm over a real vector space is an example of a positively homogeneous function that is not homogeneous. A special case is the absolute value of real numbers. The quotient of two homogeneous polynomials of the same degree gives an example of a homogeneous function of degree zero. This example is fundamental in the definition of projective schemes.

## Related

- [[Antilinear map]]
- [[Basis function]]
- [[Graded structure]]
- [[Sublinear function]]
- [[Vector-valued function]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Almost periodic function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Homogeneous_function