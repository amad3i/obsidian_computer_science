---
title: "Finite Legendre transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Finite_Legendre_transform"
wikipedia_categories: ["Digital signal processing", "Discrete transforms", "Numerical analysis"]
related: ["[[Discrete Fourier transform]]", "[[Discrete wavelet transform]]", "[[Discrete cosine transform]]", "[[Fast Fourier transform]]", "[[Lapped transform]]", "[[Least-squares spectral analysis]]", "[[Vector-radix FFT algorithm]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[2Sum]]"]
---

# Finite Legendre transform

The finite Legendre transform (fLT) transforms a mathematical function defined on the finite interval into its Legendre spectrum. Conversely, the inverse fLT (ifLT) reconstructs the original function from the components of the Legendre spectrum and the Legendre polynomials, which are orthogonal on the interval [−1,1]. Specifically, assume a function x(t) to be defined on an interval [−1,1] and discretized into N equidistant points on this interval. The fLT then yields the decomposition of x(t) into its spectral Legendre components,

  
    
      
        
          L
          
            x
          
        
        k
        =
        
          
            
              2
              k
              1
            
            N
          
        
        
          ∑
          
            t
            −
            1
          
          
            t
            1
          
        
        x
        t
        
          P
          
            k
          
        
        t
        ,
      
    
    
  

where the factor (2k + 1)/N serves as normalization factor and Lx(k) gives the contribution of the k-th Legendre polynomial to x(t) such that (ifLT)

  
    
      
        x
        t
        =
        
          ∑
          
            k
          
        
        
          L
          
            x
          
        
        k
        
          P
          
            k
          
        
        t
        .
      
    
    
  

The fLT should not be confused with the Legendre transform or Legendre transformation used in thermodynamics and quantum physics.

## Related

- [[Discrete Fourier transform]]
- [[Discrete wavelet transform]]
- [[Discrete cosine transform]]
- [[Fast Fourier transform]]
- [[Lapped transform]]
- [[Least-squares spectral analysis]]
- [[Vector-radix FFT algorithm]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[2Sum]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Finite_Legendre_transform