---
title: "Zero-crossing rate"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Zero-crossing_rate"
wikipedia_categories: ["Rates", "Signal processing", "Signal processing stubs"]
related: ["[[Adjacent channel power ratio]]", "[[Audio leveler]]", "[[Bandwidth expansion]]", "[[Constant amplitude zero autocorrelation waveform]]", "[[Cross-recurrence quantification]]", "[[Decorrelation]]", "[[Delay equalization]]", "[[Direction of arrival]]", "[[Echo removal]]", "[[Fast folding algorithm]]"]
---

# Zero-crossing rate

The zero-crossing rate (ZCR) is the rate at which a signal changes from positive to zero to negative or from negative to zero to positive. Its value has been widely used in both speech recognition and music information retrieval, being a key feature to classify percussive sounds.
ZCR is defined formally as

  
    
      
        z
        c
        r
        
          
            1
            
              T
              1
            
          
        
        
          ∑
          
            t
            1
          
          
            T
            1
          
        
        
          |
          
            
              s
              g
              n
            
            s
            t
            ]
            
              s
              g
              n
            
            s
            t
            1
            ]
          
          |
        
      
    
    
  

where 
  
    
      
        s
      
    
    
  
 is a signal of length 
  
    
      
        T
      
    
    
  
 and 
  
    
      
        
          s
          g
          n
        
        x
      
    
    
  
 is a sign function defined as:

  
    
      
        
          s
          g
          n
        
        x
        =
        
          
            
              
                
                  1
                  ,
                  
                  x
                  ≥
                  0
                
              
              
                
                  0
                  ,
                  
                  x
                  0
                
              
            
            
          
        
      
    
    
  

In some cases only the "positive-going" or "negative-going" crossings are counted, rather than all the crossings, since between a pair of adjacent positive zero-crossings there must be a single negative zero-crossing.
For monophonic tonal signals, the zero-crossing rate can be used as a primitive pitch detection algorithm. Zero crossing rates are also used for Voice activity detection (VAD), which determines whether human speech is present in an audio segment or not.

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

- Wikipedia: https://en.wikipedia.org/wiki/Zero-crossing_rate