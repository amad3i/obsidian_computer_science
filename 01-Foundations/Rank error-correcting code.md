---
title: "Rank error-correcting code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rank_error-correcting_code"
wikipedia_categories: ["Coding theory", "Error detection and correction"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Coset leader]]", "[[Delsarte–Goethals code]]"]
---

# Rank error-correcting code

In coding theory, rank codes (also called Gabidulin codes) are non-binary linear error-correcting codes over not Hamming but rank metric. They described a systematic way of building codes that could detect and correct multiple random rank errors. By adding redundancy with coding k-symbol word to a n-symbol word, a rank code can correct any errors of rank up to t = ⌊ (d − 1) / 2 ⌋, where d is a code distance. As an erasure code, it can correct up to d − 1 known erasures.
A rank code is an algebraic linear code over the finite field 
  
    
      
        G
        F
        
          q
          
            N
          
        
      
    
    
  
 similar to Reed–Solomon code.
The rank of the vector over 
  
    
      
        G
        F
        
          q
          
            N
          
        
      
    
    
  
 is the maximum number of linearly independent components over 
  
    
      
        G
        F
        q
      
    
    
  
. The rank distance between two vectors over 
  
    
      
        G
        F
        
          q
          
            N
          
        
      
    
    
  
 is the rank of the difference of these vectors.
The rank code corrects all errors with rank of the error vector not greater than t.

## Related

- [[Alternant code]]
- [[BCH code]]
- [[Berger code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Concatenated error correction code]]
- [[Coset leader]]
- [[Delsarte–Goethals code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rank_error-correcting_code