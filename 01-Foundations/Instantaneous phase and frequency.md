---
title: "Instantaneous phase and frequency"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Instantaneous_phase_and_frequency"
wikipedia_categories: ["Audio engineering", "Digital signal processing", "Electrical engineering", "Fourier analysis", "Signal processing", "Time–frequency analysis"]
related: ["[[Almost periodic function]]", "[[Analytic signal]]", "[[First-order hold]]", "[[Linear canonical transformation]]", "[[Linear time-invariant system]]", "[[Sampling (signal processing)]]", "[[Short-time Fourier transform]]", "[[Whittaker–Shannon interpolation formula]]", "[[Zero-order hold]]", "[[Aliasing]]"]
---

# Instantaneous phase and frequency

In 1922, according to Nahin, John Renshaw Carson defined the instantaneous frequency of a signal "as the time derivative of the signal's phase angle." In frequency modulation, instantaneous frequency describes the frequency varying above and below the carrier frequency, at the audio tone frequency.   
Instantaneous phase and frequency are important concepts in signal processing that occur in the context of the representation and analysis of time-varying functions. The instantaneous phase (also known as local phase or simply phase) of a complex-valued function s(t), is the real-valued function:

  
    
      
        φ
        t
        =
        arg
         
        s
        t
        }
        ,
      
    
    
  

where arg is the complex argument function.
The instantaneous frequency is the temporal rate of change of the instantaneous phase.
And for a real-valued function s(t), it is determined from the function's analytic representation, sa(t):

  
    
      
        
          
            
              
                φ
                t
              
              
                
                arg
                 
                
                  s
                  
                    
                      a
                    
                  
                
                t
                }
              
            
            
              
              
                
                arg
                 
                s
                t
                +
                j
                
                  
                    
                      s
                      ^
                    
                  
                
                t
                }
                ,
              
            
          
        
      
    
    
  

where 
  
    
      
        
          
            
              s
              ^
            
          
        
        t
      
    
    
  
 represents the Hilbert transform of s(t).
When φ(t) is constrained to its principal value, either the interval (−π, π] or [0, 2π), it is called wrapped phase. Otherwise it is called unwrapped phase, which is a continuous function of argument t, assuming sa(t) is a continuous function of t. Unless otherwise indicated, the continuous form should be inferred.

## Related

- [[Almost periodic function]]
- [[Analytic signal]]
- [[First-order hold]]
- [[Linear canonical transformation]]
- [[Linear time-invariant system]]
- [[Sampling (signal processing)]]
- [[Short-time Fourier transform]]
- [[Whittaker–Shannon interpolation formula]]
- [[Zero-order hold]]
- [[Aliasing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Instantaneous_phase_and_frequency