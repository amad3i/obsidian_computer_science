---
title: "Malleability (cryptography)"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Malleability_(cryptography)"
wikipedia_categories: ["Cryptography", "Theory of cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Averaging argument]]", "[[Backdoor (computing)]]"]
---

# Malleability (cryptography)

Malleability is a property of some cryptographic algorithms. An encryption algorithm is said to be malleable if it is possible to transform a ciphertext into another ciphertext which decrypts to a related plaintext. That is, given an encryption of a plaintext 
  
    
      
        m
      
    
    
  
, it is possible to generate another ciphertext which decrypts to 
  
    
      
        f
        m
      
    
    
  
, for a known function 
  
    
      
        f
      
    
    
  
, without necessarily knowing or learning 
  
    
      
        m
      
    
    
  
.
Malleability is often an undesirable property in a general-purpose cryptosystem, since it allows an attacker to modify the contents of a message.  For example, suppose that a bank uses a stream cipher to hide its financial information, and a user sends an encrypted message containing, say, "TRANSFER $0000100.00 TO ACCOUNT #199."  If an attacker can modify the message on the wire, and can guess the format of the unencrypted message, the attacker could change the amount of the transaction, or the recipient of the funds, e.g.  "TRANSFER $0100000.00 TO ACCOUNT #227". Malleability does not refer to the attacker's ability to read the encrypted message. Both before and after tampering, the attacker cannot read the encrypted message.
On the other hand, some cryptosystems are malleable by design. In other words, in some circumstances it may be viewed as a feature that anyone can transform an encryption of 
  
    
      
        m
      
    
    
  
 into a valid encryption of 
  
    
      
        f
        m
      
    
    
  
  (for some restricted class of functions 
  
    
      
        f
      
    
    
  
) without necessarily learning 
  
    
      
        m
      
    
    
  
. Such schemes are known as homomorphic encryption schemes.
A cryptosystem may be semantically secure against chosen-plaintext attacks or even non-adaptive chosen-ciphertext attacks (CCA1) while still being malleable. However, security against adaptive chosen-ciphertext attacks (CCA2) is equivalent to non-malleability.

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Averaging argument]]
- [[Backdoor (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Malleability_(cryptography)