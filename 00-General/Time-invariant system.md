---
title: "Time-invariant system"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Time-invariant_system"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Time-invariant system

In control theory, a time-invariant (TI) system has a time-dependent system function that is not a direct function of time. Such systems are regarded as a class of systems in the field of system analysis. The time-dependent system function is a function of the time-dependent input function. If this function depends only indirectly on the time-domain (via the input function, for example), then that is a system that would be considered time-invariant. Conversely, any direct dependence on the time-domain of the system function could be considered as a "time-varying system".
Mathematically speaking, "time-invariance" of a system is the following property:

Given a system with a time-dependent output function ⁠
  
    
      
        y
        t
      
    
    
  
⁠, and a time-dependent input function ⁠
  
    
      
        x
        t
      
    
    
  
⁠, the system will be considered time-invariant if a time-delay on the input ⁠
  
    
      
        x
        t
        δ
      
    
    
  
⁠ directly equates to a time-delay of the output ⁠
  
    
      
        y
        t
        δ
      
    
    
  
⁠ function. For example, if time ⁠
  
    
      
        t
      
    
    
  
⁠ is "elapsed time", then "time-invariance" implies that the relationship between the input function ⁠
  
    
      
        x
        t
      
    
    
  
⁠ and the output function ⁠
  
    
      
        y
        t
      
    
    
  
⁠ is constant with respect to time ⁠
  
    
      
        t
        :
      
    
    
  
⁠

  
    
      
        y
        t
        =
        f
        x
        t
        ,
        t
        =
        f
        x
        t
        )
        .
      
    
    
  

In the language of signal processing, this property can be satisfied if the transfer function of the system is not a direct function of time except as expressed by the input and output.
In the context of a system schematic, this property can also be stated as follows, as shown in the figure to the right:

If a system is time-invariant then the system block commutes with an arbitrary delay.
If a time-invariant system is also linear, it is the subject of linear time-invariant theory (linear time-invariant) with direct applications in NMR spectroscopy, seismology, circuits, signal processing, control theory, and other technical areas. Nonlinear time-invariant systems lack a comprehensive, governing theory. Discrete time-invariant systems are known as shift-invariant systems. Systems which lack the time-invariant property are studied as time-variant systems.

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

- Wikipedia: https://en.wikipedia.org/wiki/Time-invariant_system