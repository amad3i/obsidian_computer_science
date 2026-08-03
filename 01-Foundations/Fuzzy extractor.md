---
title: "Fuzzy extractor"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fuzzy_extractor"
wikipedia_categories: ["Biometrics", "Coding theory", "Cryptographic algorithms"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[Bar product]]", "[[Barker code]]", "[[BB84]]", "[[BCH code]]", "[[Beaufort cipher]]"]
---

# Fuzzy extractor

Fuzzy extractors are a method that allows biometric data to be used as inputs to standard cryptographic techniques, to enhance computer security. "Fuzzy," in this context, refers to the fact that the fixed values required for cryptography will be extracted from values close to but not identical to the original key, without compromising the security required. One application is to encrypt and authenticate users records, using the biometric inputs of the user as a key.
Fuzzy extractors are a biometric tool that allows for user authentication, using a biometric template constructed from the user's biometric data as the key, by extracting a uniform and random string 
  
    
      
        R
      
    
    
  
 from an input 
  
    
      
        w
      
    
    
  
, with a tolerance for noise. If the input changes to 
  
    
      
        
          w
          ′
        
      
    
    
  
 but is still close to 
  
    
      
        w
      
    
    
  
, the same string 
  
    
      
        R
      
    
    
  
 will be re-constructed. To achieve this, during the initial computation of 
  
    
      
        R
      
    
    
  
 the process also outputs a helper string 
  
    
      
        P
      
    
    
  
 which will be stored to recover 
  
    
      
        R
      
    
    
  
 later and can be made public without compromising the security of 
  
    
      
        R
      
    
    
  
. The security of the process is also ensured when an adversary modifies 
  
    
      
        P
      
    
    
  
. Once the fixed string 
  
    
      
        R
      
    
    
  
 has been calculated, it can be used, for example, for key agreement between a user and a server based only on a biometric input.

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[Bar product]]
- [[Barker code]]
- [[BB84]]
- [[BCH code]]
- [[Beaufort cipher]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fuzzy_extractor