---
title: "Guruswami–Sudan list decoding algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Guruswami–Sudan_list_decoding_algorithm"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Guruswami–Sudan list decoding algorithm

In coding theory, list decoding is an alternative to unique decoding of error-correcting codes in the presence of many errors.  If a code has relative distance 
  
    
      
        δ
      
    
    
  
, then it is possible in principle to recover an encoded message when up to 
  
    
      
        δ
        
          /
        
        2
      
    
    
  
 fraction of the codeword symbols are corrupted. But when error rate is greater than 
  
    
      
        δ
        
          /
        
        2
      
    
    
  
, this will not in general be possible.  List decoding overcomes that issue by allowing the decoder to output a short list of messages that might have been encoded.  List decoding can correct more than 
  
    
      
        δ
        
          /
        
        2
      
    
    
  
 fraction of errors.
There are many polynomial-time algorithms for list decoding.  In this article, we first present an algorithm for Reed–Solomon (RS) codes which corrects up to 
  
    
      
        1
        
          
            2
            R
          
        
      
    
    
  
 errors and is due to Madhu Sudan.  Subsequently, we describe the improved Guruswami–Sudan list decoding algorithm, which can correct up to 
  
    
      
        1
        
          
            R
          
        
      
    
    
  
 errors.
Here is a plot of the rate R and distance 
  
    
      
        δ
      
    
    
  
 for different algorithms.
https://wiki.cse.buffalo.edu/cse545/sites/wiki.cse.buffalo.edu.cse545/files/81/Graph.jpg

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]
- [[Berlekamp switching game]]
- [[Berlekamp–Welch algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Guruswami–Sudan_list_decoding_algorithm