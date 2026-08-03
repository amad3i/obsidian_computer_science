---
title: "Fast Fourier transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fast_Fourier_transform"
wikipedia_categories: ["Digital signal processing", "Discrete transforms", "Fast Fourier transforms"]
related: ["[[Vector-radix FFT algorithm]]", "[[Discrete cosine transform]]", "[[Discrete Fourier transform]]", "[[Discrete wavelet transform]]", "[[Finite Legendre transform]]", "[[Goertzel algorithm]]", "[[Lapped transform]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]"]
---

# Fast Fourier transform

A fast Fourier transform (FFT) is an algorithm that computes the discrete Fourier transform (DFT), or its inverse (IDFT), of a sequence. A Fourier transform converts a signal from its original domain (often time or space) to a representation in the frequency domain and vice versa.
The DFT is obtained by decomposing a sequence of values into components of different frequencies. This operation is useful in many fields, but computing it directly from the definition is often too slow to be practical. An FFT rapidly computes such transformations by factorizing the DFT matrix into a product of sparse (mostly zero) factors. As a result, it manages to reduce the complexity of computing the DFT from 
  
    
      
        O
        
          n
          
            2
          
        
      
    
    {\textstyle O(n^{2})}
  
, which arises if one simply applies the definition of DFT, to 
  
    
      
        O
        n
         
        n
      
    
    {\textstyle O(n\log n)}
  
, where n is the length of the sequence. The difference in speed can be enormous, especially for long sequences where n may be in the thousands or millions.
As the FFT is merely an algebraic refactoring of terms within the DFT, the DFT and the FFT both perform mathematically equivalent and interchangeable operations, assuming that all terms are computed with infinite precision.  However, in the presence of round-off error, many FFT algorithms are much more accurate than evaluating the DFT definition directly or indirectly. There are many different FFT algorithms based on a wide range of published theories, from simple complex-number arithmetic to group theory and number theory. The best-known FFT algorithms depend upon the factorization of n, but there are FFTs with 
  
    
      
        O
        n
         
        n
      
    
    
  
 complexity for all n, including prime values. Many FFT algorithms depend only on the fact that 
  
    
      
        
          e
          
            2
            π
            i
            
              /
            
            n
          
        
      
    
    {\textstyle e^{-2\pi i/n}}
  
 is an nth primitive root of unity, and thus can be applied to analogous transforms over any finite field, such as number-theoretic transforms. Since the inverse DFT is the same as the DFT, but with the opposite sign in the exponent and a 1/n factor, any FFT algorithm can easily be adapted for it.
Fast Fourier transforms are widely used for applications in engineering, music, science, and mathematics. The basic ideas were popularized in 1965, but some algorithms had been derived as early as 1805. In 1994, Gilbert Strang described the FFT as "the most important numerical algorithm of our lifetime", and it was included in Top 10 Algorithms of 20th Century by the IEEE magazine Computing in Science & Engineering.

## Related

- [[Vector-radix FFT algorithm]]
- [[Discrete cosine transform]]
- [[Discrete Fourier transform]]
- [[Discrete wavelet transform]]
- [[Finite Legendre transform]]
- [[Goertzel algorithm]]
- [[Lapped transform]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fast_Fourier_transform