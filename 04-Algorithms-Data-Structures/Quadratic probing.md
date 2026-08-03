---
title: "Quadratic probing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Quadratic_probing"
wikipedia_categories: ["Hashing", "Search algorithms"]
related: ["[[Cuckoo hashing]]", "[[Double hashing]]", "[[Dynamic perfect hashing]]", "[[Extendible hashing]]", "[[Hopscotch hashing]]", "[[Index mapping]]", "[[Linear hashing]]", "[[Linear probing]]", "[[Locality-sensitive hashing]]", "[[Perfect hash function]]"]
---

# Quadratic probing

Quadratic probing is an open addressing scheme in computer programming for resolving hash collisions in hash tables. Quadratic probing operates by taking the original hash index and adding successive values of an arbitrary quadratic polynomial until an open slot is found.
An example sequence using quadratic probing is:

  
    
      
        H
        
          1
          
            2
          
        
        ,
        H
        
          2
          
            2
          
        
        ,
        H
        
          3
          
            2
          
        
        ,
        H
        
          4
          
            2
          
        
        ,
        .
        .
        .
        ,
        H
        
          k
          
            2
          
        
      
    
    
  

Quadratic probing is often recommended as an alternative to linear probing because it incurs less clustering. Quadratic probing exhibits better locality of reference than many other hash table such as chaining; however, for queries, quadratic probing does not have as good locality as linear probing, causing the latter to be faster in some settings.

## Related

- [[Cuckoo hashing]]
- [[Double hashing]]
- [[Dynamic perfect hashing]]
- [[Extendible hashing]]
- [[Hopscotch hashing]]
- [[Index mapping]]
- [[Linear hashing]]
- [[Linear probing]]
- [[Locality-sensitive hashing]]
- [[Perfect hash function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quadratic_probing