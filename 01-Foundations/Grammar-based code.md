---
title: "Grammar-based code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Grammar-based_code"
wikipedia_categories: ["Coding theory", "Data compression", "Information theory"]
related: ["[[Shannon's source coding theorem]]", "[[Bar product]]", "[[Canonical Huffman code]]", "[[Distributed source coding]]", "[[Entropy (information theory)]]", "[[Error exponent]]", "[[Generalized minimum-distance decoding]]", "[[Gibbs' inequality]]", "[[Hamming distance]]", "[[Homomorphic signatures for network coding]]"]
---

# Grammar-based code

Grammar-based codes or grammar-based compression are compression algorithms based on the idea of constructing a context-free grammar (CFG) for the string to be compressed. Examples include universal lossless data compression algorithms. To compress a data sequence 
  
    
      
        x
        
          x
          
            1
          
        
        ⋯
        
          x
          
            n
          
        
      
    
    
  
, a grammar-based code transforms 
  
    
      
        x
      
    
    
  
 into a context-free grammar 
  
    
      
        G
      
    
    
  
.
The problem of finding a smallest grammar for an input sequence (smallest grammar problem) is known to be NP-hard, so many grammar-transform algorithms are proposed from theoretical and practical viewpoints.
Generally, the produced grammar 
  
    
      
        G
      
    
    
  
 is further compressed by statistical encoders like arithmetic coding.

## Related

- [[Shannon's source coding theorem]]
- [[Bar product]]
- [[Canonical Huffman code]]
- [[Distributed source coding]]
- [[Entropy (information theory)]]
- [[Error exponent]]
- [[Generalized minimum-distance decoding]]
- [[Gibbs' inequality]]
- [[Hamming distance]]
- [[Homomorphic signatures for network coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Grammar-based_code