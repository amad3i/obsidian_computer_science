---
title: "Kahan summation algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Kahan_summation_algorithm"
wikipedia_categories: ["Computer arithmetic", "Floating point", "Numerical analysis"]
related: ["[[2Sum]]", "[[Sterbenz lemma]]", "[[Summation algorithm]]", "[[CORDIC]]", "[[Gal's accurate tables]]", "[[Interval arithmetic]]", "[[Interval contractor]]", "[[INTLAB]]", "[[Karlsruhe Accurate Arithmetic]]", "[[Numerical error]]"]
---

# Kahan summation algorithm

In numerical analysis, the Kahan summation algorithm, also known as compensated summation, significantly reduces the numerical error in the total obtained by adding a sequence of finite-precision floating-point numbers, compared to the naive approach (a summation algorithm). This is done by keeping a separate running compensation (a variable to accumulate small errors), in effect extending the precision of the sum by the precision of the compensation variable.
In particular, simply summing 
  
    
      
        n
      
    
    
  
 numbers in sequence has a worst-case error that grows proportional to 
  
    
      
        n
      
    
    
  
, and a root mean square error that grows as 
  
    
      
        
          
            n
          
        
      
    
    
  
 for random inputs (the roundoff errors form a random walk).  With compensated summation, using a compensation variable with sufficiently high precision the worst-case error bound is effectively independent of 
  
    
      
        n
      
    
    
  
, so a large number of values can be summed with an error that only depends on the floating-point precision of the result.
The algorithm is attributed to William Kahan; Ivo Babuška seems to have come up with a similar algorithm independently (hence Kahan–Babuška summation). Similar, earlier techniques are, for example, Bresenham's line algorithm, keeping track of the accumulated error in integer operations (although first documented around the same time) and the delta-sigma modulation.

## Related

- [[2Sum]]
- [[Sterbenz lemma]]
- [[Summation algorithm]]
- [[CORDIC]]
- [[Gal's accurate tables]]
- [[Interval arithmetic]]
- [[Interval contractor]]
- [[INTLAB]]
- [[Karlsruhe Accurate Arithmetic]]
- [[Numerical error]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kahan_summation_algorithm