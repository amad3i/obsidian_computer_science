---
title: "Bacon–Shor code"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Bacon–Shor_code"
wikipedia_categories: ["Quantum computing"]
related: ["[[Adiabatic quantum computation]]", "[[Algorithmic qubits]]", "[[Andrea Morello]]", "[[BQP]]", "[[Cat qubit quantum computer]]", "[[Cirac–Zoller controlled-NOT gate]]", "[[Circuit Layer Operations per Second]]", "[[Classical shadow]]", "[[Cloud-based quantum computing]]", "[[Cross-entropy benchmarking]]"]
---

# Bacon–Shor code

The Bacon–Shor code is a subsystem error correcting code. In a subsystem code, information is encoded in a subsystem of a Hilbert space. Subsystem codes lend to simplified error correcting procedures unlike codes which encode information in the subspace of a Hilbert space.  This simplicity led to the first claim of fault tolerant circuit demonstration on a quantum computer. It is named after Dave Bacon and Peter Shor.
Given the stabilizer generators of Shor's code: 
  
    
      
        ⟨
        
          X
          
            0
          
        
        
          X
          
            1
          
        
        
          X
          
            2
          
        
        
          X
          
            3
          
        
        
          X
          
            4
          
        
        
          X
          
            5
          
        
        ,
        
          X
          
            0
          
        
        
          X
          
            1
          
        
        
          X
          
            2
          
        
        
          X
          
            6
          
        
        
          X
          
            7
          
        
        
          X
          
            8
          
        
        ,
        
          Z
          
            0
          
        
        
          Z
          
            1
          
        
        ,
        
          Z
          
            1
          
        
        
          Z
          
            2
          
        
        ,
        
          Z
          
            3
          
        
        
          Z
          
            4
          
        
        ,
        
          Z
          
            4
          
        
        
          Z
          
            5
          
        
        ,
        
          Z
          
            6
          
        
        
          Z
          
            7
          
        
        ,
        
          Z
          
            7
          
        
        
          Z
          
            8
          
        
        ⟩
      
    
    
  
, 4 stabilizers can be removed from this generator by recognizing gauge symmetries in the code to get: 
  
    
      
        ⟨
        
          X
          
            0
          
        
        
          X
          
            1
          
        
        
          X
          
            2
          
        
        
          X
          
            3
          
        
        
          X
          
            4
          
        
        
          X
          
            5
          
        
        ,
        
          X
          
            0
          
        
        
          X
          
            1
          
        
        
          X
          
            2
          
        
        
          X
          
            6
          
        
        
          X
          
            7
          
        
        
          X
          
            8
          
        
        ,
        
          Z
          
            0
          
        
        
          Z
          
            1
          
        
        
          Z
          
            3
          
        
        
          Z
          
            4
          
        
        
          Z
          
            6
          
        
        
          Z
          
            7
          
        
        ,
        
          Z
          
            1
          
        
        
          Z
          
            2
          
        
        
          Z
          
            4
          
        
        
          Z
          
            5
          
        
        
          Z
          
            7
          
        
        
          Z
          
            8
          
        
        ⟩
      
    
    
  
. Error correction is now simplified because 4 stabilizers are needed to measure errors instead of 8. A gauge group can be created from the stabilizer generators:
  
    
      
        ⟨
        
          Z
          
            1
          
        
        
          Z
          
            2
          
        
        ,
        
          X
          
            2
          
        
        
          X
          
            8
          
        
        ,
        
          Z
          
            4
          
        
        
          Z
          
            5
          
        
        ,
        
          X
          
            5
          
        
        
          X
          
            8
          
        
        ,
        
          Z
          
            0
          
        
        
          Z
          
            1
          
        
        ,
        
          X
          
            0
          
        
        
          X
          
            6
          
        
        ,
        
          Z
          
            3
          
        
        
          Z
          
            4
          
        
        ,
        
          X
          
            3
          
        
        
          X
          
            6
          
        
        ,
        
          X
          
            1
          
        
        
          X
          
            7
          
        
        ,
        
          X
          
            4
          
        
        
          X
          
            7
          
        
        ,
        
          Z
          
            6
          
        
        
          Z
          
            7
          
        
        ,
        
          Z
          
            7
          
        
        
          Z
          
            8
          
        
        ⟩
      
    
    
  
. Given that the Bacon–Shor code is defined on a square lattice where the qubits are placed on the vertices; laying the qubits on a grid in a way that corresponds to the gauge group shows how only 2 qubit nearest-neighbor measurements are needed to infer the error syndromes. The simplicity of  deducing the syndromes reduces the overhead for fault tolerant error correction.

## Related

- [[Adiabatic quantum computation]]
- [[Algorithmic qubits]]
- [[Andrea Morello]]
- [[BQP]]
- [[Cat qubit quantum computer]]
- [[Cirac–Zoller controlled-NOT gate]]
- [[Circuit Layer Operations per Second]]
- [[Classical shadow]]
- [[Cloud-based quantum computing]]
- [[Cross-entropy benchmarking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bacon–Shor_code