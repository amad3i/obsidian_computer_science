---
title: "Integral sliding mode"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Integral_sliding_mode"
wikipedia_categories: ["Applied mathematics stubs", "Control theory"]
related: ["[[Artstein's theorem]]", "[[Fractional-order control]]", "[[Minimal realization]]", "[[Parallel parking problem]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Adjoint state method]]", "[[Advanced process control]]"]
---

# Integral sliding mode

== Integral sliding mode control ==
Integral sliding mode control (ISM) is a modification of sliding mode control designed to compensate matched perturbations in nonlinear control systems. 
The method introduces an integral sliding variable that allows matched perturbations compensation by means of a sliding mode control component ensuring the sliding mode on a virtual integral sliding surface.
In this note systems solutions are interpreted in the sense of Filippov solution.

== Mathematical formulation ==
Consider a nonlinear control system with matched disturbance

  
    
      
        
          
            
              x
              ˙
            
          
        
        f
        x
        ,
        t
        +
        B
        x
        (
        u
        h
        x
        ,
        t
        )
        ,
      
    
    
  

where 
  
    
      
        x
        ∈
        
          
            R
          
          
            n
          
        
      
    
    
  
, 
  
    
      
        u
        ∈
        
          
            R
          
          
            m
          
        
      
    
    
  
, 
  
    
      
        r
        a
        n
        k
        B
        =
        m
      
    
    
  
, and 
  
    
      
        h
        x
        ,
        t
      
    
    
  
 is a bounded perturbation entering into the system through the same channel as the control input 
  
    
      
        B
        x
      
    
    
  
.
The objective is to ensure that the trajectories of the perturbed system converge to the trajectories of the nominal system

  
    
      
        
          
            
              
                x
                ˙
              
            
          
          
            0
          
        
        f
        
          x
          
            0
          
        
        ,
        t
        +
        B
        
          x
          
            0
          
        
        
          u
          
            0
          
        
        .
      
    
    
  

== Control Scheme ==
Matthews and DeCarlo  proposed selecting the control input in the form

  
    
      
        u
        
          u
          
            0
          
        
        
          u
          
            I
            S
            M
          
        
        ,
      
    
    
  

where 
  
    
      
        
          u
          
            0
          
        
      
    
    
  
 is a nominal controller for the nominal system and 
  
    
      
        
          u
          
            I
            S
            M
          
        
      
    
    
  
 is a sliding mode controller compensating the disturbance 
  
    
      
        h
        x
        ,
        t
      
    
    
  
.
They introduced a virtual integral sliding variable

  
    
      
        σ
        t
        =
        G
        x
        t
        −
        G
        x
        0
        −
        
          ∫
          
            0
          
          
            t
          
        
        G
        B
        x
        τ
        )
        
          u
          
            0
          
        
        τ
        +
        G
        f
        x
        τ
        )
        
        d
        τ
        .
      
    
    
  

The variable 
  
    
      
        σ
        t
      
    
    
  
 is called virtual integral because it extends real system states and depends on the integral of the system dynamics and value of nominal control.

== Control laws ==
If 
  
    
      
        det
        G
        B
        ≠
        0
      
    
    
  
, a sliding mode controller can be constructed.
One possible choice is a unit control law

  
    
      
        
          u
          
            I
            S
            M
          
        
        −
        ρ
        x
        ,
        t
        
          
            
              
                σ
                ¯
              
            
            
              ‖
              
                
                  
                    σ
                    ¯
                  
                
              
              
                ‖
                
                  2
                
              
            
          
        
        ,
      
    
    
  

where  

  
    
      
        
          
            
              σ
              ¯
            
          
        
        (
        G
        B
        
          
            T
          
        
        σ
      
    
    
  

is an auxiliary switching variable and the  gain for  
  
    
      
        
          u
          
            I
            S
            M
          
        
      
    
    
  
 should be chosen as

  
    
      
        ρ
        x
        ,
        t
        ≥
        ‖
        h
        x
        ,
        t
        
          ‖
          
            2
          
        
        .
      
    
    
  

Another option is a relay control law 

  
    
      
        
          u
          
            I
            S
            M
          
        
        −
        K
        x
        ,
        t
        S
        i
        g
        n
        
          
            
              σ
              ¯
            
          
        
        =
        K
        x
        ,
        t
        [
        s
        i
        g
        n
        
          
            
              
                σ
                ¯
              
            
          
          
            1
          
        
        ,
        …
        ,
        s
        i
        g
        n
        
          
            
              
                σ
                ¯
              
            
          
          
            m
          
        
        
          
            T
          
        
        ,
      
    
    
  

where the gain satisfies

  
    
      
        K
        x
        ,
        t
        >
        ‖
        h
        x
        ,
        t
        
          ‖
          
            ∞
          
        
        .
      
    
    
  

Once the sliding mode on the set

  
    
      
        σ
        t
        =
        0
      
    
    
  

is reached, the trajectories of the perturbed and nominal systems coincide.
A fundamental structural difference exists between classical sliding modes and integral sliding modes. In classical sliding mode control the sliding motion evolves on a manifold of dimension 
  
    
      
        n
        m
      
    
    
  
. In contrast, in integral sliding mode control the sliding dynamics evolves in the full state space of dimension 
  
    
      
        n
      
    
    
  
.

== Important Properties of ISM ==
Utkin and Shi  introduced the term integral sliding mode and emphasized two important properties.

If the initial condition 
  
    
      
        x
        0
      
    
    
  
 is known, i.e. 
  
    
      
        σ
        0
        =
        0
      
    
    
  
, the sliding motion 
  
    
      
        σ
        t
        =
        0
      
    
    
  
 exists for all 
  
    
      
        t
        ≥
        
          t
          
            0
          
        
      
    
    
  
. This eliminates the reaching phase so that the trajectories of the perturbed and nominal systems coincide from the initial moment.
Filtering the discontinuous control 
  
    
      
        
          u
          
            I
            S
            M
          
        
      
    
    
  
 makes it possible to reconstruct the perturbation 
  
    
      
        G
        B
        h
        x
        t
        ,
        t
      
    
    
  
.

== Theoretical extensions ==
Further theoretical  extensions of integral sliding mode control include several research directions.
Observer and controller design.  
Integral sliding modes can be used for the design of robust observers and output-feedback controllers for perturbed systems.
Integral sliding modes in the presence of unmatched disturbances.
Castaños and Fridman showed that in the presence of unmatched perturbation it is reasonable to select the projection matrix in the form

  
    
      
        G
        
          B
          
          
        
        ,
      
    
    
  

where 
  
    
      
        
          B
          
          
        
        (
        
          B
          
            T
          
        
        B
        
          
            1
          
        
        
          B
          
            T
          
        
      
    
    
  
 to minimize it. 
For nonlinear case it was done in.
Continuous controllers based on super-twisting algorithms.  
Discontinuous sliding mode controllers can be replaced by continuous super-twisting based control algorithms.
This approach has two main advantages: 

chattering adjustment;
perturbation reconstruction without filtration,
and important disadvantage: it has initial phase.

== References ==

*(note truncated for size; full article at the source link below)*

## Related

- [[Artstein's theorem]]
- [[Fractional-order control]]
- [[Minimal realization]]
- [[Parallel parking problem]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Adjoint state method]]
- [[Advanced process control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Integral_sliding_mode