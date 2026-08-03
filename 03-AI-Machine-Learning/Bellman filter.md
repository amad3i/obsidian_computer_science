---
title: "Bellman filter"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Bellman_filter"
wikipedia_categories: ["Control theory", "Nonlinear filters", "Signal estimation", "Time series"]
related: ["[[Covariance intersection]]", "[[Kalman filter]]", "[[Moving horizon estimation]]", "[[Projection filters]]", "[[Switching Kalman filter]]", "[[Unscented transform]]", "[[Filtering problem (stochastic processes)]]", "[[Particle filter]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]"]
---

# Bellman filter

The Bellman filter is a recursive algorithm for estimating a sequence of unobserved (latent) states in a state-space model from noisy observations. It is typically formulated for models with a linear–Gaussian state transition and a possibly nonlinear and/or non-Gaussian observation density, and it updates the state by solving a per-time-step optimisation problem involving 
  
    
      
         
        p
        
          y
          
            t
          
        
        
          |
        
        
          x
          
            t
          
        
      
    
    
  
. Under linear–Gaussian observation models, it reduces to the standard Kalman filter update.
From a dynamic-programming perspective, the Bellman filter applies Bellman's principle of optimality to a mode-estimation problem, yielding a recursion for an (online) maximisation objective whose maximiser is a filtered state estimate. In contrast with grid-based maximisation (as in the Viterbi algorithm for models with discrete states), the Bellman filter keeps the state space continuous and replaces the exact Bellman value functions by parametric (typically quadratic) function-space approximations, which makes the recursion computationally feasible in moderate to high dimensions.

## Related

- [[Covariance intersection]]
- [[Kalman filter]]
- [[Moving horizon estimation]]
- [[Projection filters]]
- [[Switching Kalman filter]]
- [[Unscented transform]]
- [[Filtering problem (stochastic processes)]]
- [[Particle filter]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bellman_filter