---
title: "Minimum energy control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Minimum_energy_control"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Minimum energy control

In control theory, the minimum energy control is the control 
  
    
      
        u
        t
      
    
    
  
 that will bring a linear time invariant system to a desired state with a minimum expenditure of energy.
Let the linear time invariant (LTI) system be

  
    
      
        
          
            
              
                x
              
              ˙
            
          
        
        t
        =
        A
        
          x
        
        t
        +
        B
        
          u
        
        t
      
    
    
  

  
    
      
        
          y
        
        t
        =
        C
        
          x
        
        t
        +
        D
        
          u
        
        t
      
    
    
  

with initial state 
  
    
      
        x
        
          t
          
            0
          
        
        =
        
          x
          
            0
          
        
      
    
    
  
.  One seeks an input 
  
    
      
        u
        t
      
    
    
  
 so that the system will be in the state 
  
    
      
        
          x
          
            1
          
        
      
    
    
  
 at time 
  
    
      
        
          t
          
            1
          
        
      
    
    
  
, and for any other input 
  
    
      
        
          
            
              u
              ¯
            
          
        
        t
      
    
    
  
, which also drives the system from 
  
    
      
        
          x
          
            0
          
        
      
    
    
  
 to 
  
    
      
        
          x
          
            1
          
        
      
    
    
  
 at time 
  
    
      
        
          t
          
            1
          
        
      
    
    
  
, the energy expenditure would be larger, i.e., 

  
    
      
        
          ∫
          
            
              t
              
                0
              
            
          
          
            
              t
              
                1
              
            
          
        
        
          
            
              
                u
                ¯
              
            
          
          
          
        
        t
        
          
            
              u
              ¯
            
          
        
        t
        d
        t
         
        ≥
         
        
          ∫
          
            
              t
              
                0
              
            
          
          
            
              t
              
                1
              
            
          
        
        
          u
          
          
        
        t
        u
        t
        d
        t
        .
      
    
    
  

To choose this input, first compute the controllability Gramian

  
    
      
        
          W
          
            c
          
        
        t
        =
        
          ∫
          
            
              t
              
                0
              
            
          
          
            t
          
        
        
          e
          
            A
            t
            τ
          
        
        B
        
          B
          
          
        
        
          e
          
            
              A
              
              
            
            t
            τ
          
        
        d
        τ
        .
      
    
    
  

Assuming  
  
    
      
        
          W
          
            c
          
        
      
    
    
  
 is nonsingular (if and only if the system is controllable), the minimum energy control is then

  
    
      
        u
        t
        =
        
          B
          
          
        
        
          e
          
            
              A
              
              
            
            
              t
              
                1
              
            
            t
          
        
        
          W
          
            c
          
          
            1
          
        
        
          t
          
            1
          
        
        [
        
          e
          
            A
            
              t
              
                1
              
            
            
              t
              
                0
              
            
          
        
        
          x
          
            0
          
        
        
          x
          
            1
          
        
        .
      
    
    
  

Substitution into the solution

  
    
      
        x
        t
        =
        
          e
          
            A
            t
            
              t
              
                0
              
            
          
        
        
          x
          
            0
          
        
        
          ∫
          
            
              t
              
                0
              
            
          
          
            t
          
        
        
          e
          
            A
            t
            τ
          
        
        B
        u
        τ
        d
        τ
      
    
    
  

verifies the achievement of state 
  
    
      
        
          x
          
            1
          
        
      
    
    
  
 at 
  
    
      
        
          t
          
            1
          
        
      
    
    
  
.

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

- Wikipedia: https://en.wikipedia.org/wiki/Minimum_energy_control