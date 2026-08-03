---
title: "Ambiguity function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Ambiguity_function"
wikipedia_categories: ["Signal processing", "Time–frequency analysis"]
related: ["[[Analytic signal]]", "[[Instantaneous phase and frequency]]", "[[Linear canonical transformation]]", "[[Low Frequency Analyzer and Recorder]]", "[[Multitaper]]", "[[Poisson wavelet]]", "[[Shearlet]]", "[[Short-time Fourier transform]]", "[[Spectral correlation density]]", "[[Spectrogram]]"]
---

# Ambiguity function

In pulsed radar and sonar signal processing, an ambiguity function is a two-dimensional function of propagation delay 
  
    
      
        τ
      
    
    
  
 and Doppler frequency 
  
    
      
        f
      
    
    
  
, 
  
    
      
        χ
        τ
        ,
        f
      
    
    
  
. It represents the distortion of a returned pulse due to the receiver matched filter (commonly, but not exclusively, used in pulse compression radar) of the return from a moving target. The ambiguity function is defined by the properties of the pulse and of the filter, and not any particular target scenario.
Many definitions of the ambiguity function exist; some are restricted to narrowband signals and others are suitable to describe the delay and Doppler relationship of wideband signals. Often the definition of the ambiguity function is given as the magnitude squared of other definitions (Weiss). 
For a given complex baseband pulse 
  
    
      
        s
        t
      
    
    
  
, the narrowband ambiguity function is given by

  
    
      
        χ
        τ
        ,
        f
        =
        
          ∫
          
            ∞
          
          
            ∞
          
        
        s
        t
        
          s
          
          
        
        t
        τ
        
          e
          
            i
            2
            π
            f
            t
          
        
        
        d
        t
      
    
    
  

where 
  
    
      
        
          
          
          
        
      
    
    
  
 denotes the complex conjugate and 
  
    
      
        i
      
    
    
  
 is the imaginary unit. Note that for zero Doppler shift (
  
    
      
        f
        0
      
    
    
  
), this reduces to the autocorrelation of 
  
    
      
        s
        t
      
    
    
  
. A more concise way of representing the
ambiguity function consists of examining the one-dimensional
zero-delay and zero-Doppler "cuts"; that is, 
  
    
      
        χ
        0
        ,
        f
      
    
    
  
 and

  
    
      
        χ
        τ
        ,
        0
      
    
    
  
, respectively. The matched filter output as a function of time (the signal one would observe in a radar system) is a Doppler cut, with the constant frequency given by the target's Doppler shift: 
  
    
      
        χ
        τ
        ,
        
          f
          
            D
          
        
      
    
    
  
.

## Related

- [[Analytic signal]]
- [[Instantaneous phase and frequency]]
- [[Linear canonical transformation]]
- [[Low Frequency Analyzer and Recorder]]
- [[Multitaper]]
- [[Poisson wavelet]]
- [[Shearlet]]
- [[Short-time Fourier transform]]
- [[Spectral correlation density]]
- [[Spectrogram]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ambiguity_function