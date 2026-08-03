---
title: "Periodic summation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Periodic_summation"
wikipedia_categories: ["Functions and mappings", "Signal processing"]
related: ["[[3D projection]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Antilinear map]]"]
---

# Periodic summation

In mathematics, any integrable function 
  
    
      
        s
        t
      
    
    
  
 can be made into a periodic function 
  
    
      
        
          s
          
            P
          
        
        t
      
    
    
  
 with period P by summing the translations of the function 
  
    
      
        s
        t
      
    
    
  
 by integer multiples of P. This is called periodic summation: 

  
    
      
        
          s
          
            P
          
        
        t
        =
        
          ∑
          
            n
            −
            ∞
          
          
            ∞
          
        
        s
        t
        n
        P
      
    
    
  

The resulting periodic function may not be defined everywhere.
When 
  
    
      
        
          s
          
            P
          
        
        t
      
    
    
  
 is represented as a Fourier series, the Fourier coefficients are equal to the values of the continuous Fourier transform, 
  
    
      
        S
        f
        ≜
        
          
            F
          
        
        s
        t
        }
        ,
      
    
    
  
 at intervals of 
  
    
      
        
          
            
              1
              P
            
          
        
      
    
    
  
. This follows easily from recognizing that the formula for finding the nth coefficient of the Fourier series for the periodic summation is identical to the formula for the value of the Fourier transform of the original function at 
  
    
      
        n
        
          /
        
        P
        .
      
    
    
  
 The identity is also a form of the Poisson summation formula.
This implies that the periodic summation of any band-limited function, such as the sinc function, is a sum of a finite number of sine waves, or even just a single sine wave or zero if the period is less than or equal to half the inverse of the upper frequency limit. A periodic summation of a function can be identically zero if the Fourier transform of the function is zero at all multiples of some frequency, but if all periodic summations (that is, with all periods) are zero then the function must be identically zero.
Similarly, a Fourier series whose coefficients are samples of 
  
    
      
        s
        t
      
    
    
  
 at constant intervals (T) is equivalent to a periodic summation of 
  
    
      
        S
        f
        ,
      
    
    
  
 which is known as a discrete-time Fourier transform.
The periodic summation of a Dirac delta function is the Dirac comb. Likewise, the periodic summation of an integrable function is its convolution with the Dirac comb.

## Related

- [[3D projection]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Antilinear map]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Periodic_summation