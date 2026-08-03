---
title: "Iso-damping"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Iso-damping"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Iso-damping

Iso-damping is a desirable system property referring to a state where the open-loop phase Bode plot is flat—i.e., the phase derivative with respect to the frequency is zero, at a given frequency called the "tangent frequency", 
  
    
      
        
          
            ω
          
          
            c
          
        
      
    
    
  
.  At the "tangent frequency" the Nyquist curve of the open-loop system tangentially touches the sensitivity circle and the phase Bode is locally flat which implies that the system will be more robust to gain variations. For systems that exhibit iso-damping property, the overshoots of the closed-loop step responses will remain almost constant for different values of the controller gain. This will ensure that the closed-loop system is robust to gain variations.
The iso-damping property can be expressed as 
  
    
      
        
          
            
              d
              ∠
              G
              s
            
            
              d
              s
            
          
        
        
          
            
              |
            
          
          
            s
            j
            
              ω
              
                c
              
            
          
        
        0
      
    
    
  
, or equivalently:

  
    
      
        ∠
        
          
            
              d
              G
              s
            
            
              d
              s
            
          
        
        
          
            
              |
            
          
          
            s
            j
            
              ω
              
                c
              
            
          
        
        ∠
        G
        s
        
          
            
              |
            
          
          
            s
            j
            ω
          
        
        ,
      
    
    
  

where 
  
    
      
        
          ω
          
            c
          
        
      
    
    
  
 is the tangent frequency and 
  
    
      
        G
        s
      
    
    
  
 is the open-loop system transfer function.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Iso-damping