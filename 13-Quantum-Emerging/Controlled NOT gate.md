---
title: "Controlled NOT gate"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Controlled_NOT_gate"
wikipedia_categories: ["Quantum gates", "Quantum information science"]
related: ["[[KLM protocol]]", "[[Linear optical quantum computing]]", "[[Quantum gate teleportation]]", "[[Quantum logic gate]]", "[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]", "[[Algorithmic cooling]]", "[[Alice & Bob (company)]]"]
---

# Controlled NOT gate

In computer science, the controlled NOT gate (also C-NOT or CNOT), controlled-X gate, controlled-bit-flip gate, Feynman gate or controlled Pauli-X is a quantum logic gate that is an essential component in the construction of a gate-based quantum computer. It can be used to entangle and disentangle Bell states. Any quantum circuit can be simulated to an arbitrary degree of accuracy using a combination of CNOT gates and single qubit rotations. The gate is sometimes named after Richard Feynman who developed an early notation for quantum gate diagrams in 1986. 
The CNOT can be expressed in the Pauli basis as:

  
    
      
        
          
            CNOT
          
        
        
          e
          
            i
            
              
                π
                4
              
            
            
              I
              
                1
              
            
            
              Z
              
                1
              
            
            (
            
              I
              
                2
              
            
            
              X
              
                2
              
            
          
        
        
          e
          
            i
            
              
                π
                4
              
            
            
              I
              
                1
              
            
            
              Z
              
                1
              
            
            (
            
              I
              
                2
              
            
            
              X
              
                2
              
            
          
        
        .
      
    
    
  

Being both unitary and Hermitian, CNOT has the property 
  
    
      
        
          e
          
            i
            θ
            U
          
        
        (
         
        θ
        I
        (
        i
         
        θ
        U
      
    
    
  
 and 
  
    
      
        U
        
          e
          
            i
            
              
                π
                2
              
            
            I
            U
          
        
        
          e
          
            i
            
              
                π
                2
              
            
            I
            U
          
        
      
    
    
  
, and is involutory.  
The CNOT gate can be further decomposed as products of rotation operator gates and exactly one two qubit interaction gate, for example

  
    
      
        
          
            CNOT
          
        
        
          e
          
            i
            
              
                π
                4
              
            
          
        
        
          R
          
            
              y
              
                1
              
            
          
        
        −
        π
        
          /
        
        2
        
          R
          
            
              x
              
                1
              
            
          
        
        −
        π
        
          /
        
        2
        
          R
          
            
              x
              
                2
              
            
          
        
        −
        π
        
          /
        
        2
        
          R
          
            x
            x
          
        
        π
        
          /
        
        2
        
          R
          
            
              y
              
                1
              
            
          
        
        π
        
          /
        
        2
        .
      
    
    
  

In general, any single qubit unitary gate can be expressed as 
  
    
      
        U
        
          e
          
            i
            H
          
        
      
    
    
  
, where H is a Hermitian matrix, and then the controlled U is 
  
    
      
        C
        U
        
          e
          
            i
            
              
                1
                2
              
            
            
              I
              
                1
              
            
            
              Z
              
                1
              
            
            
              H
              
                2
              
            
          
        
      
    
    
  
.
The CNOT gate is also used in classical reversible computing.

## Related

- [[KLM protocol]]
- [[Linear optical quantum computing]]
- [[Quantum gate teleportation]]
- [[Quantum logic gate]]
- [[1QBit]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]
- [[Algebraic theory of topological quantum information]]
- [[Algorithmic cooling]]
- [[Alice & Bob (company)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Controlled_NOT_gate