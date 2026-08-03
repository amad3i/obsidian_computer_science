---
title: "Five-qubit error correcting code"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Five-qubit_error_correcting_code"
wikipedia_categories: ["Quantum computing"]
related: ["[[Adiabatic quantum computation]]", "[[Algorithmic qubits]]", "[[Andrea Morello]]", "[[Bacon–Shor code]]", "[[BQP]]", "[[Cat qubit quantum computer]]", "[[Cirac–Zoller controlled-NOT gate]]", "[[Circuit Layer Operations per Second]]", "[[Classical shadow]]", "[[Cloud-based quantum computing]]"]
---

# Five-qubit error correcting code

The five-qubit error correcting code, [[5,1,3]] code, or Laflamme–Miquel–Paz–Zurek code is the smallest quantum error correcting code that can protect a logical qubit from any arbitrary single qubit error. In this code, 5 physical qubits are used to encode the logical qubit. With 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Z
      
    
    
  
 being Pauli matrices and 
  
    
      
        I
      
    
    
  
 the Identity matrix, this code's generators are 
  
    
      
        ⟨
        X
        Z
        Z
        X
        I
        ,
        I
        X
        Z
        Z
        X
        ,
        X
        I
        X
        Z
        Z
        ,
        Z
        X
        I
        X
        Z
        ⟩
      
    
    
  
. Its logical operators are 
  
    
      
        
          
            
              X
              ¯
            
          
        
        X
        X
        X
        X
        X
      
    
    
  
 and  
  
    
      
        
          
            
              Z
              ¯
            
          
        
        Z
        Z
        Z
        Z
        Z
      
    
    
  
.  Once the logical qubit is encoded, errors on the physical qubits can be detected via stabilizer measurements. A lookup table that maps the results of the stabilizer measurements to the types and locations of the errors gives the control system of the quantum computer enough information to correct errors.

## Related

- [[Adiabatic quantum computation]]
- [[Algorithmic qubits]]
- [[Andrea Morello]]
- [[Bacon–Shor code]]
- [[BQP]]
- [[Cat qubit quantum computer]]
- [[Cirac–Zoller controlled-NOT gate]]
- [[Circuit Layer Operations per Second]]
- [[Classical shadow]]
- [[Cloud-based quantum computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Five-qubit_error_correcting_code