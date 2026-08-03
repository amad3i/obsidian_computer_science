---
title: "Code rate"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Code_rate"
wikipedia_categories: ["Computer science stubs", "Information theory", "Rates"]
related: ["[[Constraint (information theory)]]", "[[Outage probability]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Algorithmic information theory]]", "[[Analog image processing]]"]
---

# Code rate

In telecommunication and information theory, the code rate (or information rate) of a forward error correction code is the proportion of the data-stream that is useful (non-redundant). That is, if the code rate is 
  
    
      
        k
        
          /
        
        n
      
    
    
  
, for every k bits of useful information, the coder generates a total of n bits of data, of which 
  
    
      
        n
        k
      
    
    
  
 are redundant. 
If R is the gross bit rate or data signalling rate (inclusive of redundant error coding), the net bit rate (the useful bit rate exclusive of error correction codes) is 
  
    
      
        ≤
        R
        ⋅
        k
        
          /
        
        n
      
    
    
  
. 
For example: The code rate of a convolutional code will typically be 1⁄2, 2⁄3, 3⁄4, 5⁄6, 7⁄8, etc., corresponding to one redundant bit inserted after every single, second, third, etc., bit. The code rate of the octet oriented Reed Solomon block code denoted RS(204,188) is 188/204, meaning that 204 − 188 = 16 redundant octets (or bytes) are added to each block of 188 octets of useful information. 
A few error correction codes do not have a fixed code rate—rateless erasure codes.
Note that bit/s is a more widespread unit of measurement for the information rate, implying that it is synonymous with net bit rate or useful bit rate exclusive of error-correction codes.

## Related

- [[Constraint (information theory)]]
- [[Outage probability]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Algorithmic information theory]]
- [[Analog image processing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Code_rate