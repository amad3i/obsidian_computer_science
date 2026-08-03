---
title: "Spurious-free dynamic range"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Spurious-free_dynamic_range"
wikipedia_categories: ["Digital signal processing", "Electronics stubs"]
related: ["[[Channelizer]]", "[[Differential nonlinearity]]", "[[DSSP (imaging)]]", "[[Integral nonlinearity]]", "[[Lapped transform]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]"]
---

# Spurious-free dynamic range

Spurious-free dynamic range (SFDR) is the strength ratio of the fundamental signal to the strongest spurious tone in the output. It
is also defined as a measure used to specify analog-to-digital and digital-to-analog converters (ADCs and DACs, respectively) and radio receivers.
SFDR is defined as the ratio of the RMS value of the carrier wave (maximum signal component) at the input of the ADC or output of DAC to the RMS value of the next largest noise or harmonic distortion component (which is referred to as “spurious” or a “spur”) at its output. SFDR is usually measured in dBc (i.e. with respect to the carrier signal amplitude) or in dBFS (i.e. with respect to the ADC's full-scale range). Depending on the test condition, SFDR is observed within a pre-defined frequency window or from DC up to Nyquist frequency of the converter (ADC or DAC).

In case of a radio receiver application, the definition is slightly different. The reference is the minimum detectable signal level at the input of a receiver, which can be calculated through a knowledge of the noise figure and the input signal bandwidth of the receiver or the system.  The difference between this value and the input level which will produce distortion products equal to the minimum detectable signal referred to the input of the system is the SFDR of the system. However, this procedure is mainly reliable for ADCs. In RF systems where output spurious signals are nonlinear function of input power, more precise measurement is required to take into account this non-linearity in power.

  
    
      
        D
        
          R
          
            f
          
        
        d
        B
        =
        
          
            
              2
              3
            
          
        
        
          P
          
            3
          
        
        
          N
          
            0
          
        
      
    
    
  

Where 
  
    
      
        
          P
          
            3
          
        
      
    
    
  
 is the third-order intercept point and 
  
    
      
        
          N
          
            0
          
        
      
    
    
  
 is the noise floor of the component, expressed in dB or dBm.

## Related

- [[Channelizer]]
- [[Differential nonlinearity]]
- [[DSSP (imaging)]]
- [[Integral nonlinearity]]
- [[Lapped transform]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spurious-free_dynamic_range