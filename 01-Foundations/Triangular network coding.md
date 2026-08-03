---
title: "Triangular network coding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Triangular_network_coding"
wikipedia_categories: ["Coding theory", "Finite fields", "Information theory", "Telecommunications stubs"]
related: ["[[Generalized minimum-distance decoding]]", "[[Homomorphic signatures for network coding]]", "[[Linear network coding]]", "[[Zyablov bound]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Bar product]]", "[[BCH code]]", "[[Berlekamp–Welch algorithm]]", "[[Channel use]]"]
---

# Triangular network coding

In coding theory, triangular network coding (TNC) is a non-linear network coding based packet coding scheme introduced by Qureshi, Foh & Cai (2012).
Previously, packet coding for network coding was done using linear network coding (LNC). The drawback of LNC over large finite field is that it resulted in high encoding and decoding computational complexity. While linear encoding and decoding over GF(2) alleviates the concern of high computational complexity, coding over GF(2) comes at the tradeoff cost of degrading throughput performance.
The main contribution of triangular network coding is to reduce the worst-case decoding computational complexity of 
  
    
      
        O
        
          n
          
            3
          
        
      
    
    
  
 to 
  
    
      
        O
        
          n
          
            2
          
        
      
    
    
  
 (where n is the total number of data packets being encoded in a coded packet) without degrading the throughput performance, with code rate comparable to that of optimal coding schemes.
Triangular code has also been proposed as Fountain code to achieve near-optimal performance with encoding and decoding computational complexity of 
  
    
      
        O
        n
         
        n
      
    
    
  
. It has been further shown that triangular based fountain code can even outperform optimized Luby transform code.

## Related

- [[Generalized minimum-distance decoding]]
- [[Homomorphic signatures for network coding]]
- [[Linear network coding]]
- [[Zyablov bound]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Bar product]]
- [[BCH code]]
- [[Berlekamp–Welch algorithm]]
- [[Channel use]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Triangular_network_coding