---
title: "Process gain"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Process_gain"
wikipedia_categories: ["Signal processing", "Telecommunications stubs"]
related: ["[[Gating (telecommunication)]]", "[[Multiplex baseband]]", "[[Quasi-analog signal]]", "[[Signal regeneration]]", "[[WSSUS model]]", "[[Adaptive beamformer]]", "[[Adaptive predictive coding]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]"]
---

# Process gain

In a spread-spectrum system, the process gain (or "processing gain") is the ratio of the spread (or RF) bandwidth to the unspread (or baseband) bandwidth. Research suggests that it is one of the important factors in making decisions over the performance of system in jamming environment.
It is usually expressed in decibels (dB). For example, if a 1 kHz signal is spread to 100 kHz, the process gain expressed as a numerical ratio would be 100000/1000 = 100. Or in decibels, 10 log10(100) = 20 dB.
Note that process gain does not reduce the effects of wideband thermal noise. It can be shown that a direct-sequence spread-spectrum (DSSS) system has exactly the same bit error behavior as a non-spread-spectrum system with the same modulation format.  Thus, on an additive white Gaussian noise (AWGN) channel without interference, a spread system requires the same transmitter power as an unspread system, all other things being equal.
Unlike a conventional communication system, however, a DSSS system does have a certain resistance against narrowband interference, as the interference is not subject to the process gain of the DSSS signal, and hence the signal-to-interference ratio is improved.
In frequency modulation (FM), the processing gain can be expressed as

  
    
      
        
          G
          
            p
          
        
        
          
            
              
                
              
              
                
                  1.5
                  
                    B
                    
                      n
                    
                  
                  Δ
                  f
                  
                    
                      2
                    
                  
                
              
            
            
              
                
              
              
                
                  
                    W
                    
                      3
                    
                  
                
              
            
          
        
        ,
      
    
    
  

where:

Gp is the processing gain,
Bn is the noise bandwidth,
Δf is the peak frequency deviation,
W is the sinusoidal modulating frequency.

## Related

- [[Gating (telecommunication)]]
- [[Multiplex baseband]]
- [[Quasi-analog signal]]
- [[Signal regeneration]]
- [[WSSUS model]]
- [[Adaptive beamformer]]
- [[Adaptive predictive coding]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Process_gain