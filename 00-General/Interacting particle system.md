---
title: "Interacting particle system"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Interacting_particle_system"
wikipedia_categories: ["Complex systems theory", "Lattice models", "Markov models", "Self-organization", "Spatial processes"]
related: ["[[Stochastic cellular automaton]]", "[[Baum–Welch algorithm]]", "[[Bernoulli scheme]]", "[[Burst error]]", "[[CLAWS (linguistics)]]", "[[Complex network]]", "[[Complexity]]", "[[Dependability state model]]", "[[Detailed balance]]", "[[Diffusion model]]"]
---

# Interacting particle system

In probability theory, an interacting particle system (IPS) is a stochastic process 
  
    
      
        X
        t
        
          
            t
            ∈
            
              
                R
              
              
              
            
          
        
      
    
    
  
 on some configuration space 
  
    
      
        Ω
        
          S
          
            G
          
        
      
    
    
  
 given by a site space, a countably-infinite-order graph 
  
    
      
        G
      
    
    
  
 and a local state space, a compact metric space 
  
    
      
        S
      
    
    
  
. More precisely IPS are continuous-time Markov jump processes describing the collective behavior of stochastically interacting components. IPS are the continuous-time analogue of stochastic cellular automata.
Among the main examples are the voter model, the contact process, the asymmetric simple exclusion process (ASEP), the Glauber dynamics and in particular the stochastic Ising model.
IPS are usually defined via their Markov generator giving rise to a unique Markov process using Markov semigroups and the Hille-Yosida theorem. The generator again is given via so-called transition rates 
  
    
      
        
          c
          
            Λ
          
        
        η
        ,
        ξ
        >
        0
      
    
    
  
 where 
  
    
      
        Λ
        ⊂
        G
      
    
    
  
 is a finite set of sites and 
  
    
      
        η
        ,
        ξ
        ∈
        Ω
      
    
    
  
 with 
  
    
      
        
          η
          
            i
          
        
        
          ξ
          
            i
          
        
      
    
    
  
 for all 
  
    
      
        i
        ∉
        Λ
      
    
    
  
. The rates describe exponential waiting times of the process to jump from configuration 
  
    
      
        η
      
    
    
  
 into configuration 
  
    
      
        ξ
      
    
    
  
. More generally the transition rates are given in form of a finite measure 
  
    
      
        
          c
          
            Λ
          
        
        η
        ,
        d
        ξ
      
    
    
  
 on 
  
    
      
        
          S
          
            Λ
          
        
      
    
    
  
.
The generator 
  
    
      
        L
      
    
    
  
 of an IPS has the following form. First, the domain of 
  
    
      
        L
      
    
    
  
 is a subset of the space of "observables", that is, the set of real valued continuous functions on the configuration space 
  
    
      
        Ω
      
    
    
  
. Then for any observable 
  
    
      
        f
      
    
    
  
 in the domain of 
  
    
      
        L
      
    
    
  
, one has

  
    
      
        L
        f
        η
        =
        
          ∑
          
            Λ
          
        
        
          ∫
          
            ξ
            :
            
              ξ
              
                
                  Λ
                  
                    c
                  
                
              
            
            
              η
              
                
                  Λ
                  
                    c
                  
                
              
            
          
        
        
          c
          
            Λ
          
        
        η
        ,
        d
        ξ
        [
        f
        ξ
        −
        f
        η
        ]
      
    
    
  
.
For example, for the stochastic Ising model we have 
  
    
      
        G
        
          
            Z
          
          
            d
          
        
      
    
    
  
, 
  
    
      
        S
        {
        1
        ,
        1
      
    
    
  
, 
  
    
      
        
          c
          
            Λ
          
        
        0
      
    
    
  
 if 
  
    
      
        Λ
        ≠
        i
      
    
    
  
 for some 
  
    
      
        i
        ∈
        G
      
    
    
  
 and

  
    
      
        
          c
          
            i
          
        
        η
        ,
        
          η
          
            i
          
        
        =
        exp
         
        −
        β
        
          ∑
          
            j
            :
            
              |
            
            j
            i
            
              |
            
            1
          
        
        
          η
          
            i
          
        
        
          η
          
            j
          
        
      
    
    
  

where 
  
    
      
        
          η
          
            i
          
        
      
    
    
  
 is the configuration equal to 
  
    
      
        η
      
    
    
  
 except it is flipped at site 
  
    
      
        i
      
    
    
  
. 
  
    
      
        β
      
    
    
  
 is a new parameter modeling the inverse temperature.

## Related

- [[Stochastic cellular automaton]]
- [[Baum–Welch algorithm]]
- [[Bernoulli scheme]]
- [[Burst error]]
- [[CLAWS (linguistics)]]
- [[Complex network]]
- [[Complexity]]
- [[Dependability state model]]
- [[Detailed balance]]
- [[Diffusion model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interacting_particle_system