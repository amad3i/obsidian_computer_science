---
title: "Naor–Reingold pseudorandom function"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Naor–Reingold_pseudorandom_function"
wikipedia_categories: ["Cryptography", "Pseudorandom number generators"]
related: ["[[Self-shrinking generator]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]"]
---

# Naor–Reingold pseudorandom function

In 1997, Moni Naor and Omer Reingold described efficient constructions for various cryptographic primitives in private key as well as public-key cryptography. Their result is the construction of an efficient pseudorandom function. Let p and l be prime numbers with l |p−1. Select an element g ∈ 
  
    
      
        
          
            
              
                F
              
              
                p
              
            
          
          
          
        
      
    
    
  
 of multiplicative order l. Then for each (n+1)-dimensional vector a = (a0,a1, ..., an)∈ 
  
    
      
        
          
            F
          
          
            l
          
        
        
          
            n
            1
          
        
      
    
    
  
 they define the function

  
    
      
        
          f
          
            a
          
        
        x
        =
        
          g
          
            
              a
              
                0
              
            
            ⋅
            
              a
              
                1
              
              
                
                  x
                  
                    1
                  
                
              
            
            
              a
              
                2
              
              
                
                  x
                  
                    2
                  
                
              
            
            .
            .
            .
            
              a
              
                n
              
              
                
                  x
                  
                    n
                  
                
              
            
          
        
        ∈
        
          
            F
          
          
            p
          
        
      
    
    
  

where x = x1 ... xn is the bit representation of integer x, 0 ≤ x ≤ 2n−1, with some extra leading zeros if necessary.

## Related

- [[Self-shrinking generator]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Naor–Reingold_pseudorandom_function