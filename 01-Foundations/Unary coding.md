---
title: "Unary coding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Unary_coding"
wikipedia_categories: ["Coding theory", "Data compression", "Entropy coding"]
related: ["[[Variable-length encoding]]", "[[Canonical Huffman code]]", "[[Grammar-based code]]", "[[Prefix code]]", "[[Recursive indexing]]", "[[Sardinas–Patterson algorithm]]", "[[Shannon's source coding theorem]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]"]
---

# Unary coding

Unary coding, or the unary numeral system, is an entropy encoding that represents a natural number, n, with n ones followed by a zero (if the term natural number is understood as non-negative integer) or with n − 1 ones followed by a zero (if the term natural number is understood as strictly positive integer). A unary number's code length would thus be n + 1 with that first definition, or n with that second definition. Unary code when vertical behaves like mercury in a thermometer that gets taller or shorter as n gets bigger or smaller, and so is sometimes called thermometer code. An alternative representation uses n or n − 1 zeros followed by a one, effectively swapping the ones and zeros, without loss of generality. For example, the first ten unary codes are:

Unary coding is an optimally efficient encoding for the following discrete probability distribution

  
    
      
        P
         
        n
        =
        
          2
          
            n
          
        
        
      
    
    
  

for 
  
    
      
        n
        1
        ,
        2
        ,
        3
        ,
        .
        .
        .
      
    
    
  
.
In symbol-by-symbol coding, it is optimal for any geometric distribution

  
    
      
        P
         
        n
        =
        k
        1
        
          k
          
            n
          
        
        
      
    
    
  

for which k ≥ φ = 1.61803398879..., the golden ratio, or, more generally, for any discrete distribution for which

  
    
      
        P
         
        n
        ≥
        P
         
        n
        1
        +
        P
         
        n
        2
        
      
    
    
  

for 
  
    
      
        n
        1
        ,
        2
        ,
        3
        ,
        .
        .
        .
      
    
    
  
.  Although it is the optimal symbol-by-symbol coding for such probability distributions, Golomb coding achieves better compression capability for the geometric distribution because it does not consider input symbols independently, but rather implicitly groups the inputs. For the same reason, arithmetic encoding performs better for general probability distributions, as in the last case above.
Unary coding is both a prefix-free code and a self-synchronizing code.

## Related

- [[Variable-length encoding]]
- [[Canonical Huffman code]]
- [[Grammar-based code]]
- [[Prefix code]]
- [[Recursive indexing]]
- [[Sardinas–Patterson algorithm]]
- [[Shannon's source coding theorem]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unary_coding