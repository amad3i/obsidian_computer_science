---
title: "Chebyshev center"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Chebyshev_center"
wikipedia_categories: ["Estimation methods", "Geometric centers", "Mathematical optimization"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# Chebyshev center

In geometry, the Chebyshev center of a bounded set 
  
    
      
        Q
      
    
    
  
 having non-empty interior can mean two different things:

it can be the center of the minimal-radius ball enclosing the entire set 
  
    
      
        Q
      
    
    
  
, or
it can be the center of a largest inscribed ball of 
  
    
      
        Q
      
    
    
  
.
To see that these are not equivalent, it suffices to consider as 
  
    
      
        Q
      
    
    
  
 a triangle where one side is much shorter than the two others; the enclosed kind of Chebyshev center will be in the vicinity of the midpoints of the two long sides, whereas the inscribed kind of Chebyshev center will be in the vicinity of the short side, where the triangle is thickest. This article is mostly about the enclosing kind of Chebyshev center.
In the field of parameter estimation, the Chebyshev center approach tries to find an estimator 
  
    
      
        
          
            
              x
              ^
            
          
        
      
    
    
  
 for 
  
    
      
        x
      
    
    
  
 given the feasibility set 
  
    
      
        Q
      
    
    
  
, such that 
  
    
      
        
          
            
              x
              ^
            
          
        
      
    
    
  
 minimizes the worst possible estimation error for x (e.g. best worst case). This is equivalent to the enclosing kind of Chebyshev center.

## Related

- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]
- [[Bayesian efficiency]]
- [[Bilinear program]]
- [[Binary constraint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Chebyshev_center