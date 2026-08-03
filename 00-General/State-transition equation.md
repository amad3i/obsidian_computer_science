---
title: "State-transition equation"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/State-transition_equation"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# State-transition equation

The state-transition equation is defined as the solution of the linear homogeneous state equation. The linear time-invariant state equation given by

  
    
      
        
          
            
              d
              
                x
              
              t
            
            
              d
              t
            
          
        
        
          A
          x
        
        t
        +
        
          B
          u
        
        t
        +
        
          E
          w
        
        t
        ,
      
    
    
  

with state vector x, control vector u, vector w of additive disturbances, and fixed matrices A, B, E can be solved by using either the classical method of solving linear differential equations or the Laplace transform method. The Laplace transform solution is presented in the following equations.
The Laplace transform of the above equation yields 

  
    
      
        s
        
          X
        
        s
        −
        
          x
        
        0
        =
        
          A
          X
        
        s
        +
        
          B
          U
        
        s
        +
        
          E
          W
        
        s
      
    
    
  

where x(0) denotes initial-state vector evaluated at t = 0. Solving for X(s) gives

  
    
      
        
          X
        
        s
        =
        s
        
          I
        
        
          A
        
        
          
            1
          
        
        
          x
        
        0
        +
        s
        
          I
        
        
          A
        
        
          
            1
          
        
        
          B
          U
        
        s
        +
        
          E
          W
        
        s
        ]
        .
      
    
    
  

So, the state-transition equation can be obtained by taking inverse Laplace transform as 

  
    
      
        
          
            
              
                x
                t
              
              
                
                
                  
                    
                      L
                    
                  
                  
                    1
                  
                
                
                  
                  
                
                s
                
                  I
                
                
                  A
                
                
                  
                    1
                  
                
                
                  
                  
                
                
                  x
                
                0
                +
                
                  
                    
                      L
                    
                  
                  
                    1
                  
                
                
                  
                  
                
                s
                
                  I
                
                
                  A
                
                
                  
                    1
                  
                
                
                  B
                  U
                
                s
                +
                
                  E
                  W
                
                s
                ]
                
                  
                  
                
              
            
            
              
              
                
                
                  Φ
                
                t
                
                  x
                
                0
                +
                
                  ∫
                  
                    0
                  
                  
                    t
                  
                
                
                  Φ
                
                t
                τ
                [
                
                  B
                  u
                
                τ
                +
                
                  E
                  w
                
                τ
                ]
                d
                t
              
            
          
        
      
    
    
  

where Φ(t) is the state transition matrix.
The state-transition equation as derived above is useful only when the initial time is defined to be at t = 0. In the study of control systems, specially discrete-data control systems, it is often desirable to break up a state-transition process into a sequence of transitions, so a more flexible initial time must be chosen. Let the initial time be represented by t0 and the corresponding initial state by x(t0), and assume that the input u(t) and the disturbance w(t) are applied at t ≥ 0. 
Starting with the above equation by setting t = t0, and solving for x(0), we get 

  
    
      
        
          x
        
        0
        =
        
          Φ
        
        −
        
          t
          
            0
          
        
        
          x
        
        
          t
          
            0
          
        
        −
        
          Φ
        
        −
        
          t
          
            0
          
        
        
          ∫
          
            0
          
          
            
              t
              
                0
              
            
          
        
        
          Φ
        
        
          t
          
            0
          
        
        τ
        [
        
          B
          u
        
        τ
        +
        
          E
          w
        
        τ
        ]
        d
        τ
        .
      
    
    
  

Once the state-transition equation is determined, the output vector can be expressed as a function of the initial state.

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

- Wikipedia: https://en.wikipedia.org/wiki/State-transition_equation