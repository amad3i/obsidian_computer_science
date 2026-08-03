---
title: "Eb/N0"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Eb/N0"
wikipedia_categories: ["Engineering ratios", "Noise (electronics)", "Signal processing"]
related: ["[[Dynamic range]]", "[[Quantization (signal processing)]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]"]
---

# Eb/N0

In digital communication or data transmission, 
  
    
      
        
          E
          
            b
          
        
        
          /
        
        
          N
          
            0
          
        
      
    
    
  
 (energy per bit to noise power spectral density ratio) is a normalized signal-to-noise ratio (SNR) measure, also known as the "SNR per bit". It is especially useful when comparing the bit error rate (BER) performance of different digital modulation schemes without taking bandwidth into account.
As the description implies, 
  
    
      
        
          E
          
            b
          
        
      
    
    
  
 is the signal energy associated with each user data bit; it is equal to the signal power divided by the user bit rate (not the channel symbol rate). If signal power is in watts and bit rate is in bits per second, 
  
    
      
        
          E
          
            b
          
        
      
    
    
  
 is in units of joules (watt-seconds). 
  
    
      
        
          N
          
            0
          
        
      
    
    
  
 is the noise spectral density, the noise power in a 1 Hz bandwidth, measured in watts per hertz or joules.
These are the same units as 
  
    
      
        
          E
          
            b
          
        
      
    
    
  
 so the ratio 
  
    
      
        
          E
          
            b
          
        
        
          /
        
        
          N
          
            0
          
        
      
    
    
  
 is dimensionless; it is frequently expressed in decibels. 
  
    
      
        
          E
          
            b
          
        
        
          /
        
        
          N
          
            0
          
        
      
    
    
  
 directly indicates the power efficiency of the system without regard to modulation type, error correction coding or signal bandwidth (including any use of spread spectrum). This also avoids any confusion as to which of several definitions of "bandwidth" to apply to the signal.
But when the signal bandwidth is well defined, 
  
    
      
        
          E
          
            b
          
        
        
          /
        
        
          N
          
            0
          
        
      
    
    
  
 is also equal to the signal-to-noise ratio (SNR) in that bandwidth divided by the "gross" link spectral efficiency in (bit/s)/Hz, where the bits in this context again refer to user data bits, irrespective of error correction information and modulation type.

  
    
      
        
          E
          
            b
          
        
        
          /
        
        
          N
          
            0
          
        
      
    
    
  
 must be used with care on interference-limited channels since additive white noise (with constant noise density 
  
    
      
        
          N
          
            0
          
        
      
    
    
  
) is assumed, and interference is not always noise-like. In spread spectrum systems (e.g., CDMA), the interference is sufficiently noise-like that it can be represented as 
  
    
      
        
          I
          
            0
          
        
      
    
    
  
 and added to the thermal noise 
  
    
      
        
          N
          
            0
          
        
      
    
    
  
 to produce the overall ratio 
  
    
      
        
          E
          
            b
          
        
        
          /
        
        
          N
          
            0
          
        
        
          I
          
            0
          
        
      
    
    
  
.

## Related

- [[Dynamic range]]
- [[Quantization (signal processing)]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Eb/N0