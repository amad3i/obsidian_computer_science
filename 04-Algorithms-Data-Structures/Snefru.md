---
title: "Snefru"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Snefru"
wikipedia_categories: ["Broken hash functions", "Cryptographic hash functions", "Cryptography stubs"]
related: ["[[Ascon (cipher)]]", "[[FORK-256]]", "[[Gimli (cipher)]]", "[[GOST (hash function)]]", "[[Grøstl]]", "[[HAIFA construction]]", "[[HAS-160]]", "[[HAS-V]]", "[[Hash function security summary]]", "[[HAVAL]]"]
---

# Snefru

Snefru is a cryptographic hash function invented by Ralph Merkle
in 1990 while working at Xerox PARC.
The function supports 128-bit and 256-bit output. It was named after the Egyptian Pharaoh Sneferu, continuing the tradition of the Khufu and Khafre block ciphers.
The original design of Snefru was shown to be insecure by Eli Biham and Adi Shamir who were able to use differential cryptanalysis to find hash collisions. The design was then modified by increasing the number of iterations of the main pass of the algorithm from two to eight. Although differential cryptanalysis can break the revised version with less complexity than brute force search (a certificational weakness), the attack requires 
  
    
      
        
          2
          
            88.5
          
        
      
    
    
  
 operations and is thus not currently feasible in practice.

## Related

- [[Ascon (cipher)]]
- [[FORK-256]]
- [[Gimli (cipher)]]
- [[GOST (hash function)]]
- [[Grøstl]]
- [[HAIFA construction]]
- [[HAS-160]]
- [[HAS-V]]
- [[Hash function security summary]]
- [[HAVAL]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Snefru