---
title: "Hamming space"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hamming_space"
wikipedia_categories: ["Coding theory", "Linear algebra", "Linear algebra stubs"]
related: ["[[Asymmetric norm]]", "[[Eigengap]]", "[[Independent equation]]", "[[K-frame]]", "[[Lapped transform]]", "[[Liouville space]]", "[[Locally finite operator]]", "[[Matrix pencil]]", "[[Mixed linear complementarity problem]]", "[[Modeshape]]"]
---

# Hamming space

In statistics and coding theory, a Hamming space is usually the set of all 
  
    
      
        
          2
          
            N
          
        
      
    
    
  
 binary strings of length N, where different binary strings are considered to be adjacent when they differ only in one position. The total distance between any two binary strings is then the total number of positions at which the corresponding bits are different, called the Hamming distance. Hamming spaces are named after American mathematician Richard Hamming, who introduced the concept in 1950. They are used in the theory of coding signals and transmission.
More generally, a Hamming space can be defined over any alphabet (set) Q as the set of words of a fixed length N with letters from Q. If Q is a finite field, then a Hamming space over Q is an N-dimensional vector space over Q. In the typical, binary case, the field is thus GF(2) (also denoted by Z2).
In coding theory, if Q has q elements, then any subset C (usually assumed of cardinality at least two) of the N-dimensional Hamming space over Q is called a q-ary code of length N; the elements of C are called codewords. In the case where C is a linear subspace of its Hamming space, it is called a linear code. A typical example of linear code is the Hamming code. Codes defined via a Hamming space necessarily have the same length for every codeword, so they are called block codes when it is necessary to distinguish them from variable-length codes that are defined by unique factorization on a monoid.
The Hamming distance endows a Hamming space with a metric, which is essential in defining basic notions of coding theory such as error detecting and error correcting codes.
Hamming spaces over non-field alphabets have also been considered, especially over finite rings (most notably over Z4) giving rise to modules instead of vector spaces and ring-linear codes (identified with submodules) instead of linear codes. The typical metric used in this case the Lee distance. There exist a Gray isometry between 
  
    
      
        
          
            Z
          
          
            2
          
          
            2
            m
          
        
      
    
    
  
 (i.e. GF(22m)) with the Hamming distance and 
  
    
      
        
          
            Z
          
          
            4
          
          
            m
          
        
      
    
    
  
 (also denoted as GR(4,m)) with the Lee distance.

## Related

- [[Asymmetric norm]]
- [[Eigengap]]
- [[Independent equation]]
- [[K-frame]]
- [[Lapped transform]]
- [[Liouville space]]
- [[Locally finite operator]]
- [[Matrix pencil]]
- [[Mixed linear complementarity problem]]
- [[Modeshape]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hamming_space