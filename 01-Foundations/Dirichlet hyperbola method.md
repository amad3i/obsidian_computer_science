---
title: "Dirichlet hyperbola method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dirichlet_hyperbola_method"
wikipedia_categories: ["Number theory"]
related: ["[[3x + 1 semigroup]]", "[[Abc conjecture]]", "[[Abel's summation formula]]", "[[Algebraic number theory]]", "[[Amenable number]]", "[[Amicable triple]]", "[[An Introduction to the Theory of Numbers]]", "[[Arithmetic derivative]]", "[[Arithmetic group]]", "[[Arithmetic hyperbolic 3-manifold]]"]
---

# Dirichlet hyperbola method

In number theory, the Dirichlet hyperbola method is a technique to evaluate the sum

  
    
      
        F
        n
        =
        
          ∑
          
            k
            1
          
          
            n
          
        
        f
        k
      
    
    
  
.
The first step is to find a pair of functions g and h such that, using Dirichlet convolution, we have f = g ∗ h; the sum then becomes

  
    
      
        F
        n
        =
        
          ∑
          
            k
            1
          
          
            n
          
        
        
          ∑
          
            x
            y
            k
          
          

          
        
        g
        x
        h
        y
        ,
      
    
    
  

where the inner sum runs over all ordered pairs (x,y) of positive integers such that xy = k.  In the Cartesian plane, these pairs lie on a hyperbola, and when the double sum is fully expanded, there is a bijection between the terms of the sum and the lattice points in the first quadrant on the hyperbolas of the form xy = k, where k runs over the integers 1 ≤ k ≤ n: for each such point (x,y), the sum contains a term g(x)h(y), and vice versa.
Let a be a real number, not necessarily an integer, such that 1 < a < n, and let b = n/a.  Then the lattice points can be split into three overlapping regions: one region is bounded by 1 ≤ x ≤ a and 1 ≤ y ≤ n/x, another region is bounded by 1 ≤ y ≤ b and 1 ≤ x ≤ n/y, and the third is bounded by 1 ≤ x ≤ a and 1 ≤ y ≤ b.  In the diagram, the first region is the union of the blue and red regions, the second region is the union of the red and green, and the third region is the red.  Note that this third region is the intersection of the first two regions.  By the principle of inclusion and exclusion, the full sum is therefore the sum over the first region, plus the sum over the second region, minus the sum over the third region.  This yields the formula

## Related

- [[3x + 1 semigroup]]
- [[Abc conjecture]]
- [[Abel's summation formula]]
- [[Algebraic number theory]]
- [[Amenable number]]
- [[Amicable triple]]
- [[An Introduction to the Theory of Numbers]]
- [[Arithmetic derivative]]
- [[Arithmetic group]]
- [[Arithmetic hyperbolic 3-manifold]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dirichlet_hyperbola_method