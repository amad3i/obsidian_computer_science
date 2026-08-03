---
title: "Dirichlet series inversion"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dirichlet_series_inversion"
wikipedia_categories: ["Analytic number theory", "Integer sequences", "Number theory"]
related: ["[[3x + 1 semigroup]]", "[[Amicable triple]]", "[[Bernoulli number]]", "[[Cube (algebra)]]", "[[Divisor function]]", "[[Divisor sum identities]]", "[[Eighth power]]", "[[Elliptic divisibility sequence]]", "[[Fifth power (algebra)]]", "[[Fourth power]]"]
---

# Dirichlet series inversion

In analytic number theory, a Dirichlet series, or Dirichlet generating function (DGF), of a sequence is a common way of understanding and summing arithmetic functions in a meaningful way. A little known, or at least often forgotten about, way of expressing formulas for arithmetic functions and their summatory functions is to perform an integral transform that inverts the operation of forming the DGF of a sequence. This inversion is analogous to performing an inverse Z-transform to the generating function of a sequence to express formulas for the series coefficients of a given ordinary generating function.
For now, we will use this page as a compendia of "oddities" and oft-forgotten facts about transforming and inverting Dirichlet series, DGFs, and relating the inversion of a DGF of a sequence to the sequence's summatory function. We also use the notation for coefficient extraction usually applied to formal generating functions in some complex variable, by denoting 
  
    
      
        
          n
          
            s
          
        
        
          D
          
            f
          
        
        s
        =:
        f
        n
      
    
    
  
 for any positive integer 
  
    
      
        n
        ≥
        1
      
    
    
  
, whenever

  
    
      
        
          D
          
            f
          
        
        s
        :=
        
          ∑
          
            n
            ≥
            0
          
        
        
          
            
              f
              n
            
            
              n
              
                s
              
            
          
        
        ,
        
        ℜ
        s
        >
        
          σ
          
            0
            ,
            f
          
        
        ,
      
    
    
  

denotes the DGF (or Dirichlet series) of f which is taken to be absolutely convergent whenever the real part of s is greater than the abscissa of absolute convergence, 
  
    
      
        
          σ
          
            0
            ,
            f
          
        
        ∈
        
          R
        
      
    
    
  
.
The relation of the Mellin transformation of the summatory function of a sequence to the DGF of a sequence provides us with a way of expressing arithmetic functions 
  
    
      
        f
        n
      
    
    
  
 such that 
  
    
      
        f
        1
        ≠
        0
      
    
    
  
, and the corresponding Dirichlet inverse functions, 
  
    
      
        
          f
          
            1
          
        
        n
      
    
    
  
, by inversion formulas involving the summatory function, defined by

  
    
      
        
          S
          
            f
          
        
        x
        :=
        
          
            
              ∑
              
                n
                ≤
                x
              
            
          
          
            ′
          
        
        f
        n
        ,
        
        ∀
        x
        ≥
        1.
      
    
    
  

In particular, provided that the DGF of some arithmetic function f has an analytic continuation to 
  
    
      
        s
        ↦
        s
      
    
    
  
, we can express the Mellin transform of the summatory function of f by the continued DGF formula as

  
    
      
        
          
            M
          
        
        
          S
          
            f
          
        
        (
        s
        =
        
          
            
              
                D
                
                  f
                
              
              −
              s
            
            s
          
        
        .
      
    
    
  

It is often also convenient to express formulas for the summatory functions over the Dirichlet inverse function of f using this construction of a Mellin inversion type problem.

## Related

- [[3x + 1 semigroup]]
- [[Amicable triple]]
- [[Bernoulli number]]
- [[Cube (algebra)]]
- [[Divisor function]]
- [[Divisor sum identities]]
- [[Eighth power]]
- [[Elliptic divisibility sequence]]
- [[Fifth power (algebra)]]
- [[Fourth power]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dirichlet_series_inversion