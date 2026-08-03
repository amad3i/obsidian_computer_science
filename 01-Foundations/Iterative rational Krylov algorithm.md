---
title: "Iterative rational Krylov algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Iterative_rational_Krylov_algorithm"
wikipedia_categories: ["Mathematical modeling", "Numerical analysis"]
related: ["[[Bidomain model]]", "[[Bueno-Orovio–Cherry–Fenton model]]", "[[Forward problem of electrocardiology]]", "[[Model order reduction]]", "[[Movable cellular automaton]]", "[[Proper generalized decomposition]]", "[[Surrogate model]]", "[[Variational multiscale method]]", "[[Vector field reconstruction]]", "[[2Sum]]"]
---

# Iterative rational Krylov algorithm

The iterative rational Krylov algorithm (IRKA) is an iterative algorithm, useful for model order reduction (MOR) of single-input single-output (SISO) linear time-invariant dynamical systems. At each iteration, IRKA does an Hermite type interpolation of the original system transfer function. Each interpolation requires solving 
  
    
      
        r
      
    
    
  
 shifted pairs of linear systems, each of size 
  
    
      
        n
        n
      
    
    
  
; where 
  
    
      
        n
      
    
    
  
 is the original system order, and 
  
    
      
        r
      
    
    
  
 is the desired reduced model order (usually 
  
    
      
        r
        ≪
        n
      
    
    
  
).
The algorithm was first introduced by Gugercin, Antoulas and Beattie in 2008. It is based on a first order necessary optimality condition, initially investigated by Meier and Luenberger in 1967. The first convergence proof of IRKA was given by Flagg, Beattie and Gugercin in 2012, for a particular kind of systems.

## Related

- [[Bidomain model]]
- [[Bueno-Orovio–Cherry–Fenton model]]
- [[Forward problem of electrocardiology]]
- [[Model order reduction]]
- [[Movable cellular automaton]]
- [[Proper generalized decomposition]]
- [[Surrogate model]]
- [[Variational multiscale method]]
- [[Vector field reconstruction]]
- [[2Sum]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Iterative_rational_Krylov_algorithm