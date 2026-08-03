---
title: "Steane code"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Steane_code"
wikipedia_categories: ["Quantum information science"]
related: ["[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]", "[[Algorithmic cooling]]", "[[Alice & Bob (company)]]", "[[Amplitude damping channel]]", "[[Ancilla bit]]", "[[AQUA@home]]", "[[Atomic radio receiver]]"]
---

# Steane code

The Steane code is a tool in quantum error correction introduced by Andrew Steane in 1996. It is a CSS code (Calderbank-Shor-Steane), using the classical binary  [7,4,3] Hamming code to correct for both qubit flip errors (X errors) and phase flip errors (Z errors). The Steane code encodes one logical qubit in 7 physical qubits and is able to correct arbitrary single qubit errors.
Its check matrix in standard form is 

  
    
      
        
          
            
              
                
                  H
                
                
                  0
                
              
              
                
                  0
                
                
                  H
                
              
            
          
        
      
    
    
  

where H is the parity-check matrix of the Hamming code and is given by

  
    
      
        H
        
          
            
              
                
                  1
                
                
                  0
                
                
                  0
                
                
                  1
                
                
                  0
                
                
                  1
                
                
                  1
                
              
              
                
                  0
                
                
                  1
                
                
                  0
                
                
                  1
                
                
                  1
                
                
                  0
                
                
                  1
                
              
              
                
                  0
                
                
                  0
                
                
                  1
                
                
                  0
                
                
                  1
                
                
                  1
                
                
                  1
                
              
            
          
        
        .
      
    
    
  

The 
  
    
      
        [
        7
        ,
        1
        ,
        3
        ]
      
    
    
  
 Steane code is the first in the family of quantum Hamming codes, codes with parameters 
  
    
      
        [
        
          2
          
            r
          
        
        1
        ,
        
          2
          
            r
          
        
        1
        2
        r
        ,
        3
        ]
      
    
    
  
 for integers 
  
    
      
        r
        ≥
        3
      
    
    
  
.  It is also a quantum color code.

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
- [[Atomic radio receiver]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Steane_code