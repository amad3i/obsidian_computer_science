---
title: "Semilinear map"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Semilinear_map"
wikipedia_categories: ["Functions and mappings", "Linear algebra", "Linear operators", "Projective geometry"]
related: ["[[3D projection]]", "[[Antilinear map]]", "[[Homogeneous coordinates]]", "[[Hyperplane]]", "[[Linear form]]", "[[Locally finite operator]]", "[[Motzkin–Taussky theorem]]", "[[Projection (linear algebra)]]", "[[Projectivization]]", "[[Rotation of axes in two dimensions]]"]
---

# Semilinear map

In linear algebra, particularly projective geometry, a semilinear map between vector spaces V and W over a field K is a function that is a linear map "up to a twist", hence semi-linear, where "twist" means "field automorphism of K". Explicitly, it is a function T : V → W that is:

additive with respect to vector addition: 
  
    
      
        T
        v
        
          v
          ′
        
        =
        T
        v
        +
        T
        
          v
          ′
        
      
    
    
  

there exists a field automorphism θ of K such that 
  
    
      
        T
        λ
        v
        =
        θ
        λ
        T
        v
      
    
    
  
. If such an automorphism exists and T is nonzero, it is unique, and T is called θ-semilinear.
Where the domain and codomain are the same space (i.e. T : V → V), it may be termed a semilinear transformation.  The invertible semilinear transforms of a given vector space V (for all choices of field automorphism) form a group, called the general semilinear group and denoted 
  
    
      
        
          Γ
          L
        
         
        V
        ,
      
    
    
  
 by analogy with and extending the general linear group. The special case where the field is the complex numbers 
  
    
      
        
          C
        
      
    
    
  
 and the automorphism is complex conjugation, a semilinear map is called an antilinear map. 
Similar notation (replacing Latin characters with Greek ones) is used for semilinear analogs of more restricted linear transformations; formally, the semidirect product of a linear group with the Galois group of field automorphisms. For example, PΣU is used for the semilinear analogs of the projective special unitary group PSU.  Note, however, that it was only recently noticed that these generalized semilinear groups are not well-defined, as pointed out in (Bray, Holt & Roney-Dougal 2009) – isomorphic classical groups G and H (subgroups of SL) may have non-isomorphic semilinear extensions. At the level of semidirect products, this corresponds to different actions of the Galois group on a given abstract group, a semidirect product depending on two groups and an action. If the extension is non-unique, there are exactly two semilinear extensions; for example, symplectic groups have a unique semilinear extension, while SU(n, q) has two extensions if n is even and q is odd, and likewise for PSU.

## Related

- [[3D projection]]
- [[Antilinear map]]
- [[Homogeneous coordinates]]
- [[Hyperplane]]
- [[Linear form]]
- [[Locally finite operator]]
- [[Motzkin–Taussky theorem]]
- [[Projection (linear algebra)]]
- [[Projectivization]]
- [[Rotation of axes in two dimensions]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semilinear_map