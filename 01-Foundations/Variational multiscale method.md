---
title: "Variational multiscale method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Variational_multiscale_method"
wikipedia_categories: ["Computational fluid dynamics", "Mathematical modeling", "Numerical analysis"]
related: ["[[Bidomain model]]", "[[Bueno-Orovio–Cherry–Fenton model]]", "[[Explicit algebraic stress model]]", "[[Finite volume method]]", "[[Forward problem of electrocardiology]]", "[[Iterative rational Krylov algorithm]]", "[[Material point method]]", "[[Mesh generation]]", "[[Meshfree methods]]", "[[Model order reduction]]"]
---

# Variational multiscale method

The variational multiscale method (VMS) is a technique used for deriving models and numerical methods for multiscale phenomena. The VMS framework has been mainly applied to design stabilized finite element methods in which stability of the standard Galerkin method is not ensured both in terms of singular perturbation and of compatibility conditions with the finite element spaces.
Stabilized methods are getting increasing attention in computational fluid dynamics because they are designed to solve drawbacks typical of the standard Galerkin method: advection-dominated flows problems and problems in which an arbitrary combination of interpolation functions may yield to unstable discretized formulations. The milestone of stabilized methods for this class of problems can be considered the Streamline Upwind Petrov-Galerkin method (SUPG), designed during 80s for convection dominated-flows for the incompressible Navier–Stokes equations by Brooks and Hughes. Variational Multiscale Method (VMS) was introduced by Hughes in 1995. Broadly speaking, VMS is a technique used to get mathematical models and numerical methods which are able to catch multiscale phenomena; in fact, it is usually adopted for problems with huge scale ranges, which are separated into a number of scale groups. The main idea of the method is to design a sum decomposition of the solution as 
  
    
      
        u
        
          
            
              u
              ¯
            
          
        
        
          u
          ′
        
      
    
    
  
, where 
  
    
      
        
          
            
              u
              ¯
            
          
        
      
    
    
  
 is denoted as coarse-scale solution and it is solved numerically, whereas 
  
    
      
        
          u
          ′
        
      
    
    
  
 represents the fine scale solution and is determined analytically eliminating it from the problem of the coarse scale equation.

## Related

- [[Bidomain model]]
- [[Bueno-Orovio–Cherry–Fenton model]]
- [[Explicit algebraic stress model]]
- [[Finite volume method]]
- [[Forward problem of electrocardiology]]
- [[Iterative rational Krylov algorithm]]
- [[Material point method]]
- [[Mesh generation]]
- [[Meshfree methods]]
- [[Model order reduction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Variational_multiscale_method