---
title: "Security protocol notation"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Security_protocol_notation"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Security protocol notation

In cryptography, security (engineering) protocol notation, also known as protocol narrations and Alice & Bob notation, is a way of expressing a protocol of correspondence between entities of a dynamic system, such as a computer network. In the context of a formal model, it allows reasoning about the properties of such a system.
The standard notation consists of a set of principals (traditionally named Alice, Bob, Charlie, and so on) who wish to communicate. They may have access to a server S, shared keys K, timestamps T, and can generate nonces N for authentication purposes.
A simple example might be the following:

  
    
      
        A
        →
        B
        :
        X
        
          
            
              K
              
                A
                ,
                B
              
            
          
        
      
    
    
  

This states that Alice intends a message for Bob consisting of a plaintext X encrypted under shared key KA,B.
Another example might be the following:

  
    
      
        B
        →
        A
        :
        
          N
          
            B
          
        
        
          
            
              K
              
                A
              
            
          
        
      
    
    
  

This states that Bob intends a message for Alice consisting of a nonce NB encrypted using public key of Alice.
A key with two subscripts, KA,B, is a symmetric key shared by the two corresponding individuals. A key with one subscript, KA, is the public key of the corresponding individual. A private key is represented as the inverse of the public key.
The notation specifies only the operation and not its semantics — for instance, private key encryption and signature are represented identically.
We can express more complicated protocols in such a fashion. See Kerberos as an example. Some sources refer to this notation as Kerberos Notation. Some authors consider the notation used by Steiner, Neuman, & Schiller as a notable reference.
Several models exist to reason about security protocols in this way, one of which is BAN logic.
Security protocol notation inspired many of the programming languages used in choreographic programming.

## Related

- [[Batch cryptography]]
- [[Branch number]]
- [[Cipher device]]
- [[Ciphertext expansion]]
- [[Client-side encryption]]
- [[Codress message]]
- [[Completeness (cryptography)]]
- [[Conjugate coding]]
- [[Correlation immunity]]
- [[Cover (telecommunications)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Security_protocol_notation