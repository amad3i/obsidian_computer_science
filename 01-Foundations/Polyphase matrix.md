---
title: "Polyphase matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Polyphase_matrix"
wikipedia_categories: ["Digital signal processing", "Wavelets"]
related: ["[[Discrete wavelet transform]]", "[[Filter bank]]", "[[Lifting scheme]]", "[[Quadrature mirror filter]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]"]
---

# Polyphase matrix

In signal processing, a polyphase matrix is a matrix whose elements are filter masks.  It represents a filter bank as it is used in sub-band coders alias discrete wavelet transforms.
If 
  
    
      
        
          h
          ,
          
          g
        
      
    
    
  
 are two filters, then one level the traditional wavelet transform maps an input signal 
  
    
      
        
          
            a
            
              0
            
          
        
      
    
    
  
 to two output signals 
  
    
      
        
          
            a
            
              1
            
          
          ,
          
          
            d
            
              1
            
          
        
      
    
    
  
, each of the half length:

  
    
      
        
          
            
              
                
                  a
                  
                    1
                  
                
              
              
                
                (
                h
                ⋅
                
                  a
                  
                    0
                  
                
                ↓
                2
              
            
            
              
                
                  d
                  
                    1
                  
                
              
              
                
                (
                g
                ⋅
                
                  a
                  
                    0
                  
                
                ↓
                2
              
            
          
        
      
    
    
  

Note, that the dot means polynomial multiplication; i.e., convolution and 
  
    
      
        
          ↓
        
      
    
    
  
 means downsampling.
If the above formula is implemented directly, you will compute values that are subsequently flushed by the down-sampling.  You can avoid their computation by splitting the filters and the signal into even and odd indexed values before the wavelet transformation:

  
    
      
        
          
            
              
                
                  h
                  
                    
                      e
                    
                  
                
              
              
                
                h
                ↓
                2
              
              
                
                  a
                  
                    0
                    ,
                    
                      
                        e
                      
                    
                  
                
              
              
                
                
                  a
                  
                    0
                  
                
                ↓
                2
              
            
            
              
                
                  h
                  
                    
                      o
                    
                  
                
              
              
                
                (
                h
                ←
                1
                ↓
                2
              
              
                
                  a
                  
                    0
                    ,
                    
                      
                        o
                      
                    
                  
                
              
              
                
                (
                
                  a
                  
                    0
                  
                
                ←
                1
                ↓
                2
              
            
          
        
      
    
    
  

The arrows 
  
    
      
        
          ←
        
      
    
    
  
 and 
  
    
      
        
          →
        
      
    
    
  
 denote left and right shifting, respectively.  They shall have the same precedence like convolution, because they are in fact convolutions with a shifted discrete delta impulse.

  
    
      
        δ
        (
        …
        ,
        0
        ,
        0
        ,
        
          
            1
            
              0
              
                
                  th position
                
              
            
          
        
        ,
        0
        ,
        0
        ,
        …
      
    
    
  

The wavelet transformation reformulated to the split filters is:

  
    
      
        
          
            
              
                
                  a
                  
                    1
                  
                
              
              
                
                
                  h
                  
                    
                      e
                    
                  
                
                ⋅
                
                  a
                  
                    0
                    ,
                    
                      
                        e
                      
                    
                  
                
                
                  h
                  
                    
                      o
                    
                  
                
                ⋅
                
                  a
                  
                    0
                    ,
                    
                      
                        o
                      
                    
                  
                
                →
                1
              
            
            
              
                
                  d
                  
                    1
                  
                
              
              
                
                
                  g
                  
                    
                      e
                    
                  
                
                ⋅
                
                  a
                  
                    0
                    ,
                    
                      
                        e
                      
                    
                  
                
                
                  g
                  
                    
                      o
                    
                  
                
                ⋅
                
                  a
                  
                    0
                    ,
                    
                      
                        o
                      
                    
                  
                
                →
                1
              
            
          
        
      
    
    
  

This can be written as matrix-vector-multiplication

  
    
      
        
          
            
              
                P
              
              
                
                
                  
                    
                      
                        
                          
                            h
                            
                              
                                e
                              
                            
                          
                        
                        
                          
                            h
                            
                              
                                o
                              
                            
                          
                          →
                          1
                        
                      
                      
                        
                          
                            g
                            
                              
                                e
                              
                            
                          
                        
                        
                          
                            g
                            
                              
                                o
                              
                            
                          
                          →
                          1
                        
                      
                    
                  
                
              
            
            
              
                
                  
                    
                      
                        
                          
                            a
                            
                              1
                            
                          
                        
                      
                      
                        
                          
                            d
                            
                              1
                            
                          
                        
                      
                    
                  
                
              
              
                
                P
                ⋅
                
                  
                    
                      
                        
                          
                            a
                            
                              0
                              ,
                              
                                
                                  e
                                
                              
                            
                          
                        
                      
                      
                        
                          
                            a
                            
                              0
                              ,
                              
                                
                                  o
                                
                              
                            
                          
                        
                      
                    
                  
                
              
            
          
        
      
    
    
  

This matrix 
  
    
      
        
          P
        
      
    
    
  
 is the polyphase matrix.
Of course, a polyphase matrix can have any size, it need not to have square shape.  That is, the principle scales well to any filterbanks, multiwavelets, wavelet transforms based on fractional refinements.

*(note truncated for size; full article at the source link below)*

## Related

- [[Discrete wavelet transform]]
- [[Filter bank]]
- [[Lifting scheme]]
- [[Quadrature mirror filter]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Polyphase_matrix