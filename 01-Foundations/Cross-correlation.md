---
title: "Cross-correlation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Cross-correlation"
wikipedia_categories: ["Bilinear maps", "Covariance and correlation", "Signal processing", "Time domain analysis"]
related: ["[[Cross-covariance]]", "[[Autocorrelation]]", "[[Cross-correlation matrix]]", "[[Linear time-invariant system]]", "[[Triple correlation]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]"]
---

# Cross-correlation

In signal processing, cross-correlation is a measure of similarity of two series as a function of the displacement of one relative to the other. This is also known as a sliding dot product or sliding inner-product. It is commonly used for searching a long signal for a shorter, known feature. It has applications in pattern recognition, single particle analysis, electron tomography, averaging, cryptanalysis, and neurophysiology. The cross-correlation is similar in nature to the convolution of two functions.  In an autocorrelation, which is the cross-correlation of a signal with itself, there will always be a peak at a lag of zero, and its size will be the signal energy.
In probability and statistics, the term cross-correlations refers to the correlations between the entries of two random vectors 
  
    
      
        
          X
        
      
    
    
  
 and 
  
    
      
        
          Y
        
      
    
    
  
, while the correlations of a random vector 
  
    
      
        
          X
        
      
    
    
  
 are the correlations between the entries of 
  
    
      
        
          X
        
      
    
    
  
 itself, those forming the correlation matrix of 
  
    
      
        
          X
        
      
    
    
  
. If each of 
  
    
      
        
          X
        
      
    
    
  
 and 
  
    
      
        
          Y
        
      
    
    
  
 is a scalar random variable which is realized repeatedly in a time series, then the correlations of the various temporal instances of 
  
    
      
        
          X
        
      
    
    
  
 are known as autocorrelations of 
  
    
      
        
          X
        
      
    
    
  
, and the cross-correlations of 
  
    
      
        
          X
        
      
    
    
  
 with 
  
    
      
        
          Y
        
      
    
    
  
 across time are temporal cross-correlations. In probability and statistics, the definition of correlation always includes a standardising factor in such a way that correlations have values between −1 and +1.
If 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
 are two independent random variables with probability density functions 
  
    
      
        f
      
    
    
  
 and 
  
    
      
        g
      
    
    
  
, respectively, then the probability density of the difference 
  
    
      
        Y
        X
      
    
    
  
 is formally given by the cross-correlation (in the signal-processing sense) 
  
    
      
        f
        ⋆
        g
      
    
    
  
; however, this terminology is not used in probability and statistics. In contrast, the convolution 
  
    
      
        f
        g
      
    
    
  
 (equivalent to the cross-correlation of 
  
    
      
        
          
            
              f
              −
              t
            
            ¯
          
        
      
    
    
  
 and 
  
    
      
        g
        t
      
    
    
  
) gives the probability density function of the sum 
  
    
      
        X
        Y
      
    
    
  
.

## Related

- [[Cross-covariance]]
- [[Autocorrelation]]
- [[Cross-correlation matrix]]
- [[Linear time-invariant system]]
- [[Triple correlation]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cross-correlation