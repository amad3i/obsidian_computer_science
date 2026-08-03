---
title: "Vector-radix FFT algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Vector-radix_FFT_algorithm"
wikipedia_categories: ["Digital signal processing", "Discrete transforms", "Fast Fourier transforms"]
related: ["[[Fast Fourier transform]]", "[[Discrete cosine transform]]", "[[Discrete Fourier transform]]", "[[Discrete wavelet transform]]", "[[Finite Legendre transform]]", "[[Goertzel algorithm]]", "[[Lapped transform]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]"]
---

# Vector-radix FFT algorithm

The vector-radix FFT algorithm, is a multidimensional fast Fourier transform (FFT) algorithm, which is a generalization of the ordinary Cooley–Tukey FFT algorithm that divides the transform dimensions by arbitrary radices. It breaks a multidimensional (MD) discrete Fourier transform (DFT) down into successively smaller MD DFTs until, ultimately, only trivial MD DFTs need to be evaluated.
The most common multidimensional FFT algorithm is the row-column algorithm, which means transforming the array first in one index and then in the other, see more in FFT. Then a radix-2 direct 2-D FFT has been developed, and it can eliminate 25% of the multiplies as compared to the conventional row-column approach. And this algorithm has been extended to rectangular arrays and arbitrary radices, which is the general vector-radix algorithm.
Vector-radix FFT algorithm can reduce the number of complex multiplications significantly, compared to row-vector algorithm. For example, for a 
  
    
      
        
          N
          
            M
          
        
      
    
    
  
 element matrix (M dimensions, and size N on each dimension), the number of complex multiples of vector-radix FFT algorithm for radix-2 is 
  
    
      
        
          
            
              
                2
                
                  M
                
              
              1
            
            
              2
              
                M
              
            
          
        
        
          N
          
            M
          
        
        
          
            2
          
        
         
        N
      
    
    
  
, meanwhile, for row-column algorithm, it is 
  
    
      
        
          
            
              M
              
                N
                
                  M
                
              
            
            2
          
        
        
          
            2
          
        
         
        N
      
    
    
  
. And generally, even larger savings in multiplies are obtained when this algorithm is operated on larger radices and on higher dimensional arrays.
Overall, the vector-radix algorithm significantly reduces the structural complexity of the traditional DFT having a better indexing scheme, at the expense of a slight increase in arithmetic operations. So this algorithm is widely used for many applications in engineering, science, and mathematics, for example, implementations in image processing, and high speed FFT processor designing.

## Related

- [[Fast Fourier transform]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Vector-radix_FFT_algorithm