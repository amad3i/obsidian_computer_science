---
title: "Stress majorization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Stress_majorization"
wikipedia_categories: ["Dimension reduction", "Graph drawing", "Mathematical analysis", "Mathematical optimization"]
related: ["[[Least-squares spectral analysis]]", "[[Low-rank approximation]]", "[[Maximum and minimum]]", "[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Automorphic number]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]"]
---

# Stress majorization

Stress majorization is an optimization strategy used in multidimensional scaling (MDS) where, for a set of 
  
    
      
        n
      
    
    
  
 
  
    
      
        m
      
    
    
  
-dimensional data items, a configuration 
  
    
      
        X
      
    
    
  
 of 
  
    
      
        n
      
    
    
  
 points in 
  
    
      
        r
      
    
    
  
 
  
    
      
        ≪
        m
      
    
    
  
-dimensional space is sought that minimizes the so-called stress function 
  
    
      
        σ
        X
      
    
    
  
.  Usually 
  
    
      
        r
      
    
    
  
 is 
  
    
      
        2
      
    
    
  
 or 
  
    
      
        3
      
    
    
  
, i.e. the 
  
    
      
        n
        r
      
    
    
  
 matrix 
  
    
      
        X
      
    
    
  
 lists points in 
  
    
      
        2
      
    
    
  
 or 
  
    
      
        3
      
    
    
  
dimensional Euclidean space so that the result may be visualised (i.e. an MDS plot).  The function 
  
    
      
        σ
      
    
    
  
 is a cost or loss function that measures the squared differences between ideal (
  
    
      
        m
      
    
    
  
-dimensional) distances and actual distances in r-dimensional space.  It is defined as:

  
    
      
        σ
        X
        =
        
          ∑
          
            i
            j
            ≤
            n
          
        
        
          w
          
            i
            j
          
        
        
          d
          
            i
            j
          
        
        X
        −
        
          δ
          
            i
            j
          
        
        
          
            2
          
        
      
    
    
  

where 
  
    
      
        
          w
          
            i
            j
          
        
        ≥
        0
      
    
    
  
 is a weight for the measurement between a pair of points 
  
    
      
        i
        ,
        j
      
    
    
  
, 
  
    
      
        
          d
          
            i
            j
          
        
        X
      
    
    
  
 is the euclidean distance between 
  
    
      
        i
      
    
    
  
 and 
  
    
      
        j
      
    
    
  
 and 
  
    
      
        
          δ
          
            i
            j
          
        
      
    
    
  
 is the ideal distance between the points (their separation) in the 
  
    
      
        m
      
    
    
  
-dimensional data space.  Note that 
  
    
      
        
          w
          
            i
            j
          
        
      
    
    
  
 can be used to specify a degree of confidence in the similarity between points (e.g. 0 can be specified if there is no information for a particular pair).
A configuration 
  
    
      
        X
      
    
    
  
 which minimizes 
  
    
      
        σ
        X
      
    
    
  
 gives a plot in which points that are close together correspond to points that are also close together in the original 
  
    
      
        m
      
    
    
  
-dimensional data space.
There are many ways that 
  
    
      
        σ
        X
      
    
    
  
 could be minimized.  For example, Kruskal recommended an iterative steepest descent approach. However, a significantly better (in terms of guarantees on, and rate of, convergence) method for minimizing stress was introduced by Jan de Leeuw.  De Leeuw's iterative majorization method at each step minimizes a simple convex function which both bounds 
  
    
      
        σ
      
    
    
  
 from above and touches the surface of 
  
    
      
        σ
      
    
    
  
 at a point 
  
    
      
        Z
      
    
    
  
, called the supporting point.  In convex analysis such a function is called a majorizing function.  This iterative majorization process is also referred to as the SMACOF algorithm ("Scaling by MAjorizing a COmplicated Function").

## Related

- [[Least-squares spectral analysis]]
- [[Low-rank approximation]]
- [[Maximum and minimum]]
- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Automorphic number]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stress_majorization