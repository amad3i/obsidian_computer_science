---
title: "Sum of radicals"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sum_of_radicals"
wikipedia_categories: ["Computational geometry", "Computational problems", "Computer algebra"]
related: ["[[3SUM]]", "[[AI-complete]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]", "[[Barrier resilience]]", "[[Bentley–Ottmann algorithm]]"]
---

# Sum of radicals

In mathematics, a sum of radicals is defined as a finite linear combination of nth roots:

  
    
      
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          k
          
            i
          
        
        
          
            
              x
              
                i
              
            
            
              
                r
                
                  i
                
              
            
          
        
        ,
      
    
    
  

where 
  
    
      
        n
        ,
        
          r
          
            i
          
        
      
    
    
  
 are natural numbers and 
  
    
      
        
          k
          
            i
          
        
        ,
        
          x
          
            i
          
        
      
    
    
  
 are real numbers.
A particular special case arising in computational complexity theory is the square-root sum problem, asking whether it is possible to determine the sign of a sum of square roots, with integer coefficients, in polynomial time. This is of importance for many problems in computational geometry, since the computation of the Euclidean distance between two points in the general case involves the computation of a square root, and therefore the perimeter of a polygon or the length of a polygonal chain takes the form of a sum of radicals.
In 1991, Blömer proposed a polynomial time Monte Carlo algorithm for determining whether a sum of radicals is zero, or more generally whether it represents a rational number. Blömer's result applies more generally than the square-root sum problem, to sums of radicals that are not necessarily square roots. However, his algorithm does not solve the problem, because it does not determine the sign of a non-zero sum of radicals.

## Related

- [[3SUM]]
- [[AI-complete]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Badouel intersection algorithm]]
- [[Barrier resilience]]
- [[Bentley–Ottmann algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sum_of_radicals