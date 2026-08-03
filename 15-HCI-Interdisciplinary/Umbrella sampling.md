---
title: "Umbrella sampling"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Umbrella_sampling"
wikipedia_categories: ["Computational chemistry", "Computational physics", "Molecular dynamics", "Monte Carlo methods", "Theoretical chemistry"]
related: ["[[Car–Parrinello molecular dynamics]]", "[[Transition path sampling]]", "[[Cell lists]]", "[[Combining rules]]", "[[Computational chemical methods in solid-state physics]]", "[[Computational chemistry]]", "[[Constraint (computational chemistry)]]", "[[Hartree–Fock method]]", "[[Intracule]]", "[[Local elevation]]"]
---

# Umbrella sampling

Umbrella sampling is a technique in computational physics and chemistry, used to improve sampling of a system (or different systems) where ergodicity is hindered by the form of the system's energy landscape. It was first suggested by Torrie and Valleau in 1977. It is a particular physical application of the more general importance sampling in statistics.
Systems in which an energy barrier separates two regions of configuration space may suffer from poor sampling. In Metropolis Monte Carlo runs, the low probability of overcoming the potential barrier can leave inaccessible configurations poorly sampled—or even entirely unsampled—by the simulation. An easily visualised example occurs with a solid at its melting point: considering the state of the system with an order parameter Q, both liquid (low Q) and solid (high Q) phases are low in energy, but are separated by a free-energy barrier at intermediate values of Q. This prevents the simulation from adequately sampling both phases.
Umbrella sampling is a means of "bridging the gap" in this situation. The standard Boltzmann weighting for Monte Carlo sampling is replaced by a potential chosen to cancel the influence of the energy barrier present. The Markov chain generated has a distribution given by

  
    
      
        π
        
          
            r
          
          
            N
          
        
        =
        
          
            
              w
              
                
                  
                    r
                  
                
                
                  N
                
              
              exp
               
              
                
                  
                    
                      
                        
                          U
                          
                            
                              r
                            
                            
                              N
                            
                          
                        
                        
                          
                            k
                            
                              B
                            
                          
                          T
                        
                      
                    
                  
                
              
            
            
              ∫
              
                w
                
                  
                    r
                  
                  
                    ′
                    
                      N
                    
                  
                
                exp
                 
                
                  
                    
                      
                        
                          
                            U
                            
                              
                                r
                              
                              
                                ′
                                
                                  N
                                
                              
                            
                          
                          
                            
                              k
                              
                                B
                              
                            
                            T
                          
                        
                      
                    
                  
                
                
                d
                
                  
                    r
                  
                  
                    ′
                    
                      N
                    
                  
                
              
            
          
        
        ,
      
    
    
  

with U the potential energy, w(rN) a function chosen to promote configurations that would otherwise be inaccessible to a Boltzmann-weighted Monte Carlo run. In the example above, w may be chosen such that w = w(Q), taking high values at intermediate Q and low values at low/high Q, facilitating barrier crossing.
Values for a thermodynamic property A deduced from a sampling run performed in this manner can be transformed into canonical-ensemble values by applying the formula

  
    
      
        ⟨
        A
        ⟩
        
          
            
              ⟨
              A
              
                /
              
              w
              
                ⟩
                
                  π
                
              
            
            
              ⟨
              1
              
                /
              
              w
              
                ⟩
                
                  π
                
              
            
          
        
        ,
      
    
    
  

with the 
  
    
      
        π
      
    
    
  
 subscript indicating values from the umbrella-sampled simulation.
The effect of introducing the weighting function w(rN) is equivalent to adding a biasing potential

  
    
      
        V
        
          
            r
          
          
            N
          
        
        =
        
          k
          
            B
          
        
        T
         
        w
        
          
            r
          
          
            N
          
        
      
    
    
  

to the potential energy of the system.
If the biasing potential is strictly a function of a reaction coordinate or order parameter 
  
    
      
        Q
      
    
    
  
, then the (unbiased) free-energy profile on the reaction coordinate can be calculated by subtracting the biasing potential from the biased free-energy profile:

  
    
      
        
          F
          
            0
          
        
        Q
        =
        
          F
          
            π
          
        
        Q
        −
        V
        Q
        ,
      
    
    
  

where 
  
    
      
        
          F
          
            0
          
        
        Q
      
    
    
  
 is the free-energy profile of the unbiased system, and 
  
    
      
        
          F
          
            π
          
        
        Q
      
    
    
  
 is the free-energy profile calculated for the biased, umbrella-sampled system.
Series of umbrella sampling simulations can be analyzed using the weighted histogram analysis method (WHAM) or its generalization. WHAM can be derived using the maximum likelihood method.
Subtleties exist in deciding the most computationally efficient way to apply the umbrella sampling method, as described in Frenkel and Smit's book Understanding Molecular Simulation.
Alternatives to umbrella sampling for computing potentials of mean force or reaction rates are free-energy perturbation and transition interface sampling. A further alternative, which functions in full non-equilibrium, is S-PRES.

## Related

- [[Car–Parrinello molecular dynamics]]
- [[Transition path sampling]]
- [[Cell lists]]
- [[Combining rules]]
- [[Computational chemical methods in solid-state physics]]
- [[Computational chemistry]]
- [[Constraint (computational chemistry)]]
- [[Hartree–Fock method]]
- [[Intracule]]
- [[Local elevation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Umbrella_sampling