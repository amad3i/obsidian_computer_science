---
title: "Swap test"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Swap_test"
wikipedia_categories: ["Quantum algorithms"]
related: ["[[Aharonov–Jones–Landau algorithm]]", "[[Amplitude amplification]]", "[[Bernstein–Vazirani algorithm]]", "[[BHT algorithm]]", "[[Boson sampling]]", "[[Continuous-time quantum walk]]", "[[Deutsch–Jozsa algorithm]]", "[[Feynman's algorithm]]", "[[Grover's algorithm]]", "[[Hadamard test]]"]
---

# Swap test

The swap test is a procedure in quantum computation that is used to check how much two quantum states differ, appearing first in the work of Barenco et al.
and later rediscovered by Harry Buhrman, Richard Cleve, John Watrous, and Ronald de Wolf. It appears commonly in quantum machine learning, and is a circuit used for proofs-of-concept in implementations of quantum computers.
Formally, the swap test takes two input states 
  
    
      
        
          |
        
        ϕ
        ⟩
      
    
    
  
 and 
  
    
      
        
          |
        
        ψ
        ⟩
      
    
    
  
 and outputs a Bernoulli random variable that is 1 with probability 
  
    
      
        
          
            
              1
              2
            
          
          
            
              1
              2
            
          
          
            
              
                |
              
              ⟨
              ψ
              
                |
              
              ϕ
              ⟩
              
                |
              
            
            
              2
            
          
        
      
    
    
  
 (where the expressions here use bra–ket notation). This allows one to, for example, estimate the squared inner product between the two states, 
  
    
      
        
          
            
              |
            
            ⟨
            ψ
            
              |
            
            ϕ
            ⟩
            
              |
            
          
          
            2
          
        
      
    
    
  
, to 
  
    
      
        ε
      
    
    
  
 additive error by taking the average over 
  
    
      
        O
        
          
            
              1
              
                ε
                
                  2
                
              
            
          
        
      
    
    
  
 runs of the swap test. This requires 
  
    
      
        O
        
          
            
              1
              
                ε
                
                  2
                
              
            
          
        
      
    
    
  
 copies of the input states. The squared inner product roughly measures "overlap" between the two states, and can be used in linear-algebraic applications, including clustering quantum states.

## Related

- [[Aharonov–Jones–Landau algorithm]]
- [[Amplitude amplification]]
- [[Bernstein–Vazirani algorithm]]
- [[BHT algorithm]]
- [[Boson sampling]]
- [[Continuous-time quantum walk]]
- [[Deutsch–Jozsa algorithm]]
- [[Feynman's algorithm]]
- [[Grover's algorithm]]
- [[Hadamard test]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Swap_test