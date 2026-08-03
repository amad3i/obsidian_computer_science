---
title: "Quantum Fisher information"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Quantum_Fisher_information"
wikipedia_categories: ["Quantum information science", "Quantum optics"]
related: ["[[Boson sampling]]", "[[Cavity quantum electrodynamics]]", "[[Dephasing]]", "[[Entanglement depth]]", "[[KLM protocol]]", "[[Optical cluster state]]", "[[Quantum Cramér–Rao bound]]", "[[Quantum metrological gain]]", "[[Quantum metrology]]", "[[Quantum radar]]"]
---

# Quantum Fisher information

The quantum Fisher information is a central quantity in quantum metrology and is the quantum analogue of the classical Fisher information. It is one of the central quantities used to qualify the utility of an input state, especially in Mach–Zehnder (or, equivalently, Ramsey) interferometer-based phase or parameter estimation.  It is shown that the quantum Fisher information can also be a sensitive probe of a quantum phase transition (e.g. recognizing the superradiant quantum phase transition in the Dicke model). The quantum Fisher information 
  
    
      
        
          F
          
            
              Q
            
          
        
        ϱ
        ,
        A
      
    
    
  
 of a state 
  
    
      
        ϱ
      
    
    
  
 with respect to the observable 
  
    
      
        A
      
    
    
  
 is defined as

  
    
      
        
          F
          
            
              Q
            
          
        
        ϱ
        ,
        A
        =
        2
        
          ∑
          
            k
            ,
            l
          
        
        
          
            
              
                λ
                
                  k
                
              
              
                λ
                
                  l
                
              
              
                
                  2
                
              
            
            
              
                λ
                
                  k
                
              
              
                λ
                
                  l
                
              
            
          
        
        |
        ⟨
        k
        |
        A
        |
        l
        ⟩
        
          |
          
            2
          
        
        ,
      
    
    
  

where 
  
    
      
        
          λ
          
            k
          
        
      
    
    
  
 and 
  
    
      
        |
        k
        ⟩
      
    
    
  
 are the eigenvalues and eigenvectors of the density matrix 
  
    
      
        ϱ
        ,
      
    
    
  
 respectively, and the summation goes over all 
  
    
      
        k
      
    
    
  
 and 
  
    
      
        l
      
    
    
  
 such that 
  
    
      
        
          λ
          
            k
          
        
        
          λ
          
            l
          
        
        0
      
    
    
  
.
When the observable generates a unitary transformation of the system with a parameter 
  
    
      
        θ
      
    
    
  
 from initial state 
  
    
      
        
          ϱ
          
            0
          
        
      
    
    
  
,

  
    
      
        ϱ
        θ
        =
        exp
         
        −
        i
        A
        θ
        
          ϱ
          
            0
          
        
        exp
         
        +
        i
        A
        θ
        ,
      
    
    
  

the quantum Fisher information constrains the achievable precision in statistical estimation of the parameter 
  
    
      
        θ
      
    
    
  
 via the quantum Cramér–Rao bound as

  
    
      
        Δ
        θ
        
          
            2
          
        
        ≥
        
          
            1
            
              m
              
                F
                
                  
                    Q
                  
                
              
              ϱ
              ,
              A
            
          
        
        ,
      
    
    
  

where 
  
    
      
        m
      
    
    
  
 is the number of independent repetitions.
It is often desirable to estimate the magnitude of an unknown parameter 
  
    
      
        α
      
    
    
  
 that controls the strength of a system's Hamiltonian 
  
    
      
        H
        α
        A
      
    
    
  
 with respect to a known observable 
  
    
      
        A
      
    
    
  
 during a known dynamical time 
  
    
      
        t
      
    
    
  
. In this case, defining 
  
    
      
        θ
        α
        t
      
    
    
  
, so that 
  
    
      
        θ
        A
        t
        H
      
    
    
  
, means estimates of 
  
    
      
        θ
      
    
    
  
 can be directly translated into estimates of 
  
    
      
        α
      
    
    
  
.

## Related

- [[Boson sampling]]
- [[Cavity quantum electrodynamics]]
- [[Dephasing]]
- [[Entanglement depth]]
- [[KLM protocol]]
- [[Optical cluster state]]
- [[Quantum Cramér–Rao bound]]
- [[Quantum metrological gain]]
- [[Quantum metrology]]
- [[Quantum radar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_Fisher_information