---
title: "Phase kickback"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Phase_kickback"
wikipedia_categories: ["Quantum computing"]
related: ["[[Adiabatic quantum computation]]", "[[Algorithmic qubits]]", "[[Andrea Morello]]", "[[Bacon–Shor code]]", "[[BQP]]", "[[Cat qubit quantum computer]]", "[[Cirac–Zoller controlled-NOT gate]]", "[[Circuit Layer Operations per Second]]", "[[Classical shadow]]", "[[Cloud-based quantum computing]]"]
---

# Phase kickback

In quantum computing, phase kickback refers to the fact that controlled operations have effects on their controls, in addition to on their targets, and that these effects correspond to phasing operations. 
When a controlled operation, such as a Controlled NOT (CNOT) gate, is applied to two qubits, the phase of the second (target) qubit is conditioned on the state of the first (control) qubit. 
Because the phase of the second qubit is being "kicked back" to the first qubit, this phenomenon was coined "phase kickback" in 1997 by Richard Cleve, Artur Ekert, Chiara Macchiavello, and Michele Mosca through a paper that solved the Deutsch-Jozsa problem.
For example, when a controlled NOT gate's target qubit is in the state 
  
    
      
        1
        
          /
        
        
          
            2
          
        
        
          |
        
        0
        ⟩
        
          |
        
        1
        ⟩
      
    
    
  
, the effect of the controlled NOT gate is equivalent to the effect of applying a Pauli Z gate to the controlled NOT's control qubit.
Phase kickback is one of the key effects that distinguishes quantum computation from classical computation.
Phase kickback also provides a justification for why qubits would be disrupted by measurements: a measurement is an operation that flips a classical bit (the result) with the flip being controlled by a quantum bit (the qubit being measured).
This creates kickback from the bit to the qubit, randomizing the qubit's phase.

Phase kickback occurs because the basis transformations that distinguish targets from controls are available as operations.
For example, surrounding a controlled NOT gate with four Hadamard gates produces a compound operation whose effect is equivalent to a controlled NOT gate, but with the roles of its control qubit and target qubit exchanged.
More abstractly, phase kickback occurs because the eigendecomposition of controlled operations makes no significant distinction between controls and targets.
For example, the controlled Z gate is a symmetric operation that has the same effect if its target and control are switched, and a controlled NOT gate can be decomposed into a Hadamard gate on its target, then a controlled Z gate, then a second Hadamard gate on its target.
This decomposition reveals that, at the core of the apparently-asymmetric controlled-NOT gate, there is a symmetric effect that does not distinguish between control and target.
Phase kickback can be used to measure an operator 
  
    
      
        P
      
    
    
  
 whose eigenvalues are +1 and -1.
This is a common technique for measuring operators in quantum error correcting codes, such as the surface code.
The procedure is as follows.
Initialize a control qubit 
  
    
      
        c
      
    
    
  
 in the 
  
    
      
        
          |
        
        0
        ⟩
      
    
    
  
 state, then apply a Hadamard gate 
  
    
      
        H
      
    
    
  
 to 
  
    
      
        c
      
    
    
  
, then apply 
  
    
      
        P
      
    
    
  
 controlled by 
  
    
      
        c
      
    
    
  
, then apply another Hadamard gate 
  
    
      
        H
      
    
    
  
 to 
  
    
      
        c
      
    
    
  
, then measure 
  
    
      
        c
      
    
    
  
 in the computational basis.
Phase kickback results in the +1 eigenstates of 
  
    
      
        P
      
    
    
  
 having no effect on 
  
    
      
        c
      
    
    
  
, while -1 eigenstates apply a Pauli 
  
    
      
        Z
      
    
    
  
 to 
  
    
      
        c
      
    
    
  
.
The surrounding Hadamard gates turn the Pauli 
  
    
      
        Z
      
    
    
  
 (a phase flip) into a Pauli 
  
    
      
        X
      
    
    
  
 (a bit flip).
So 
  
    
      
        c
      
    
    
  
 gets flipped from 
  
    
      
        
          |
        
        0
        ⟩
      
    
    
  
 to 
  
    
      
        
          |
        
        1
        ⟩
      
    
    
  
 when the state is in the -1 eigenstate of 
  
    
      
        P
      
    
    
  
.
The measurement operation reveals whether 
  
    
      
        c
      
    
    
  
 is 
  
    
      
        
          |
        
        0
        ⟩
      
    
    
  
 or 
  
    
      
        
          |
        
        1
        ⟩
      
    
    
  
, which reveals whether the state was in the +1 or -1 eigenspace of 
  
    
      
        P
      
    
    
  
.

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

- Wikipedia: https://en.wikipedia.org/wiki/Phase_kickback