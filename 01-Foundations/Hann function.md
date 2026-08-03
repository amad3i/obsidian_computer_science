---
title: "Hann function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hann_function"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Hann function

The Hann function is named after the Austrian meteorologist Julius von Hann.  It is a window function used to perform Hann smoothing or hanning. The function, with length 
  
    
      
        L
      
    
    
  
 and amplitude 
  
    
      
        1
        
          /
        
        L
        ,
      
    
    
  
 is given by:

  
    
      
        
          w
          
            0
          
        
        x
        ≜
        
          
            
              
                
                  
                    
                      
                        1
                        L
                      
                    
                  
                  
                    
                      
                        
                          
                            1
                            2
                          
                        
                      
                      
                        
                          
                            1
                            2
                          
                        
                      
                       
                      
                        
                          
                            
                              2
                              π
                              x
                            
                            L
                          
                        
                      
                    
                  
                  
                    
                      
                        1
                        L
                      
                    
                  
                  
                    
                      2
                    
                  
                   
                  
                    
                      
                        
                          π
                          x
                        
                        L
                      
                    
                  
                  ,
                  
                
                
                  
                    |
                    x
                    |
                  
                  ≤
                  L
                  
                    /
                  
                  2
                
              
              
                
                  0
                  ,
                  
                
                
                  
                    |
                    x
                    |
                  
                  L
                  
                    /
                  
                  2
                
              
            
          
        
        .
      
    
    
  
   
For digital signal processing, the function is sampled symmetrically (with spacing 
  
    
      
        L
        
          /
        
        N
      
    
    
  
 and amplitude 
  
    
      
        1
      
    
    
  
):

  
    
      
        
          
          
            
              
                
                  w
                  n
                  =
                  L
                  ⋅
                  
                    w
                    
                      0
                    
                  
                  
                    
                      
                        
                          
                            L
                            N
                          
                        
                      
                      n
                      N
                      
                        /
                      
                      2
                    
                  
                
                
                  
                  
                    
                      
                        1
                        2
                      
                    
                  
                  
                    
                      1
                      cos
                       
                      
                        
                          
                            
                              
                                2
                                π
                                n
                              
                              N
                            
                          
                        
                      
                    
                  
                
              
              
                
                
                  
                  
                    
                      2
                    
                  
                   
                  
                    
                      
                        
                          
                            π
                            n
                          
                          N
                        
                      
                    
                  
                
              
            
          
        
        ,
        
        0
        ≤
        n
        ≤
        N
        ,
      
    
    ,\quad 0\leq n\leq N,}
  

which is a sequence of 
  
    
      
        N
        1
      
    
    
  
 samples, and 
  
    
      
        N
      
    
    
  
 can be even or odd. It is also known as the raised cosine window, Hann filter, von Hann window, Hanning window, etc.

## Related

- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]
- [[Argument (complex analysis)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hann_function