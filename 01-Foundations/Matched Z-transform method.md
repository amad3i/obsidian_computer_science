---
title: "Matched Z-transform method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Matched_Z-transform_method"
wikipedia_categories: ["Control theory", "Digital signal processing", "Filter theory"]
related: ["[[Advanced process control]]", "[[Anticausal system]]", "[[Bilinear transform]]", "[[Filter design]]", "[[Finite impulse response]]", "[[FIR transfer function]]", "[[First-order hold]]", "[[Impulse invariance]]", "[[Infinite impulse response]]", "[[Least mean squares filter]]"]
---

# Matched Z-transform method

The matched Z-transform method, also called the pole–zero mapping or pole–zero matching method, and abbreviated MPZ or MZT, is a technique for converting a continuous-time filter design to a discrete-time filter (digital filter) design.
The method works by mapping all poles and zeros of the s-plane design to z-plane locations 
  
    
      
        z
        
          e
          
            s
            T
          
        
      
    
    
  
, for a sample interval 
  
    
      
        T
        1
        
          /
        
        
          f
          
            
              s
            
          
        
      
    
    
  
.  So an analog filter with transfer function:

  
    
      
        H
        s
        =
        
          k
          
            
              a
            
          
        
        
          
            
              
                ∏
                
                  i
                  1
                
                
                  M
                
              
              s
              
                ξ
                
                  i
                
              
            
            
              
                ∏
                
                  i
                  1
                
                
                  N
                
              
              s
              
                p
                
                  i
                
              
            
          
        
      
    
    
  

is transformed into the digital transfer function

  
    
      
        H
        z
        =
        
          k
          
            
              d
            
          
        
        
          
            
              
                ∏
                
                  i
                  1
                
                
                  M
                
              
              1
              
                e
                
                  
                    ξ
                    
                      i
                    
                  
                  T
                
              
              
                z
                
                  1
                
              
            
            
              
                ∏
                
                  i
                  1
                
                
                  N
                
              
              1
              
                e
                
                  
                    p
                    
                      i
                    
                  
                  T
                
              
              
                z
                
                  1
                
              
            
          
        
      
    
    
  

The gain 
  
    
      
        
          k
          
            
              d
            
          
        
      
    
    
  
 must be adjusted to normalize the desired gain, typically set to match the analog filter's gain at DC by setting 
  
    
      
        s
        0
      
    
    
  
 and 
  
    
      
        z
        1
      
    
    
  
 and solving for 
  
    
      
        
          k
          
            
              d
            
          
        
      
    
    
  
.
Since the mapping wraps the s-plane's 
  
    
      
        j
        ω
      
    
    
  
 axis around the z-plane's unit circle repeatedly, any zeros (or poles) greater than the Nyquist frequency will be mapped to an aliased location.
In the (common) case that the analog transfer function has more poles than zeros, the zeros at 
  
    
      
        s
        ∞
      
    
    
  
 may optionally be shifted down to the Nyquist frequency by putting them at 
  
    
      
        z
        −
        1
      
    
    
  
, causing the transfer function to drop off as 
  
    
      
        z
        →
        1
      
    
    
  
 in much the same manner as with the bilinear transform (BLT).
While this transform preserves stability and minimum phase, it preserves neither time- nor frequency-domain response and so is not widely used.  More common methods include the BLT and impulse invariance methods. MZT does provide less high frequency response error than the BLT, however, making it easier to correct by adding additional zeros, which is called the MZTi (for "improved").
A specific application of the matched Z-transform method in the digital control field is with the Ackermann's formula, which changes the poles of the controllable system; in general from an unstable (or nearby) location to a stable location.

## Related

- [[Advanced process control]]
- [[Anticausal system]]
- [[Bilinear transform]]
- [[Filter design]]
- [[Finite impulse response]]
- [[FIR transfer function]]
- [[First-order hold]]
- [[Impulse invariance]]
- [[Infinite impulse response]]
- [[Least mean squares filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Matched_Z-transform_method