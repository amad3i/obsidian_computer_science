---
title: "Shearlet"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Shearlet"
wikipedia_categories: ["Image processing", "Signal processing", "Time–frequency analysis", "Wavelets"]
related: ["[[Curvelet]]", "[[Poisson wavelet]]", "[[Wavelet]]", "[[Ambiguity function]]", "[[Analytic signal]]", "[[Chirplet transform]]", "[[Deconvolution]]", "[[Decorrelation]]", "[[Homomorphic filtering]]", "[[Imaging]]"]
---

# Shearlet

In applied mathematical analysis, shearlets are a multiscale framework which allows efficient encoding of anisotropic features in multivariate problem classes. Originally, shearlets were introduced in 2006 for the analysis and sparse approximation of functions  
  
    
      
        f
        ∈
        
          L
          
            2
          
        
        
          
            R
          
          
            2
          
        
      
    
    
  
. They are a natural extension of wavelets, to accommodate the fact that multivariate functions are typically governed by anisotropic features such as edges in images, since wavelets, as isotropic objects, are not capable of capturing such phenomena.
Shearlets are constructed by parabolic scaling, shearing, and translation applied to a few generating functions. At fine scales, they are essentially supported within skinny and directional ridges following the parabolic scaling law, which reads length² ≈ width. Similar to wavelets, shearlets arise from the affine group and allow a unified treatment of the continuum and digital situation leading to faithful implementations. Although they do not constitute an orthonormal basis for 
  
    
      
        
          L
          
            2
          
        
        
          
            R
          
          
            2
          
        
      
    
    
  
, they still form a frame allowing stable expansions of arbitrary functions 
  
    
      
        f
        ∈
        
          L
          
            2
          
        
        
          
            R
          
          
            2
          
        
      
    
    
  
.
One of the most important properties of shearlets is their ability to provide optimally sparse approximations (in the sense of optimality in ) for cartoon-like functions 
  
    
      
        f
      
    
    
  
. In imaging sciences, cartoon-like functions serve as a model for anisotropic features and are compactly supported in 
  
    
      
        0
        ,
        1
        
          
            2
          
        
      
    
    
  
 while being 
  
    
      
        
          C
          
            2
          
        
      
    
    
  
 apart from a closed piecewise 
  
    
      
        
          C
          
            2
          
        
      
    
    
  
 singularity curve with bounded curvature.  The decay rate of the 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
-error of the 
  
    
      
        N
      
    
    
  
-term shearlet approximation obtained by taking the 
  
    
      
        N
      
    
    
  
 largest coefficients from the shearlet expansion is in fact optimal up to a log-factor:

  
    
      
        ‖
        f
        
          f
          
            N
          
        
        
          ‖
          
            
              L
              
                2
              
            
          
          
            2
          
        
        ≤
        C
        
          N
          
            2
          
        
        log
         
        N
        
          
            3
          
        
        ,
        
        N
        →
        ∞
        ,
      
    
    
  

where the constant 
  
    
      
        C
      
    
    
  
 depends only on the maximum curvature of the singularity curve and the maximum magnitudes of 
  
    
      
        f
      
    
    
  
, 
  
    
      
        
          f
          ′
        
      
    
    
  
 and 
  
    
      
        
          f
          ″
        
        .
      
    
    
  
 This approximation rate significantly improves the best 
  
    
      
        N
      
    
    
  
-term approximation rate of wavelets providing only 
  
    
      
        O
        
          N
          
            1
          
        
      
    
    
  
 for such class of functions.
Shearlets are to date the only directional representation system that provides sparse approximation of anisotropic features while providing a unified treatment of the continuum and digital realm that allows faithful implementation. Extensions of shearlet systems to 
  
    
      
        
          L
          
            2
          
        
        
          
            R
          
          
            d
          
        
        ,
        d
        ≥
        2
      
    
    
  
 are also available. A comprehensive presentation of the theory and applications of shearlets can be found in.

## Related

- [[Curvelet]]
- [[Poisson wavelet]]
- [[Wavelet]]
- [[Ambiguity function]]
- [[Analytic signal]]
- [[Chirplet transform]]
- [[Deconvolution]]
- [[Decorrelation]]
- [[Homomorphic filtering]]
- [[Imaging]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shearlet