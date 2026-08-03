---
title: "Hadamard code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hadamard_code"
wikipedia_categories: ["Coding theory", "Error detection and correction"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Coset leader]]", "[[Delsarte–Goethals code]]"]
---

# Hadamard code

The Hadamard code is an error-correcting code named after the French mathematician Jacques Hadamard that is used for error detection and correction when transmitting messages over very noisy or unreliable channels. In 1971, the code was used to transmit photos of Mars back to Earth from the NASA space probe Mariner 9. Because of its unique mathematical properties, the Hadamard code is not only used by engineers, but also intensely studied in coding theory, mathematics, and theoretical computer science.
The Hadamard code is also known under the names Walsh code, Walsh family, and Walsh–Hadamard code in recognition of the American mathematician Joseph Leonard Walsh.
The Hadamard code's mathematical specification is rather involved, and is described under Constructions.  It is an example of a linear code of length 
  
    
      
        
          2
          
            m
          
        
      
    
    
  
 over a binary alphabet.
Unfortunately, this term is somewhat ambiguous as some references assume a message length 
  
    
      
        k
        m
      
    
    
  
 while others assume a message length of 
  
    
      
        k
        m
        1
      
    
    
  
.
In this article, the first case is called the Hadamard code while the second is called the augmented Hadamard code.
The Hadamard code is unique in that each non-zero codeword has a Hamming weight of exactly 
  
    
      
        
          2
          
            k
            1
          
        
      
    
    
  
, which implies that the distance of the code is also 
  
    
      
        
          2
          
            k
            1
          
        
      
    
    
  
.
In standard coding theory notation for block codes, the Hadamard code is a 
  
    
      
        
          2
          
            k
          
        
        ,
        k
        ,
        
          2
          
            k
            1
          
        
        
          
            2
          
        
      
    
    
  
-code, that is, it is a linear code over a binary alphabet, has block length 
  
    
      
        
          2
          
            k
          
        
      
    
    
  
, message length (or dimension) 
  
    
      
        k
      
    
    
  
, and minimum distance 
  
    
      
        
          2
          
            k
          
        
        
          /
        
        2
      
    
    
  
.
The block length is very large compared to the message length, but on the other hand, errors can be corrected even in extremely noisy conditions.
The augmented Hadamard code is a slightly improved version of the Hadamard code; it is a 
  
    
      
        
          2
          
            k
          
        
        ,
        k
        1
        ,
        
          2
          
            k
            1
          
        
        
          
            2
          
        
      
    
    
  
-code and thus has a slightly better rate while maintaining the relative distance of 
  
    
      
        1
        
          /
        
        2
      
    
    
  
, and is thus preferred in practical applications.
In communication theory, this is simply called the Hadamard code and it is the same as the first order Reed–Muller code over the binary alphabet.
Normally, Hadamard codes are based on Sylvester's construction of Hadamard matrices, but the term “Hadamard code” is also used to refer to codes constructed from arbitrary Hadamard matrices, which are not necessarily of Sylvester type.
In general, such a code is not linear.
Such codes were first constructed by Raj Chandra Bose and Sharadchandra Shankar Shrikhande in 1959.
If n is the size of the Hadamard matrix, the code has parameters 
  
    
      
        n
        ,
        2
        n
        ,
        n
        
          /
        
        2
        
          
            2
          
        
      
    
    
  
, meaning it is a not-necessarily-linear binary code with 2n codewords of block length n and minimal distance n/2. The construction and decoding scheme described below apply for general n, but the property of linearity and the identification with Reed–Muller codes require that n be a power of 2 and that the Hadamard matrix be equivalent to the matrix constructed by Sylvester's method.
The Hadamard code is a locally decodable code, which provides a way to recover parts of the original message with high probability, while only looking at a small fraction of the received word. This gives rise to applications in computational complexity theory and particularly in the design of probabilistically checkable proofs.
Since the relative distance of the Hadamard code is 1/2, normally one can only hope to recover from at most a 1/4 fraction of error. Using list decoding, however, it is possible to compute a short list of possible candidate messages as long as fewer than 
  
    
      
        
          
            1
            2
          
        
        ϵ
      
    
    
  
 of the bits in the received word have been corrupted.
In code-division multiple access (CDMA) communication, the Hadamard code is referred to as Walsh Code, and is used to define individual communication channels. It is usual in the CDMA literature to refer to codewords as “codes”. Each user will use a different codeword, or “code”, to modulate their signal. Because Walsh codewords are mathematically orthogonal, a Walsh-encoded signal appears as random noise to a CDMA capable mobile terminal, unless that terminal uses the same codeword as the one used to encode the incoming signal.

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

- Wikipedia: https://en.wikipedia.org/wiki/Hadamard_code