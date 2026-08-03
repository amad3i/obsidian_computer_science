---
title: "Log-spectral distance"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Log-spectral_distance"
wikipedia_categories: ["Computing stubs", "Signal processing", "Signal processing stubs"]
related: ["[[Adjacent channel power ratio]]", "[[Audio leveler]]", "[[Bandwidth expansion]]", "[[Constant amplitude zero autocorrelation waveform]]", "[[Cross-recurrence quantification]]", "[[Decorrelation]]", "[[Delay equalization]]", "[[Direction of arrival]]", "[[Echo removal]]", "[[Fast folding algorithm]]"]
---

# Log-spectral distance

The log-spectral distance (LSD), also referred to as log-spectral distortion  or root mean square log-spectral distance, is a distance measure between two spectra. The log-spectral distance between spectra 
  
    
      
        P
        
          ω
        
      
    
    
  
 and 
  
    
      
        
          
            
              P
              ^
            
          
        
        
          ω
        
      
    
    
  
 is defined as p-norm:

  
    
      
        
          D
          
            L
            S
          
        
        
          
            
              
                
                  
                    1
                    
                      2
                      π
                    
                  
                
                
                  ∫
                  
                    π
                  
                  
                    π
                  
                
                
                  
                    
                       
                      P
                      ω
                      −
                       
                      
                        
                          
                            P
                            ^
                          
                        
                      
                      ω
                    
                  
                  
                    p
                  
                
                
                d
                ω
              
            
          
          
            1
            
              /
            
            p
          
        
        ,
      
    
    
  
 where 
  
    
      
        P
        
          ω
        
      
    
    
  
 and 
  
    
      
        
          
            
              P
              ^
            
          
        
        
          ω
        
      
    
    
  
 are power spectra.
Unlike the Itakura–Saito distance, the log-spectral distance is symmetric.
In speech coding, log spectral distortion for a given frame is defined as the root mean square difference between the original LPC log power spectrum and the quantized or interpolated LPC log power spectrum. Usually the average of spectral distortion over a large number of frames is calculated and that is used as the measure of performance of quantization or interpolation.

## Related

- [[Adjacent channel power ratio]]
- [[Audio leveler]]
- [[Bandwidth expansion]]
- [[Constant amplitude zero autocorrelation waveform]]
- [[Cross-recurrence quantification]]
- [[Decorrelation]]
- [[Delay equalization]]
- [[Direction of arrival]]
- [[Echo removal]]
- [[Fast folding algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Log-spectral_distance