---
title: "Solovay–Kitaev theorem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Solovay–Kitaev_theorem"
wikipedia_categories: ["Mathematical theorems", "Quantum computing", "Quantum information theory"]
related: ["[[Classical shadow]]", "[[Parity measurement]]", "[[Quantum Computing Since Democritus]]", "[[Quantum state discrimination]]", "[[Adiabatic quantum computation]]", "[[Algorithmic qubits]]", "[[Andrea Morello]]", "[[Bacon–Shor code]]", "[[Bauer maximum principle]]", "[[BQP]]"]
---

# Solovay–Kitaev theorem

In quantum information and computation, the Solovay–Kitaev theorem says that if a set of single-qubit quantum gates generates a dense subgroup of SU(2), then that set can be used to approximate any desired quantum gate with a short sequence of gates that can also be found efficiently. This theorem is considered one of the most significant results in the field of quantum computation and was first announced by Robert M. Solovay in 1995 and independently proven by Alexei Kitaev in 1997. Michael Nielsen and Christopher M. Dawson have noted its importance in the field.
A consequence of this theorem is that a quantum circuit of 
  
    
      
        m
      
    
    
  
 constant-qubit gates can be approximated to 
  
    
      
        ε
      
    
    
  
 error (in operator norm) by a quantum circuit of 
  
    
      
        O
        m
        
          
            c
          
        
         
        m
        
          /
        
        ε
        )
      
    
    
  
 gates from a desired finite universal gate set (where c is a constant). By comparison, just knowing that a gate set is universal only implies that constant-qubit gates can be approximated by a finite circuit from the gate set, with no bound on its length. So, the Solovay–Kitaev theorem shows that this approximation can be made surprisingly efficient, thereby justifying that quantum computers need only implement a finite number of gates to gain the full power of quantum computation.

## Related

- [[Classical shadow]]
- [[Parity measurement]]
- [[Quantum Computing Since Democritus]]
- [[Quantum state discrimination]]
- [[Adiabatic quantum computation]]
- [[Algorithmic qubits]]
- [[Andrea Morello]]
- [[Bacon–Shor code]]
- [[Bauer maximum principle]]
- [[BQP]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Solovay–Kitaev_theorem