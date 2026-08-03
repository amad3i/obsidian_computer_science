---
title: "Unknown key-share attack"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Unknown_key-share_attack"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Unknown key-share attack

As defined by Blake-Wilson & Menezes (1999), an unknown key-share (UKS) attack on an authenticated key agreement (AK) or authenticated key agreement with key confirmation (AKC) protocol is an attack whereby an entity 
  
    
      
        A
      
    
    
  
 ends up believing she shares a key with 
  
    
      
        B
      
    
    
  
, and although this is in fact the case, 
  
    
      
        B
      
    
    
  
 mistakenly believes the key is instead shared with an entity 
  
    
      
        E
        ≠
        A
      
    
    
  
.
In other words, in a UKS, an opponent, say Eve, coerces honest parties Alice and Bob into establishing a secret key where at least one of Alice and Bob does not know that the secret key is shared with the other. For example, Eve may coerce Bob into believing he shares the key with Eve, while he actually shares the key with Alice. The “key share” with Alice is thus unknown to Bob.

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

- Wikipedia: https://en.wikipedia.org/wiki/Unknown_key-share_attack