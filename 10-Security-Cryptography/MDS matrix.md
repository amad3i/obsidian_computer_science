---
title: "MDS matrix"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/MDS_matrix"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# MDS matrix

An MDS matrix (maximum distance separable) is a matrix representing a function with certain diffusion properties that have useful applications in cryptography. Technically, an 
  
    
      
        m
        n
      
    
    
  
 matrix 
  
    
      
        A
      
    
    
  
 over a finite field 
  
    
      
        K
      
    
    
  
 is an MDS matrix if it is the transformation matrix of a linear transformation 
  
    
      
        f
        x
        =
        A
        x
      
    
    
  
 from 
  
    
      
        
          K
          
            n
          
        
      
    
    
  
 to 
  
    
      
        
          K
          
            m
          
        
      
    
    
  
 such that no two different 
  
    
      
        m
        n
      
    
    
  
-tuples of the form 
  
    
      
        x
        ,
        f
        x
        )
      
    
    
  
 coincide in 
  
    
      
        n
      
    
    
  
 or more components.
Equivalently, the set of all 
  
    
      
        m
        n
      
    
    
  
-tuples 
  
    
      
        x
        ,
        f
        x
        )
      
    
    
  
 is an MDS code, i.e., a linear code that reaches the Singleton bound.
Let 
  
    
      
        
          
            
              A
              ~
            
          
        
        
          
            
              
                
                  
                    
                      I
                    
                    
                      n
                    
                  
                
              
              
                
                  
                    A
                  
                
              
            
          
        
      
    
    
  
 be the matrix obtained by joining the identity matrix 
  
    
      
        
          
            I
          
          
            n
          
        
      
    
    
  
 to 
  
    
      
        A
      
    
    
  
. Then a necessary and sufficient condition for a matrix 
  
    
      
        A
      
    
    
  
 to be MDS is that every possible 
  
    
      
        n
        n
      
    
    
  
 submatrix obtained by removing 
  
    
      
        m
      
    
    
  
 rows from 
  
    
      
        
          
            
              A
              ~
            
          
        
      
    
    
  
 is non-singular. This is also equivalent to the following: all the sub-determinants of the matrix 
  
    
      
        A
      
    
    
  
 are non-zero. Then a binary matrix 
  
    
      
        A
      
    
    
  
 (namely over the field with two elements) is never MDS unless it has only one row or only one column with all components 
  
    
      
        1
      
    
    
  
.
Reed–Solomon codes have the MDS property and are frequently used to obtain the MDS matrices used in cryptographic algorithms.
Serge Vaudenay suggested using MDS matrices in cryptographic primitives to produce what he called multipermutations, not-necessarily linear functions with this same property. These functions have what he called perfect diffusion: changing 
  
    
      
        t
      
    
    
  
 of the inputs changes at least 
  
    
      
        m
        t
        1
      
    
    
  
 of the outputs. He showed how to exploit imperfect diffusion to cryptanalyze functions that are not multipermutations.
MDS matrices are used for diffusion in such block ciphers as AES, SHARK, Square, Twofish, Anubis, KHAZAD, Manta, Hierocrypt, Kalyna, Camellia and HADESMiMC, and in the stream cipher MUGI and the cryptographic hash function Whirlpool, Poseidon.

## Related

- [[Batch cryptography]]
- [[Branch number]]
- [[Cipher device]]
- [[Ciphertext expansion]]
- [[Client-side encryption]]
- [[Codress message]]
- [[Completeness (cryptography)]]
- [[Conjugate coding]]
- [[Correlation immunity]]
- [[Cover (telecommunications)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MDS_matrix