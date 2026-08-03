---
title: "Unisolvent functions"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Unisolvent_functions"
wikipedia_categories: ["Approximation theory", "Interpolation", "Inverse problems", "Numerical analysis"]
related: ["[[Radial basis function interpolation]]", "[[Approximation theory]]", "[[De Boor's algorithm]]", "[[Gal's accurate tables]]", "[[Identifiability analysis]]", "[[Method of dominant balance]]", "[[Modulus of smoothness]]", "[[Radial basis function]]", "[[Remez algorithm]]", "[[Semi-infinite programming]]"]
---

# Unisolvent functions

In mathematics, a set of n functions f1, f2, ..., fn is unisolvent (meaning "uniquely solvable") on a domain Ω if the vectors

  
    
      
        
          
            
              
                
                  
                    f
                    
                      1
                    
                  
                  
                    x
                    
                      1
                    
                  
                
              
              
                
                  
                    f
                    
                      1
                    
                  
                  
                    x
                    
                      2
                    
                  
                
              
              
                
                  ⋮
                
              
              
                
                  
                    f
                    
                      1
                    
                  
                  
                    x
                    
                      n
                    
                  
                
              
            
          
        
        ,
        
          
            
              
                
                  
                    f
                    
                      2
                    
                  
                  
                    x
                    
                      1
                    
                  
                
              
              
                
                  
                    f
                    
                      2
                    
                  
                  
                    x
                    
                      2
                    
                  
                
              
              
                
                  ⋮
                
              
              
                
                  
                    f
                    
                      2
                    
                  
                  
                    x
                    
                      n
                    
                  
                
              
            
          
        
        ,
        …
        ,
        
          
            
              
                
                  
                    f
                    
                      n
                    
                  
                  
                    x
                    
                      1
                    
                  
                
              
              
                
                  
                    f
                    
                      n
                    
                  
                  
                    x
                    
                      2
                    
                  
                
              
              
                
                  ⋮
                
              
              
                
                  
                    f
                    
                      n
                    
                  
                  
                    x
                    
                      n
                    
                  
                
              
            
          
        
      
    
    
  

are linearly independent for any choice of n distinct points x1, x2 ... xn in Ω. Equivalently, the collection is unisolvent if the matrix F with entries fi(xj) has a nonzero determinant: det(F) ≠ 0 for any choice of distinct xj's in Ω. Unisolvency is a property of vector spaces, not just particular sets of functions. That is, a vector space of functions of dimension n is unisolvent if given any basis (equivalently, a linearly independent set of n functions), the basis is unisolvent (as a set of functions). This is because any two bases are related by an invertible matrix (the change of basis matrix), so one basis is unisolvent if and only if any other basis is unisolvent.
Unisolvent systems of functions are widely used in interpolation since they guarantee a unique solution to the interpolation problem. The set of polynomials of degree at most ⁠
  
    
      
        d
      
    
    
  
⁠ (which form a vector space of dimension ⁠
  
    
      
        d
        1
      
    
    
  
⁠) are unisolvent by the unisolvence theorem.

## Related

- [[Radial basis function interpolation]]
- [[Approximation theory]]
- [[De Boor's algorithm]]
- [[Gal's accurate tables]]
- [[Identifiability analysis]]
- [[Method of dominant balance]]
- [[Modulus of smoothness]]
- [[Radial basis function]]
- [[Remez algorithm]]
- [[Semi-infinite programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unisolvent_functions