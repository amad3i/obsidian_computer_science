---
title: "Mølmer–Sørensen gate"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Mølmer–Sørensen_gate"
wikipedia_categories: ["Quantum computing", "Quantum gates"]
related: ["[[Cirac–Zoller controlled-NOT gate]]", "[[Adiabatic quantum computation]]", "[[Algorithmic qubits]]", "[[Andrea Morello]]", "[[Bacon–Shor code]]", "[[BQP]]", "[[Cat qubit quantum computer]]", "[[Circuit Layer Operations per Second]]", "[[Classical shadow]]", "[[Cloud-based quantum computing]]"]
---

# Mølmer–Sørensen gate

In quantum computing, Mølmer–Sørensen gate scheme (or MS gate) refers to an implementation procedure for various multi-qubit quantum logic gates used mostly in trapped ion quantum computing. This procedure is based on the original proposition by Klaus Mølmer and Anders Sørensen in 1999–2000.
This proposal was an alternative to the 1995 Cirac–Zoller controlled-NOT gate implementation for trapped ions, which requires that the system be restricted to the joint motional ground state of the ions.
In an MS gate, entangled states are prepared by illuminating ions with a bichromatic light field. Mølmer and Sørensen identified two regimes in which this is possible:

A weak-field regime, where single-photon absorption is suppressed and two-photon processes interfere in a way that makes internal state dynamics insensitive to the vibrational state
A strong-field regime where the individual ions are coherently excited, and the motional state is highly entangled with the internal state until all undesirable excitations are deterministically removed toward the end of the interaction.
In both regimes, a red and blue sideband interaction are applied simultaneously to each ion, with the red and blue tones symmetrically detuned by 
  
    
      
        
          δ
          ′
        
      
    
    
  
 from the sidebands. This results in laser detunings 
  
    
      
        ±
        
          ω
          
            k
          
        
        
          δ
          ′
        
      
    
    
  
, where 
  
    
      
        
          ω
          
            k
          
        
      
    
    
  
 is the motional mode frequency.
When an MS gate is applied globally to all ions in a chain, multipartite entanglement is created, with the form of the gate being a sum of local XX (or YY, or XY depending on experimental parameters) interactions applied to all qubit pairs. When the gate is performed on a single pair of ions, it reduces to the RXX gate. Thus, the CNOT gate can be decomposed into an MS gate and combination of single particle rotations.

## Related

- [[Cirac–Zoller controlled-NOT gate]]
- [[Adiabatic quantum computation]]
- [[Algorithmic qubits]]
- [[Andrea Morello]]
- [[Bacon–Shor code]]
- [[BQP]]
- [[Cat qubit quantum computer]]
- [[Circuit Layer Operations per Second]]
- [[Classical shadow]]
- [[Cloud-based quantum computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mølmer–Sørensen_gate