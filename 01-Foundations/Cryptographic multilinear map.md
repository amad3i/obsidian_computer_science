---
title: "Cryptographic multilinear map"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Cryptographic_multilinear_map"
wikipedia_categories: ["Cryptography", "Multilinear algebra"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Cryptographic multilinear map

A cryptographic 
  
    
      
        n
      
    
    
  
-multilinear map is a kind of multilinear map, that is, a function 
  
    
      
        e
        :
        
          G
          
            1
          
        
        ⋯
        
          G
          
            n
          
        
        →
        
          G
          
            T
          
        
      
    
    
  
 such that for any integers 
  
    
      
        
          a
          
            1
          
        
        ,
        …
        ,
        
          a
          
            n
          
        
      
    
    
  
 and elements 
  
    
      
        
          g
          
            i
          
        
        ∈
        
          G
          
            i
          
        
      
    
    
  
, 
  
    
      
        e
        
          g
          
            1
          
          
            
              a
              
                1
              
            
          
        
        ,
        …
        ,
        
          g
          
            n
          
          
            
              a
              
                n
              
            
          
        
        =
        e
        
          g
          
            1
          
        
        ,
        …
        ,
        
          g
          
            n
          
        
        
          
            
              ∏
              
                i
                1
              
              
                n
              
            
            
              a
              
                i
              
            
          
        
      
    
    
  
, and which in addition is efficiently computable and satisfies some security properties. It has several applications on cryptography, as key exchange protocols, identity-based encryption, and broadcast encryption. There exist constructions of cryptographic 2-multilinear maps, known as bilinear maps, however, the problem of constructing such multilinear maps for 
  
    
      
        n
        2
      
    
    
  
 seems much more difficult   and the security of the proposed candidates is still unclear.

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]
- [[Batch cryptography]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cryptographic_multilinear_map