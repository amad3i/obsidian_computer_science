---
title: "Bilinear transform"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bilinear_transform"
wikipedia_categories: ["Control theory", "Digital signal processing", "Transforms"]
related: ["[[Advanced process control]]", "[[Anticausal system]]", "[[Discrete-time Fourier transform]]", "[[First-order hold]]", "[[Matched Z-transform method]]", "[[Minimum phase]]", "[[Non-uniform discrete Fourier transform]]", "[[PLL multibit]]", "[[System analysis]]", "[[Zero-order hold]]"]
---

# Bilinear transform

The bilinear transform (also known as Tustin's method, after Arnold Tustin) is used in digital signal processing and discrete-time control theory to transform continuous-time system representations to discrete-time and vice versa.
The bilinear transform is a special case of a conformal mapping (namely, a Möbius transformation), often used for converting a transfer function 
  
    
      
        
          H
          
            a
          
        
        s
      
    
    
  
 of a linear, time-invariant (LTI) filter in the continuous-time domain (often named an analog filter) to a transfer function 
  
    
      
        
          H
          
            d
          
        
        z
      
    
    
  
 of a linear, shift-invariant filter in the discrete-time domain (often named a digital filter although there are analog filters constructed with switched capacitors that are discrete-time filters). It maps positions on the 
  
    
      
        j
        ω
      
    
    
  
 axis, 
  
    
      
        
          R
          e
        
        s
        =
        0
      
    
    
  
, in the s-plane to the unit circle, 
  
    
      
        
          |
        
        z
        
          |
        
        1
      
    
    
  
, in the z-plane.  Other bilinear transforms can be used for warping the frequency response of any discrete-time linear system (for example to approximate the non-linear frequency resolution of the human auditory system) and are implementable in the discrete domain by replacing a system's unit delays 
  
    
      
        
          
            z
            
              1
            
          
        
      
    
    
  
 with first order all-pass filters.
The transform preserves stability and maps every point of the frequency response of the continuous-time filter, 
  
    
      
        
          H
          
            a
          
        
        j
        
          ω
          
            a
          
        
      
    
    
  
 to a corresponding point in the frequency response of the discrete-time filter, 
  
    
      
        
          H
          
            d
          
        
        
          e
          
            j
            
              ω
              
                d
              
            
            T
          
        
      
    
    
  
 although to a somewhat different frequency, as shown in the Frequency warping section below.  This means that for every feature that one sees in the frequency response of the analog filter, there is a corresponding feature, with identical gain and phase shift, in the frequency response of the digital filter but, perhaps, at a somewhat different frequency.  The change in frequency is barely noticeable at low frequencies but is quite evident at frequencies close to the Nyquist frequency.

## Related

- [[Advanced process control]]
- [[Anticausal system]]
- [[Discrete-time Fourier transform]]
- [[First-order hold]]
- [[Matched Z-transform method]]
- [[Minimum phase]]
- [[Non-uniform discrete Fourier transform]]
- [[PLL multibit]]
- [[System analysis]]
- [[Zero-order hold]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bilinear_transform