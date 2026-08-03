---
title: "Fast multipole method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fast_multipole_method"
wikipedia_categories: ["Computational science", "Numerical analysis", "Numerical differential equations"]
related: ["[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Finite difference]]"]
---

# Fast multipole method

The fast multipole method (FMM) is a numerical technique that was developed to speed up the calculation of long-ranged forces in the n-body problem. It does this by expanding the system Green's function using a multipole expansion, which allows one to group sources that lie close together and treat them as if they were a single source.
The FMM has also been applied in accelerating the iterative solver in the method of moments (MoM) as applied to computational electromagnetics problems, and in particular in computational bioelectromagnetism. The FMM was first introduced in this manner by Leslie Greengard and Vladimir Rokhlin Jr. and is based on the multipole expansion of the vector Helmholtz equation. By treating the interactions between far-away basis functions using the FMM, the corresponding matrix elements do not need to be explicitly stored, resulting in a significant reduction in required memory. If the FMM is then applied in a hierarchical manner, it can improve the complexity of matrix-vector products in an iterative solver from 
  
    
      
        
          
            O
          
        
        
          N
          
            2
          
        
      
    
    
  
 to 
  
    
      
        
          
            O
          
        
        N
      
    
    
  
 in finite arithmetic, i.e., given a tolerance 
  
    
      
        ε
      
    
    
  
, the matrix-vector product is guaranteed to be within a tolerance 
  
    
      
        ε
        .
      
    
    
  
 The dependence of the complexity on the tolerance 
  
    
      
        ε
      
    
    
  
 is 
  
    
      
        
          
            O
          
        
        log
         
        1
        
          /
        
        ε
        )
      
    
    
  
, i.e., the complexity of FMM is 
  
    
      
        
          
            O
          
        
        N
         
        1
        
          /
        
        ε
        )
      
    
    
  
. This has expanded the area of applicability of the MOM to far greater problems than were previously possible.
The FMM, introduced by Rokhlin Jr. and Greengard has been said to be one of the top ten algorithms of the 20th century. The FMM algorithm reduces the complexity of matrix-vector multiplication involving a certain type of dense matrix which can arise out of many physical systems.
The FMM has also been applied for efficiently treating the Coulomb interaction in the Hartree–Fock method and density functional theory calculations in quantum chemistry.

## Related

- [[Adaptive step size]]
- [[Bi-directional delay line]]
- [[Boundary knot method]]
- [[Boundary particle method]]
- [[Composite methods for structural dynamics]]
- [[Deep backward stochastic differential equation method]]
- [[Discrete calculus]]
- [[Dormand–Prince method]]
- [[Exponential integrator]]
- [[Finite difference]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fast_multipole_method