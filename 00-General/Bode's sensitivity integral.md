---
title: "Bode's sensitivity integral"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Bode's_sensitivity_integral"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Bode's sensitivity integral

Bode's sensitivity integral, discovered by Hendrik Wade Bode, is a formula that quantifies some of the limitations in feedback control of linear parameter-invariant systems. Let L be the loop transfer function, and S be the sensitivity function. 
In the diagram, P is a dynamical process that has a transfer function P(s). The controller C has the transfer function C(s). The controller attempts to cause the process output y to track the reference input r. Disturbances d and measurement noise n may cause undesired deviations of the output. Loop gain is defined by L(s) = P(s)C(s).
The following holds:

  
    
      
        
          ∫
          
            0
          
          
            ∞
          
        
         
        
          |
        
        S
        j
        ω
        
          |
        
        
        d
        ω
        
          ∫
          
            0
          
          
            ∞
          
        
         
        
          |
          
            
              1
              
                1
                L
                j
                ω
              
            
          
          |
        
        
        d
        ω
        π
        ∑
        Re
         
        
          p
          
            k
          
        
        −
        
          
            π
            2
          
        
        
          
            s
            →
            ∞
          
        
        s
        L
        s
        ,
      
    
    
  

where 
  
    
      
        
          p
          
            k
          
        
      
    
    
  
 are the poles of L in the right half-plane (unstable poles).
If L has at least two more poles than zeros, and has no poles in the right half-plane (is stable), the equation simplifies to

  
    
      
        
          ∫
          
            0
          
          
            ∞
          
        
         
        
          |
        
        S
        j
        ω
        
          |
        
        
        d
        ω
        0.
      
    
    
  

This equality shows that if sensitivity to disturbance is suppressed at some frequency range, it is necessarily increased at some other range. This has been called the "waterbed effect".
For multi-input, multi-output (MIMO) systems, if the loop gain L(s) has entries with pole excess of at least two, the theorem generalizes to

  
    
      
        
          ∫
          
            0
          
          
            ∞
          
        
         
        
          |
        
        det
        S
        j
        ω
        
          |
        
        
        d
        ω
        π
        ∑
        Re
         
        
          p
          
            k
          
        
        ,
      
    
    
  

where 
  
    
      
        
          p
          
            k
          
        
      
    
    
  
 are the unstable poles of L(s).

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

- Wikipedia: https://en.wikipedia.org/wiki/Bode's_sensitivity_integral