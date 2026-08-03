---
title: "Berlekamp–Welch algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Berlekamp–Welch_algorithm"
wikipedia_categories: ["Coding theory", "Error detection and correction", "Finite fields"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Concatenated error correction code]]", "[[Generalized minimum-distance decoding]]", "[[Homomorphic signatures for network coding]]", "[[Justesen code]]", "[[Preparata code]]", "[[Srivastava code]]", "[[Zyablov bound]]", "[[Algebraic geometry code]]"]
---

# Berlekamp–Welch algorithm

The Berlekamp–Welch algorithm, also known as the Welch–Berlekamp algorithm, is named for Elwyn R. Berlekamp and Lloyd R. Welch. This is a decoder algorithm that efficiently corrects errors in Reed–Solomon codes for an RS(n, k), code based on the Reed Solomon original view where a message 
  
    
      
        
          m
          
            1
          
        
        ,
        ⋯
        ,
        
          m
          
            k
          
        
      
    
    
  
 is used as coefficients of a polynomial 
  
    
      
        F
        
          a
          
            i
          
        
      
    
    
  
 or used with Lagrange interpolation to generate the polynomial 
  
    
      
        F
        
          a
          
            i
          
        
      
    
    
  
 of degree < k for inputs 
  
    
      
        
          a
          
            1
          
        
        ,
        ⋯
        ,
        
          a
          
            k
          
        
      
    
    
  
 and then 
  
    
      
        F
        
          a
          
            i
          
        
      
    
    
  
 is applied to 
  
    
      
        
          a
          
            k
            1
          
        
        ,
        ⋯
        ,
        
          a
          
            n
          
        
      
    
    
  
 to create an encoded codeword 
  
    
      
        
          c
          
            1
          
        
        ,
        ⋯
        ,
        
          c
          
            n
          
        
      
    
    
  
.
The goal of the decoder is to recover the original encoding polynomial 
  
    
      
        F
        
          a
          
            i
          
        
      
    
    
  
, using the known inputs 
  
    
      
        
          a
          
            1
          
        
        ,
        ⋯
        ,
        
          a
          
            n
          
        
      
    
    
  
 and received codeword 
  
    
      
        
          b
          
            1
          
        
        ,
        ⋯
        ,
        
          b
          
            n
          
        
      
    
    
  
 with possible errors. It also computes an error polynomial 
  
    
      
        E
        
          a
          
            i
          
        
      
    
    
  
 where 
  
    
      
        E
        
          a
          
            i
          
        
        =
        0
      
    
    
  
 corresponding to errors in the received codeword.

## Related

- [[Alternant code]]
- [[BCH code]]
- [[Concatenated error correction code]]
- [[Generalized minimum-distance decoding]]
- [[Homomorphic signatures for network coding]]
- [[Justesen code]]
- [[Preparata code]]
- [[Srivastava code]]
- [[Zyablov bound]]
- [[Algebraic geometry code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Berlekamp–Welch_algorithm