---
title: "Gnu code"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Gnu_code"
wikipedia_categories: ["Fault-tolerant computer systems", "Quantum information science"]
related: ["[[Surface code]]", "[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]", "[[Algorithmic cooling]]", "[[Alice & Bob (company)]]", "[[Amplitude damping channel]]", "[[Ancilla bit]]", "[[AQUA@home]]"]
---

# Gnu code

In quantum information, the gnu code refers to a particular family of quantum error correcting codes, with the special property of being invariant under permutations of the qubits. Given integers g (the gap), n (the occupancy), and m (the length of the code), the two codewords are

  
    
      
        
          |
        
        
          0
          
            
              L
            
          
        
        ⟩
        
          ∑
          
            
              
                ℓ
                
                
                  
                    even
                  
                
              
              
                0
                ≤
                ℓ
                ≤
                n
              
            
          
        
        
          
            
              
                
                
                
                  n
                  ℓ
                
                
                
              
              
                2
                
                  n
                  1
                
              
            
          
        
        
          |
        
        
          D
          
            g
            ℓ
          
          
            m
          
        
        ⟩
      
    
    
  

  
    
      
        
          |
        
        
          1
          
            
              L
            
          
        
        ⟩
        
          ∑
          
            
              
                ℓ
                
                
                  
                    odd
                  
                
              
              
                0
                ≤
                ℓ
                ≤
                n
              
            
          
        
        
          
            
              
                
                
                
                  n
                  ℓ
                
                
                
              
              
                2
                
                  n
                  1
                
              
            
          
        
        
          |
        
        
          D
          
            g
            ℓ
          
          
            m
          
        
        ⟩
      
    
    
  

where 
  
    
      
        
          |
        
        
          D
          
            k
          
          
            m
          
        
        ⟩
      
    
    
  
 are the Dicke states consisting of a uniform superposition of all weight-k words on m qubits, e.g.

  
    
      
        
          |
        
        
          D
          
            2
          
          
            4
          
        
        ⟩
        
          
            
              
                |
              
              0011
              ⟩
              
                |
              
              0101
              ⟩
              
                |
              
              1001
              ⟩
              
                |
              
              0110
              ⟩
              
                |
              
              1010
              ⟩
              
                |
              
              1100
              ⟩
            
            
              6
            
          
        
      
    
    
  

The real parameter 
  
    
      
        u
        
          
            m
            
              g
              n
            
          
        
      
    
    
  
 scales the length of the code. The number 
  
    
      
        u
      
    
    
  
 needs to be at least 1. The length 
  
    
      
        m
        g
        n
        u
      
    
    
  
, hence the name of the code. The distance of the code is the minimum of 
  
    
      
        g
      
    
    
  
 and 
  
    
      
        n
      
    
    
  
. For 
  
    
      
        g
        n
      
    
    
  
 and 
  
    
      
        u
        ≥
        1
      
    
    
  
, the gnu code is capable of correcting 
  
    
      
        g
        1
      
    
    
  
 erasure errors, or deletion errors. The code can also correct up to 
  
    
      
        ⌊
        g
        1
        
          /
        
        2
        ⌋
      
    
    
  
 corrupted qubits from the property of the distance.

## Related

- [[Surface code]]
- [[1QBit]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]
- [[Algebraic theory of topological quantum information]]
- [[Algorithmic cooling]]
- [[Alice & Bob (company)]]
- [[Amplitude damping channel]]
- [[Ancilla bit]]
- [[AQUA@home]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gnu_code