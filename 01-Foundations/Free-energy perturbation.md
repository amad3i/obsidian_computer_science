---
title: "Free-energy perturbation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Free-energy_perturbation"
wikipedia_categories: ["Computational chemistry", "Statistical mechanics"]
related: ["[[Thermodynamic integration]]", "[[1s Slater-type function]]", "[[Ab initio quantum chemistry methods]]", "[[Accessible surface area]]", "[[Activation strain model]]", "[[Adaptive sampling]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Alexander Boldyrev]]", "[[Basis set (chemistry)]]", "[[Bette Korber]]"]
---

# Free-energy perturbation

Free-energy perturbation (FEP) is an alchemical method based on statistical mechanics that is used in computational chemistry for computing free-energy differences from molecular dynamics or Metropolis Monte Carlo simulations. It is widely used to compute the free energy difference between two states, state A and state B.
The FEP method was introduced by Robert W. Zwanzig in 1954. According to the free-energy perturbation method, the free-energy difference for going from state A to state B is obtained from the following equation, known as the Zwanzig equation:

  
    
      
        Δ
        F
        
          A
        
        →
        
          B
        
        =
        
          F
          
            
              B
            
          
        
        
          F
          
            
              A
            
          
        
        −
        
          k
          
            B
          
        
        T
         
        
          
            ⟨
            
              exp
               
              
                
                  
                    
                      
                        
                          E
                          
                            
                              B
                            
                          
                        
                        
                          E
                          
                            
                              A
                            
                          
                        
                      
                      
                        
                          k
                          
                            B
                          
                        
                        T
                      
                    
                  
                
              
            
            ⟩
          
          
            
              A
            
          
        
        ,
      
    
    
  

where T is the temperature, kB is the Boltzmann constant, and the angular brackets denote an average over a simulation run for state A. In practice, one runs a normal simulation for state A, but each time a new configuration is accepted, the energy for state B is also computed. The difference between states A and B may be in the atom types involved, in which case the ΔF obtained is for "mutating" one molecule onto another, or it may be a difference of geometry, in which case one obtains a free-energy map along one or more reaction coordinates. This free-energy map is also known as a potential of mean force (PMF).
Free-energy perturbation calculations only converge properly when the difference between the two states is small enough (the phase space of the two states overlap). In practice, the perturbation is divided into a series of smaller, discrete intermediate FEP windows defined by the coupling parameter 
  
    
      
        λ
      
    
    
  
.  A value of 
  
    
      
        λ
      
    
    
  
 = 0 represent 100% state A, and 
  
    
      
        λ
      
    
    
  
 = 1 represent 100% state B. In any particular window, we have the effective potential energy function 
  
    
      
        
          U
          
            m
          
        
        (
        1
        
          λ
          
            m
          
        
        
          U
          
            A
          
        
        
          λ
          
            m
          
        
        
          U
          
            B
          
        
      
    
    
  
, which is the linear combination of the initial potential A and final B. Stepwise varying 
  
    
      
        λ
      
    
    
  
 from 0 to 1 creates an "alchemical" pathway of transformation between state A and B through non-physical intermediate states.
Since there is no need for constant communication between the simulation for one window and the next, the process can be trivially parallelized by running each window on a different CPU, in what is known as an "embarrassingly parallel" setup.

## Related

- [[Thermodynamic integration]]
- [[1s Slater-type function]]
- [[Ab initio quantum chemistry methods]]
- [[Accessible surface area]]
- [[Activation strain model]]
- [[Adaptive sampling]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Alexander Boldyrev]]
- [[Basis set (chemistry)]]
- [[Bette Korber]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Free-energy_perturbation