---
title: "Reed–Muller code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Reed–Muller_code"
wikipedia_categories: ["Coding theory", "Error detection and correction", "Theoretical computer science"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Coset leader]]", "[[Delsarte–Goethals code]]"]
---

# Reed–Muller code

Reed–Muller codes are error-correcting codes that are used in wireless communications applications, particularly in deep-space communication. In cryptography, duplicated Reed–Muller codes are concatenated with shortened Reed–Solomon codes in the Hamming Quasi-Cyclic (HQC) key encapsulation mechanism selected by NIST for standardization as an alternative quantum-resistant algorithm.  Moreover, the proposed 5G standard relies on the closely related polar codes for error correction in the control channel. Due to their favorable theoretical and mathematical properties, Reed–Muller codes have also been extensively studied in theoretical computer science. For example, they have been shown to asymptotically achieve Shannon capacity on symmetric memoryless channels.
Reed–Muller codes generalize the Reed–Solomon codes and the Walsh–Hadamard code. Reed–Muller codes are linear block codes that are locally testable, locally decodable, and list decodable. These properties make them particularly useful in the design of probabilistically checkable proofs.
Traditional Reed–Muller codes are binary codes, which means that messages and codewords are binary strings. When r and m are integers with 0 ≤ r ≤ m, the Reed–Muller code with parameters  r and m is denoted as RM(r, m). When asked to encode a message consisting of k bits, where  
  
    
      
        
          k
          
            ∑
            
              i
              0
            
            
              r
            
          
          
            
              
              
              
                m
                i
              
              
              
            
          
        
      
    
    
  
 holds, the RM(r, m) code produces a codeword consisting of 2m bits.
Reed–Muller codes are named after David E. Muller, who discovered the codes in 1954, and Irving S. Reed, who proposed the first efficient decoding algorithm.

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

- Wikipedia: https://en.wikipedia.org/wiki/Reed–Muller_code