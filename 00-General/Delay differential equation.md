---
title: "Delay differential equation"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Delay_differential_equation"
wikipedia_categories: ["Control theory", "Differential equations"]
related: ["[[Hybrid system]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]"]
---

# Delay differential equation

In mathematics, delay differential equations (DDEs) are a type of differential equation in which the derivative of the unknown function at a certain time is given in terms of the values of the function at previous times.
DDEs are also called time-delay systems,  systems with aftereffect or dead-time, hereditary systems, equations with deviating argument, or differential-difference equations. They belong to the class of systems with a functional state, i.e. partial differential equations (PDEs) which are infinite dimensional, as opposed to ordinary differential equations (ODEs) having a finite dimensional state vector. Four points may give a possible explanation of the popularity of DDEs:

Aftereffect is an applied problem: it is well known that, together with the increasing expectations of dynamic performances, engineers need their models to behave more like the real process. Many processes include aftereffect phenomena in their inner dynamics. In addition, actuators, sensors, and communication networks that are now involved in feedback control loops introduce such delays. Finally, besides actual delays, time lags are frequently used to simplify very high order models. Then, the interest for DDEs keeps on growing in all scientific areas and, especially, in control engineering.
Delay systems are still resistant to many classical controllers: one could think that the simplest approach would consist in replacing them by some finite-dimensional approximations. Unfortunately, ignoring effects which are adequately represented by DDEs is not a general alternative: in the best situation (constant and known delays), it leads to the same degree of complexity in the control design. In worst cases (time-varying delays, for instance), it is potentially disastrous in terms of stability and oscillations.
Voluntary introduction of delays can benefit the control system.
In spite of their complexity, DDEs often appear as simple infinite-dimensional models in the very complex area of partial differential equations (PDEs).
A general form of the time-delay differential equation for 
  
    
      
        x
        t
        ∈
        
          
            R
          
          
            n
          
        
      
    
    
  
 is

  
    
      
        
          
            d
            
              d
              t
            
          
        
        x
        t
        =
        f
        t
        ,
        x
        t
        ,
        
          x
          
            t
          
        
        ,
      
    
    
  

where 
  
    
      
        
          x
          
            t
          
        
        {
        x
        τ
        :
        τ
        ≤
        t
      
    
    
  
 represents the trajectory of the solution in the past. In this equation, 
  
    
      
        f
      
    
    
  
 is a functional operator from 
  
    
      
        
          R
        
        
          
            R
          
          
            n
          
        
        
          C
          
            1
          
        
        
          R
        
        ,
        
          
            R
          
          
            n
          
        
      
    
    
  
 to 
  
    
      
        
          
            R
          
          
            n
          
        
        .
      
    
    

## Related

- [[Hybrid system]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Delay_differential_equation