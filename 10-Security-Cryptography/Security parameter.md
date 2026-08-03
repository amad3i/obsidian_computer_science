---
title: "Security parameter"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Security_parameter"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Security parameter

In cryptography, a security parameter is a way of measuring of how "hard" it is for an adversary to break a cryptographic scheme.  There are two main types of security parameter: computational and statistical, often denoted by 
  
    
      
        κ
      
    
    
  
 and 
  
    
      
        λ
      
    
    
  
, respectively.  Roughly speaking, the computational security parameter is a measure for the input size of the computational problem on which the cryptographic scheme is based, which determines its computational complexity, whereas the statistical security parameter is a measure of the probability with which an adversary can break the scheme (whatever that means for the protocol).
Security parameters are usually expressed in unary representation - i.e. 
  
    
      
        κ
      
    
    
  
 is expressed as a string of 
  
    
      
        κ
      
    
    
  
 
  
    
      
        1
      
    
    
  
s, 
  
    
      
        κ
        1
        ⋯
        1
      
    
    
  
, conventionally written as 
  
    
      
        
          1
          
            κ
          
        
      
    
    
  
 - so that the time complexity of the cryptographic algorithm is polynomial in the size of the input.

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

- Wikipedia: https://en.wikipedia.org/wiki/Security_parameter