---
title: "Berger code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Berger_code"
wikipedia_categories: ["Coding theory", "Error detection and correction"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Coset leader]]", "[[Delsarte–Goethals code]]", "[[Enumerator polynomial]]"]
---

# Berger code

In telecommunications, a Berger code is a unidirectional error-detecting code. It is named after J. M. Berger, its inventor.
Berger codes can detect all unidirectional errors. Unidirectional errors are errors that only flip ones into zeroes or only zeroes into ones, such as in asymmetric channels. The check bits of Berger codes are computed by counting all the zeroes in the information word, and expressing that number in natural binary. If the information word consists of 
  
    
      
        n
      
    
    
  
 bits, then the Berger code needs 
  
    
      
        k
        ⌈
        
          
            2
          
        
         
        n
        1
        ⌉
      
    
    
  
 "check bits", giving a Berger code of length k+n. (In other words, the 
  
    
      
        k
      
    
    
  
 check bits are enough to check up to 
  
    
      
        n
        
          2
          
            k
          
        
        1
      
    
    
  
 information bits).
Berger codes can detect any number of one-to-zero bit-flip errors, as long as no zero-to-one errors occurred in the same code word.
Similarly, Berger codes can detect any number of zero-to-one bit-flip errors, as long as no one-to-zero bit-flip errors occur in the same code word.
Berger codes cannot correct any error.
Like all unidirectional error detecting codes,
Berger codes can also be used in delay-insensitive circuits.

## Related

- [[Alternant code]]
- [[BCH code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Concatenated error correction code]]
- [[Coset leader]]
- [[Delsarte–Goethals code]]
- [[Enumerator polynomial]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Berger_code