---
title: "Quantum logic gate"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Quantum_logic_gate"
wikipedia_categories: ["Australian inventions", "Logic gates", "Quantum gates", "Quantum information science"]
related: ["[[Controlled NOT gate]]", "[[Fredkin gate]]", "[[KLM protocol]]", "[[Linear optical quantum computing]]", "[[Quantum gate teleportation]]", "[[Toffoli gate]]", "[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]"]
---

# Quantum logic gate

In quantum computing and specifically the quantum circuit model of computation, a quantum logic gate (or simply quantum gate) is a basic quantum circuit operating on a small number of qubits. Quantum logic gates are the building blocks of quantum circuits, like classical logic gates are for conventional digital circuits.
According to quantum mechanics, a quantum system can only either evolve unitarily according to the Schrödinger equation, or be measured (sometimes called "Observed"). Quantum gates describe these unitary transformations, that occur when the system is not being measured. The expression "quantum gate" appears in relation to quantum processors, and in this context they are the logical operations that the quantum computer at the assembly language-level of abstraction (e.g. OpenQASM) can perform on the quantum data (qubits or quantum states) that they process, although they can also be whole algorithms (e.g. the Quantum Fourier transform) – But this is only true if such algorithms contains no measurement operations. When the quantum data is measured, it is usually transformed into binary bits, which is then sent to a normal ("classical") computer. The quantum processor behaves like a coprocessor to such classical binary processors.
Unlike many classical logic gates, quantum logic gates are reversible. It is possible to perform classical computing using only reversible gates. For example, the reversible Toffoli gate can implement all Boolean functions, often at the cost of having to use ancilla bits. The Toffoli gate has a direct quantum equivalent, showing that quantum circuits can perform all operations performed by classical circuits.
Quantum gates are unitary operators, and are described as unitary matrices relative to some orthonormal basis. Usually the computational basis is used, which unless comparing it with something, just means that for a d-level quantum system (such as a qubit, a quantum register, or qutrits and qudits) the orthonormal basis vectors are labeled 
  
    
      
        
          |
        
        0
        ⟩
        ,
        
          |
        
        1
        ⟩
        ,
        …
        ,
        
          |
        
        d
        1
        ⟩
      
    
    
  
, or use binary notation.

## Related

- [[Controlled NOT gate]]
- [[Fredkin gate]]
- [[KLM protocol]]
- [[Linear optical quantum computing]]
- [[Quantum gate teleportation]]
- [[Toffoli gate]]
- [[1QBit]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]
- [[Algebraic theory of topological quantum information]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_logic_gate