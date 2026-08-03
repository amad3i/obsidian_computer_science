---
title: "Higher-order sinusoidal input describing function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Higher-order_sinusoidal_input_describing_function"
wikipedia_categories: ["Control theory", "Electrical engineering", "Signal processing"]
related: ["[[First-order hold]]", "[[Zero-order hold]]", "[[Asymptotic gain model]]", "[[Derivation of the Routh array]]", "[[Frequency response]]", "[[Group delay and phase delay]]", "[[Head-related transfer function]]", "[[Instantaneous phase and frequency]]", "[[Linear time-invariant system]]", "[[Masreliez's theorem]]"]
---

# Higher-order sinusoidal input describing function

== Definition ==
The higher-order sinusoidal input describing functions (HOSIDF) were first introduced by dr. ir. P.W.J.M. Nuij. The HOSIDFs are an extension of the sinusoidal input describing function which describe the response (gain and phase) of a system at harmonics of the base frequency of a sinusoidal input signal. The HOSIDFs bear an intuitive resemblance to the classical frequency response function and define the periodic output of a stable, causal, time invariant nonlinear system to a sinusoidal input signal:

  
    
      
        u
        t
        =
        γ
         
        
          ω
          
            0
          
        
        t
        
          φ
          
            0
          
        
      
    
    
  

This output is denoted by 
  
    
      
        y
        t
      
    
    
  
 and consists of harmonics of the input frequency:

  
    
      
        y
        t
        =
        
          ∑
          
            k
            0
          
          
            K
          
        
        
          |
        
        
          H
          
            k
          
        
        
          ω
          
            0
          
        
        ,
        γ
        
          |
        
        
          γ
          
            k
          
        
         
        
          
          
        
        k
        
          ω
          
            0
          
        
        t
        
          φ
          
            0
          
        
        +
        ∠
        
          H
          
            k
          
        
        
          ω
          
            0
          
        
        ,
        γ
        
          
          
        
      
    
    
  

Defining the single sided spectra of the input and output as 
  
    
      
        U
        ω
      
    
    
  
 and 
  
    
      
        Y
        ω
      
    
    
  
, such that 
  
    
      
        
          |
        
        U
        
          ω
          
            0
          
        
        
          |
        
        γ
      
    
    
  
 yields the definition of the k-th order HOSIDF:

  
    
      
        
          H
          
            k
          
        
        
          ω
          
            0
          
        
        ,
        γ
        =
        
          
            
              Y
              k
              
                ω
                
                  0
                
              
              ,
              γ
            
            
              
                U
                
                  k
                
              
              
                ω
                
                  0
                
              
              ,
              γ
            
          
        
      
    
    
  

== Advantages and applications ==
The application and analysis of the HOSIDFs is advantageous both when a nonlinear model is already identified and when no model is known yet. In the latter case the HOSIDFs require little model assumptions and can easily be identified while requiring no advanced mathematical tools. Moreover, even when a model is already identified, the analysis of the HOSIDFs often yields significant advantages over the use of the identified nonlinear model. First of all, the HOSIDFs are intuitive in their identification and interpretation while other nonlinear model structures often yield limited direct information about the behavior of the system in practice. Furthermore, the HOSIDFs provide a natural extension of the widely used sinusoidal describing functions in case nonlinearities cannot be neglected. In practice the HOSIDFs have two distinct applications: Due to their ease of identification, HOSIDFs provide a tool to provide on-site testing during system design. Finally, the application of HOSIDFs to (nonlinear) controller design for nonlinear systems is shown to yield significant advantages over conventional time domain based tuning.

## Related

- [[First-order hold]]
- [[Zero-order hold]]
- [[Asymptotic gain model]]
- [[Derivation of the Routh array]]
- [[Frequency response]]
- [[Group delay and phase delay]]
- [[Head-related transfer function]]
- [[Instantaneous phase and frequency]]
- [[Linear time-invariant system]]
- [[Masreliez's theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Higher-order_sinusoidal_input_describing_function