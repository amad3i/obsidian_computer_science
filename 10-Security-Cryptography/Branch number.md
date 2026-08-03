---
title: "Branch number"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Branch_number"
wikipedia_categories: ["Cryptography", "Cryptography stubs"]
related: ["[[Batch cryptography]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]", "[[Cover-coding]]"]
---

# Branch number

In cryptography, the branch number is a numerical value that characterizes the amount of diffusion introduced by a vectorial Boolean function F that maps an input vector a to output vector 
  
    
      
        F
        a
      
    
    
  
. For the (usual) case of a linear F the value of the differential branch number is produced by:

applying nonzero values of a (i.e., values that have at least one non-zero component of the vector) to the input of F;
calculating for each input value a the Hamming weight 
  
    
      
        W
      
    
    
  
 (number of nonzero components), and adding weights 
  
    
      
        W
        a
      
    
    
  
 and 
  
    
      
        W
        F
        a
        )
      
    
    
  
 together;
selecting the smallest combined weight across for all nonzero input values: 
  
    
      
        
          B
          
            d
          
        
        F
        =
        
          
            min
            
              a
              ≠
              0
            
          
        
        W
        a
        +
        W
        F
        a
        )
      
    
    
  
.
If both a and 
  
    
      
        F
        a
      
    
    
  
 have s components, the result is obviously limited on the high side by the value 
  
    
      
        s
        1
      
    
    
  
 (this "perfect" result is achieved when any single nonzero component in a makes all components of 
  
    
      
        F
        a
      
    
    
  
 to be non-zero). A high branch number suggests higher resistance to the differential cryptanalysis: the small variations of input will produce large changes on the output and in order to obtain small variations of the output, large changes of the input value will be required.
The term was introduced by Daemen and Rijmen in early 2000s and quickly became a typical tool to assess the diffusion properties of the transformations.

## Related

- [[Batch cryptography]]
- [[Cipher device]]
- [[Ciphertext expansion]]
- [[Client-side encryption]]
- [[Codress message]]
- [[Completeness (cryptography)]]
- [[Conjugate coding]]
- [[Correlation immunity]]
- [[Cover (telecommunications)]]
- [[Cover-coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Branch_number