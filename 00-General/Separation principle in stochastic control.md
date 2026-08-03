---
title: "Separation principle in stochastic control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Separation_principle_in_stochastic_control"
wikipedia_categories: ["Control theory", "Stochastic control"]
related: ["[[Optimal projection equations]]", "[[Robust control]]", "[[Separation principle]]", "[[Stochastic control]]", "[[Witsenhausen's counterexample]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]"]
---

# Separation principle in stochastic control

The separation principle is one of the fundamental principles of stochastic control theory, which states that the problems of optimal control and state estimation can be decoupled under certain conditions. In its most basic formulation it deals with a linear stochastic system

  
    
      
        
          
            
              
                d
                x
              
              
                
                A
                t
                x
                t
                
                d
                t
                
                  B
                  
                    1
                  
                
                t
                u
                t
                
                d
                t
                
                  B
                  
                    2
                  
                
                t
                
                d
                w
              
            
            
              
                d
                y
              
              
                
                C
                t
                x
                t
                
                d
                t
                D
                t
                
                d
                w
              
            
          
        
      
    
    
  

with a state process 
  
    
      
        x
      
    
    
  
, an output process 
  
    
      
        y
      
    
    
  
 and a control 
  
    
      
        u
      
    
    
  
, where 
  
    
      
        w
      
    
    
  
 is a vector-valued Wiener process, 
  
    
      
        x
        0
      
    
    
  
 is a zero-mean Gaussian random vector independent of 
  
    
      
        w
      
    
    
  
, 
  
    
      
        y
        0
        =
        0
      
    
    
  
, and 
  
    
      
        A
      
    
    
  
, 
  
    
      
        
          B
          
            1
          
        
      
    
    
  
, 
  
    
      
        
          B
          
            2
          
        
      
    
    
  
, 
  
    
      
        C
      
    
    
  
, 
  
    
      
        D
      
    
    
  
 are matrix-valued functions which generally are taken to be continuous of bounded variation. Moreover, 
  
    
      
        D
        
          D
          ′
        
      
    
    
  
 is  nonsingular on some interval 
  
    
      
        0
        ,
        T
      
    
    
  
. The problem is to design an output feedback law 
  
    
      
        π
        :
        
        y
        ↦
        u
      
    
    
  
 which maps the observed process 
  
    
      
        y
      
    
    
  
 to the control input 
  
    
      
        u
      
    
    
  
 in a nonanticipatory manner so as to minimize the functional

  
    
      
        J
        u
        =
        
          E
        
        
          
            
              ∫
              
                0
              
              
                T
              
            
            x
            t
            
              ′
            
            Q
            t
            x
            t
            
            d
            t
            
              ∫
              
                0
              
              
                T
              
            
            u
            t
            
              ′
            
            R
            t
            u
            t
            
            d
            t
            x
            T
            
              ′
            
            S
            x
            T
          
        
        ,
      
    
    
  

where 
  
    
      
        
          E
        
      
    
    
  
 denotes expected value, prime (
  
    
      
        
          
          ′
        
      
    
    
  
) denotes transpose. and 
  
    
      
        Q
      
    
    
  
 and 
  
    
      
        R
      
    
    
  
 are continuous matrix functions of bounded variation, 
  
    
      
        Q
        t
      
    
    
  
 is positive semi-definite and 
  
    
      
        R
        t
      
    
    
  
 is positive definite for all 
  
    
      
        t
      
    
    
  
. Under suitable conditions, which need to be properly stated,  the optimal policy 
  
    
      
        π
      
    
    
  
 can be chosen in the form

  
    
      
        u
        t
        =
        K
        t
        
          
            
              x
              ^
            
          
        
        t
        ,
      
    
    
  

where 
  
    
      
        
          
            
              x
              ^
            
          
        
        t
      
    
    
  
 is the linear least-squares estimate of the state vector 
  
    
      
        x
        t
      
    
    
  
 obtained from the Kalman filter

  
    
      
        d
        
          
            
              x
              ^
            
          
        
        A
        t
        
          
            
              x
              ^
            
          
        
        t
        
        d
        t
        
          B
          
            1
          
        
        t
        u
        t
        
        d
        t
        L
        t
        (
        d
        y
        C
        t
        
          
            
              x
              ^
            
          
        
        t
        
        d
        t
        ,
        
        
          
            
              x
              ^
            
          
        
        0
        =
        0
        ,
      
    
    
  

where 
  
    
      
        K
      
    
    
  
 is the gain of the optimal linear-quadratic regulator obtained by taking 
  
    
      
        
          B
          
            2
          
        
        D
        0
      
    
    
  
 and 
  
    
      
        x
        0
      
    
    
  
 deterministic, and where 
  
    
      
        L
      
    
    
  
 is the  Kalman gain. There is also a non-Gaussian version of this problem (to be discussed below) where the Wiener process  
  
    
      
        w
      
    
    
  
 is replaced by a more general square-integrable martingale with possible jumps. In this case, the Kalman filter needs to be replaced by a nonlinear filter providing an estimate of the (strict sense) conditional mean

  
    
      
        
          
            
              x
              ^
            
          
        
        t
        =
        E
         
        x
        t
        ∣
        
          
            
              Y
            
          
          
            t
          
        
        ,
      
    
    
  

where

  
    
      
        
          
            
              Y
            
          
          
            t
          
        
        :=
        σ
        y
        τ
        ,
        τ
        ∈
        0
        ,
        t
        }
        ,
        
        0
        ≤
        t
        ≤
        T
        ,
      
    
    
  

is the filtration generated by the output process; i.e., the family of increasing sigma fields representing the data as it is produced.
In the early literature on the separation principle it was common to allow as admissible controls 
  
    
      
        u
      
    
    
  
 all processes that are adapted to the filtration 
  
    
      
        
          
            
              Y
            
          
          
            t
          
        
        ,
        
        0
        ≤
        t
        ≤
        T
      
    
    
  
. This is equivalent to allowing all non-anticipatory Borel functions as feedback laws, which raises the question of existence of a unique solution to the equations of the feedback loop. Moreover, one needs to exclude the possibility that a nonlinear controller extracts more information from the data than what is possible with a linear control law.

*(note truncated for size; full article at the source link below)*

## Related

- [[Optimal projection equations]]
- [[Robust control]]
- [[Separation principle]]
- [[Stochastic control]]
- [[Witsenhausen's counterexample]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Separation_principle_in_stochastic_control