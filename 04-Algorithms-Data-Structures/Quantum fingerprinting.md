---
title: "Quantum fingerprinting"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Quantum_fingerprinting"
wikipedia_categories: ["Cryptographic hash functions", "Quantum information science"]
related: ["[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]", "[[Algorithmic cooling]]", "[[Alice & Bob (company)]]", "[[Amplitude damping channel]]", "[[Ancilla bit]]", "[[AQUA@home]]", "[[Argon2]]"]
---

# Quantum fingerprinting

Quantum fingerprinting is a proposed technique that uses a quantum computer to generate a string with a similar function to the cryptographic hash function. Alice and Bob hold 
  
    
      
        n
      
    
    
  
-bit strings 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
. Their goal and a referee's is to obtain the correct value of 
  
    
      
        f
        x
        ,
        y
        =
        
          
            
              
                
                  1
                
                
                  
                    if 
                  
                  x
                  y
                  ,
                
              
              
                
                  0
                
                
                  
                    if 
                  
                  x
                  ≠
                  y
                  .
                
              
            
            
          
        
      
    
    
  
. To do this, 
  
    
      
        
          2
          
            n
          
        
      
    
    
  
 quantum states are produced from the O(logn)-qubit state fingerprints and sent to the referee who performs the Swap test to detect if the fingerprints are similar or different with a high probability.
If unconditional guarantees of security are needed, and if it is impractical for the communicating parties to arrange to share a secret that can be used in a Carter–Wegman MAC, this technique might one day be faster than classical techniques given a quantum computer with 5 to 10 qubits.  However, these circumstances are very unusual and it is unlikely the technique will ever have a practical application; it is largely of theoretical interest.

## Related

- [[1QBit]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]
- [[Algebraic theory of topological quantum information]]
- [[Algorithmic cooling]]
- [[Alice & Bob (company)]]
- [[Amplitude damping channel]]
- [[Ancilla bit]]
- [[AQUA@home]]
- [[Argon2]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_fingerprinting