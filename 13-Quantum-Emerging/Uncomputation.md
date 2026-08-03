---
title: "Uncomputation"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Uncomputation"
wikipedia_categories: ["Quantum information science", "Quantum physics stubs"]
related: ["[[Ancilla bit]]", "[[AQUA@home]]", "[[CSS code]]", "[[Deferred measurement principle]]", "[[Entropy exchange]]", "[[Information causality]]", "[[Quantum catalyst]]", "[[Reduced dynamics]]", "[[1QBit]]", "[[Absolutely maximally entangled state]]"]
---

# Uncomputation

Uncomputation is a technique, used in reversible circuits, for cleaning up temporary effects on ancilla bits so that they can be re-used.
Uncomputation is a fundamental step in quantum computing algorithms. Whether or not intermediate effects have been uncomputed affects how states interfere with each other when measuring results.
The process is primarily motivated by the principle of implicit measurement, which states that discarding a register during computation is physically equivalent to measuring it. Failure to uncompute garbage registers can have unintentional consequences. For example, if we take the state 
  
    
      
    
    
  
 
  
    
      
        
          
            1
            
              2
            
          
        
        
          |
        
        0
        ⟩
        
          |
        
        
          g
          
            0
          
        
        ⟩
        
          |
        
        1
        ⟩
        
          |
        
        
          g
          
            1
          
        
        ⟩
      
    
    
  
 where 
  
    
      
        
          g
          
            0
          
        
      
    
    
  
 and 
  
    
      
        
          g
          
            1
          
        
      
    
    
  
 are garbage registers. Then, if we do not apply any further operations to those registers, according to the principle of implicit measurement, the entangled state has been measured, resulting in a collapse to either 
  
    
      
        
          |
        
        0
        ⟩
        
          |
        
        
          g
          
            0
          
        
        ⟩
      
    
    
  
 or 
  
    
      
        
          |
        
        1
        ⟩
        
          |
        
        
          g
          
            1
          
        
        ⟩
      
    
    
  
 with probability 
  
    
      
        
          
            1
            2
          
        
      
    
    
  
. What makes this undesirable is that wave-function collapse occurs before the program terminates, and thus may not yield the expected result.

## Related

- [[Ancilla bit]]
- [[AQUA@home]]
- [[CSS code]]
- [[Deferred measurement principle]]
- [[Entropy exchange]]
- [[Information causality]]
- [[Quantum catalyst]]
- [[Reduced dynamics]]
- [[1QBit]]
- [[Absolutely maximally entangled state]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Uncomputation