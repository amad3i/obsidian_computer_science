---
title: "Sigma approximation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sigma_approximation"
wikipedia_categories: ["Fourier series", "Mathematical analysis stubs", "Numerical analysis"]
related: ["[[Bi-directional delay line]]", "[[Blossom (functional)]]", "[[Equioscillation theorem]]", "[[Guard digit]]", "[[Local convergence]]", "[[Minimum polynomial extrapolation]]", "[[Sparse grid]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]"]
---

# Sigma approximation

In mathematics, σ-approximation adjusts a Fourier summation to greatly reduce the Gibbs phenomenon, which would otherwise occur at discontinuities.
An m-1-term, σ-approximated summation for a series of period T can be written as follows:

  
    
      
        s
        θ
        =
        
          
            1
            2
          
        
        
          a
          
            0
          
        
        
          ∑
          
            k
            1
          
          
            m
            1
          
        
        
          
            
              sinc
               
              
                
                  k
                  m
                
              
            
          
          
            p
          
        
        ⋅
        
          
            
              a
              
                k
              
            
             
            
              
                
                  
                    
                      2
                      π
                      k
                    
                    T
                  
                
                θ
              
            
            
              b
              
                k
              
            
             
            
              
                
                  
                    
                      2
                      π
                      k
                    
                    T
                  
                
                θ
              
            
          
        
        ,
      
    
    
  

in terms of the normalized sinc function:

  
    
      
        sinc
         
        x
        
          
            
               
              π
              x
            
            
              π
              x
            
          
        
        .
      
    
    
  
 

  
    
      
        
          a
          
            k
          
        
      
    
    
  
 and 
  
    
      
        
          b
          
            k
          
        
      
    
    
  
 are the typical Fourier Series coefficients, and p, a non negative parameter, determines the amount of smoothening applied, where higher values of p further reduce the Gibbs phenomenon but can overly smoothen the representation of the function.
The term

  
    
      
        
          
            
              sinc
               
              
                
                  k
                  m
                
              
            
          
          
            p
          
        
      
    
    
  

is the Lanczos σ factor, which is responsible for eliminating most of the Gibbs phenomenon. This is sampling the right side of the main lobe of the 
  
    
      
        sinc
      
    
    
  
 function to rolloff the higher frequency Fourier Series coefficients.
As is known by the uncertainty principle, having a sharp cutoff in the frequency domain (cutting off the Fourier series abruptly without adjusting coefficients) causes a wide spread of information in the time domain (equivalent to large amounts of ringing).
This can also be understood as applying a window function to the Fourier series coefficients to balance maintaining a fast rise time (analogous to a narrow transition band) and small amounts of ringing (analogous to stopband attenuation).

## Related

- [[Bi-directional delay line]]
- [[Blossom (functional)]]
- [[Equioscillation theorem]]
- [[Guard digit]]
- [[Local convergence]]
- [[Minimum polynomial extrapolation]]
- [[Sparse grid]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sigma_approximation