---
title: "Gradient discretisation method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Gradient_discretisation_method"
wikipedia_categories: ["Numerical analysis", "Numerical differential equations"]
related: ["[[Adaptive step size]]", "[[Bi-directional delay line]]", "[[Boundary knot method]]", "[[Boundary particle method]]", "[[Composite methods for structural dynamics]]", "[[Deep backward stochastic differential equation method]]", "[[Discrete calculus]]", "[[Dormand–Prince method]]", "[[Exponential integrator]]", "[[Fast multipole method]]"]
---

# Gradient discretisation method

In numerical mathematics, the gradient discretisation method (GDM) is a framework which contains classical and recent numerical schemes for diffusion problems of various kinds: linear or non-linear, steady-state or time-dependent.  The schemes may be conforming or non-conforming, and may rely on very general polygonal or polyhedral meshes (or may even be meshless).
Some core properties are required to prove the convergence of a GDM. These core properties enable complete proofs of convergence of the GDM for elliptic and parabolic problems, linear or non-linear. For linear problems, stationary or transient, error estimates can be established based on three indicators specific to the GDM  (the quantities 
  
    
      
        
          C
          
            D
          
        
      
    
    
  
, 
  
    
      
        
          S
          
            D
          
        
      
    
    
  
 and 
  
    
      
        
          W
          
            D
          
        
      
    
    
  
, see below). For non-linear problems, the proofs are based on compactness techniques and do not require any non-physical strong regularity assumption on the solution or the model data. Non-linear models for which such convergence proof of the GDM have been carried out comprise: the Stefan problem which is modelling a melting material, two-phase flows in porous media, the Richards equation of underground water flow, the fully non-linear Leray—Lions equations.
Any scheme entering the GDM framework is then known to converge on all these problems. This applies in particular to conforming Finite Elements, Mixed Finite Elements, nonconforming Finite Elements, and, in the case of more recent schemes, the Discontinuous Galerkin method, Hybrid Mixed Mimetic method, the Nodal Mimetic Finite Difference method, some Discrete Duality Finite Volume schemes, and some Multi-Point Flux Approximation schemes

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
- [[Fast multipole method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gradient_discretisation_method