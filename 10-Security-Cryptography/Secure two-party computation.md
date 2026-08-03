---
title: "Secure two-party computation"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Secure_two-party_computation"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Secure two-party computation

Secure two-party computation (2PC, or secure function evaluation) is a sub-problem of secure multi-party computation (MPC) that has received special attention by researchers because of its close relation to many cryptographic tasks. The goal of 2PC is to create a generic protocol that allows two parties to jointly compute an arbitrary function on their inputs without sharing the value of their inputs with the opposing party. One of the most well known examples of 2PC is Yao's Millionaires' problem, in which two parties, Alice and Bob, are millionaires who wish to determine who is wealthier without revealing their wealth. Formally, Alice has wealth 
  
    
      
        a
      
    
    
  
, Bob has wealth 
  
    
      
        b
      
    
    
  
, and they wish to compute 
  
    
      
        a
        ≥
        b
      
    
    
  
 without revealing the values 
  
    
      
        a
      
    
    
  
 or 
  
    
      
        b
      
    
    
  
.
Yao's garbled circuit protocol for two-party computation only provided security against passive adversaries. One of the first general solutions for achieving security against active adversary was introduced by Goldreich, Micali and Wigderson by applying Zero-Knowledge Proof to enforce semi-honest behavior. This approach was known to be impractical for years due to high complexity overheads. However, significant improvements have been made toward applying this method in 2PC and Abascal, Faghihi Sereshgi, Hazay, Yuval Ishai and Venkitasubramaniam gave the first efficient protocol based on this approach. Another type of 2PC protocols that are secure against active adversaries were proposed by Yehuda Lindell and Benny Pinkas, Ishai, Manoj Prabhakaran and Amit Sahai and Jesper Buus Nielsen and Claudio Orlandi. Another solution for this problem, that explicitly works with committed input was proposed by Stanisław Jarecki and Vitaly Shmatikov.

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

- Wikipedia: https://en.wikipedia.org/wiki/Secure_two-party_computation