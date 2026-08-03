---
title: "Variational Monte Carlo"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Variational_Monte_Carlo"
wikipedia_categories: ["Mathematical optimization", "Quantum Monte Carlo", "Quantum chemistry"]
related: ["[[Diffusion Monte Carlo]]", "[[Path integral Monte Carlo]]", "[[1s Slater-type function]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]"]
---

# Variational Monte Carlo

In computational physics, variational Monte Carlo (VMC) is a quantum Monte Carlo method that applies the variational method to approximate the ground state of a quantum system.
The basic building block is a generic wave function 
  
    
      
        
          |
        
        Ψ
        a
        ⟩
      
    
    
  
 depending on some parameters 
  
    
      
        a
      
    
    
  
. The optimal values of the parameters 
  
    
      
        a
      
    
    
  
 is then found upon minimizing the total energy of the system.
In particular, given the Hamiltonian 
  
    
      
        
          
            H
          
        
      
    
    
  
, and denoting with 
  
    
      
        X
      
    
    
  
 a many-body configuration, the expectation value of the energy can be written as:

  
    
      
        E
        a
        =
        
          
            
              ⟨
              Ψ
              a
              
                |
              
              
                
                  H
                
              
              
                |
              
              Ψ
              a
              ⟩
            
            
              ⟨
              Ψ
              a
              
                |
              
              Ψ
              a
              ⟩
            
          
        
        
          
            
              ∫
              
                |
              
              Ψ
              X
              ,
              a
              
                
                  |
                
                
                  2
                
              
              
                
                  
                    
                      
                        H
                      
                    
                    Ψ
                    X
                    ,
                    a
                  
                  
                    Ψ
                    X
                    ,
                    a
                  
                
              
              
              d
              X
            
            
              ∫
              
                |
              
              Ψ
              X
              ,
              a
              
                
                  |
                
                
                  2
                
              
              
              d
              X
            
          
        
        .
      
    
    
  

Following the Monte Carlo method for evaluating integrals, we can interpret 
  
    
      
        
          
            
              
                |
              
              Ψ
              X
              ,
              a
              
                
                  |
                
                
                  2
                
              
            
            
              ∫
              
                |
              
              Ψ
              X
              ,
              a
              
                
                  |
                
                
                  2
                
              
              
              d
              X
            
          
        
      
    
    
  
 as a probability distribution function, sample it, and evaluate the energy expectation value 
  
    
      
        E
        a
      
    
    
  
 as the average of the so-called local energy 
  
    
      
        
          E
          
            
              loc
            
          
        
        X
        =
        
          
            
              
                
                  H
                
              
              Ψ
              X
              ,
              a
            
            
              Ψ
              X
              ,
              a
            
          
        
      
    
    
  
. Once 
  
    
      
        E
        a
      
    
    
  
 is known for a given set of variational parameters 
  
    
      
        a
      
    
    
  
, then optimization is performed in order to minimize the energy and obtain the best possible representation of the ground-state wave-function.
VMC is no different from any other variational method, except that the many-dimensional integrals are evaluated numerically. Monte Carlo integration is particularly crucial in this problem since the dimension of the many-body Hilbert space, comprising all the possible values of the configurations 
  
    
      
        X
      
    
    
  
, typically grows exponentially with the size of the physical system. Other approaches to the numerical evaluation of the energy expectation values would therefore, in general, limit applications to much smaller systems than those analyzable thanks to the Monte Carlo approach.
The accuracy of the method then largely depends on the choice of the variational state. The simplest choice typically corresponds to a mean-field form, where the state 
  
    
      
        Ψ
      
    
    
  
 is written as a factorization over the Hilbert space. This particularly simple form is typically not very accurate since it neglects many-body effects. One of the largest gains in accuracy over writing the wave function separably comes from the introduction of the so-called Jastrow factor. In this case the wave function is written as 
  
    
      
        Ψ
        X
        =
        exp
         
        ∑
        
          u
          
            r
            
              i
              j
            
          
        
      
    
    {\textstyle \Psi (X)=\exp(\sum {u(r_{ij})})}
  
, where 
  
    
      
        
          r
          
            i
            j
          
        
      
    
    
  
 is the distance between a pair of quantum particles and 
  
    
      
        u
        r
      
    
    
  
 is a variational function to be determined. With this factor, we can explicitly account for particle-particle correlation, but the many-body integral becomes unseparable, so Monte Carlo is the only way to evaluate it efficiently. In chemical systems, slightly more sophisticated versions of this factor can obtain 80–90% of the correlation energy (see electronic correlation) with less than 30 parameters.  In comparison, a configuration interaction calculation may require around 50,000 parameters to reach that accuracy, although it depends greatly on the particular case being considered. In addition, VMC usually scales as a small power of the number of particles in the simulation, usually something like N2−4 for calculation of the energy expectation value, depending on the form of the wave function.

## Related

- [[Diffusion Monte Carlo]]
- [[Path integral Monte Carlo]]
- [[1s Slater-type function]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Variational_Monte_Carlo