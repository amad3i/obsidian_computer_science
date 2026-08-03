---
title: "Quantum LC circuit"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Quantum_LC_circuit"
wikipedia_categories: ["Quantum information science", "Quantum models"]
related: ["[[1QBit]]", "[[1s Slater-type function]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]", "[[Algorithmic cooling]]", "[[Alice & Bob (company)]]", "[[Amplitude damping channel]]", "[[Ancilla bit]]", "[[AQUA@home]]"]
---

# Quantum LC circuit

An LC circuit can be quantized using the same methods as for the quantum harmonic oscillator.  An LC circuit is a variety of resonant circuit, and consists of an inductor, represented by the letter L, and a capacitor, represented by the letter C. When connected together, an electric current can alternate between them at the circuit's resonant frequency:

  
    
      
        ω
        
          
            
              1
              
                L
                C
              
            
          
        
      
    
    
  

where L is the inductance in henries, and C is the capacitance in farads.  The angular frequency 
  
    
      
        ω
        
      
    
    
  
  has units of radians per second.  A capacitor stores energy in the electric field between the plates, which can be written as follows:

  
    
      
        
          U
          
            C
          
        
        
          
            1
            2
          
        
        C
        
          V
          
            2
          
        
        
          
            
              Q
              
                2
              
            
            
              2
              C
            
          
        
      
    
    
  

Where Q is the net charge on the capacitor, calculated as

  
    
      
        Q
        t
        =
        
          ∫
          
            ∞
          
          
            t
          
        
        I
        τ
        d
        τ
      
    
    
  

Likewise, an inductor stores energy in the magnetic field depending on the current, which can be written as follows:

  
    
      
        
          U
          
            L
          
        
        
          
            1
            2
          
        
        L
        
          I
          
            2
          
        
        
          
            
              ϕ
              
                2
              
            
            
              2
              L
            
          
        
      
    
    
  

Where 
  
    
      
        ϕ
      
    
    
  
 is the branch flux, defined as

  
    
      
        ϕ
        t
        ≡
        
          ∫
          
            ∞
          
          
            t
          
        
        V
        τ
        d
        τ
      
    
    
  

Since charge and flux are canonically conjugate variables, one can use canonical quantization to rewrite the classical hamiltonian in the quantum formalism, by identifying

  
    
      
        ϕ
        →
        
          
            
              ϕ
              ^
            
          
        
      
    
    
  

  
    
      
        q
        →
        
          
            
              q
              ^
            
          
        
      
    
    
  

  
    
      
        H
        →
        
          
            
              H
              ^
            
          
        
        
          
            
              
                
                  
                    ϕ
                    ^
                  
                
              
              
                2
              
            
            
              2
              L
            
          
        
        
          
            
              
                
                  
                    q
                    ^
                  
                
              
              
                2
              
            
            
              2
              C
            
          
        
      
    
    
  

and enforcing the canonical commutation relation

  
    
      
        
          
            
              
                
                  ϕ
                  ^
                
              
            
            ,
            
              
                
                  q
                  ^
                
              
            
          
        
        i
        ℏ
      
    
    

## Related

- [[1QBit]]
- [[1s Slater-type function]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]
- [[Algebraic theory of topological quantum information]]
- [[Algorithmic cooling]]
- [[Alice & Bob (company)]]
- [[Amplitude damping channel]]
- [[Ancilla bit]]
- [[AQUA@home]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_LC_circuit