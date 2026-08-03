---
title: "Tate's algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Tate's_algorithm"
wikipedia_categories: ["Elliptic curves", "Number theory"]
related: ["[[Frey curve]]", "[[Schoof's algorithm]]", "[[3x + 1 semigroup]]", "[[Abc conjecture]]", "[[Abel's summation formula]]", "[[Algebraic number theory]]", "[[Amenable number]]", "[[Amicable triple]]", "[[An Introduction to the Theory of Numbers]]", "[[Arithmetic derivative]]"]
---

# Tate's algorithm

In the theory of elliptic curves, Tate's algorithm takes as input an integral model of an elliptic curve E over 
  
    
      
        
          Q
        
      
    
    
  
, or more generally an algebraic number field, and a prime or prime ideal p. It returns the exponent fp of p in the conductor of E, the type of reduction at p, the local index

  
    
      
        
          c
          
            p
          
        
        [
        E
        
          
            Q
          
          
            p
          
        
        :
        
          E
          
            0
          
        
        
          
            Q
          
          
            p
          
        
        ]
        ,
      
    
    
  

where 
  
    
      
        
          E
          
            0
          
        
        
          
            Q
          
          
            p
          
        
      
    
    
  
 is the group of 
  
    
      
        
          
            Q
          
          
            p
          
        
      
    
    
  
-points
whose reduction mod p is a non-singular point. Also, the algorithm determines whether or not the given integral model is minimal at p, and, if not, returns an integral model with integral coefficients for which the valuation  at p of the discriminant is minimal.
Tate's algorithm also gives the structure of the singular fibers given by the Kodaira symbol or Néron symbol, for which, see elliptic surfaces: in turn this determines the exponent fp of the conductor E.
Tate's algorithm can be greatly simplified if the characteristic of the residue class field is not 2 or 3; in this case the type and c and f can be read off from the valuations of j and Δ (defined below).
Tate's algorithm was introduced by John Tate (1975) as an improvement of the description of the Néron model of an elliptic curve by Néron (1964).

## Related

- [[Frey curve]]
- [[Schoof's algorithm]]
- [[3x + 1 semigroup]]
- [[Abc conjecture]]
- [[Abel's summation formula]]
- [[Algebraic number theory]]
- [[Amenable number]]
- [[Amicable triple]]
- [[An Introduction to the Theory of Numbers]]
- [[Arithmetic derivative]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tate's_algorithm