---
title: "Double hashing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Double_hashing"
wikipedia_categories: ["Hashing", "Search algorithms"]
related: ["[[Cuckoo hashing]]", "[[Dynamic perfect hashing]]", "[[Extendible hashing]]", "[[Hopscotch hashing]]", "[[Index mapping]]", "[[Linear hashing]]", "[[Linear probing]]", "[[Locality-sensitive hashing]]", "[[Perfect hash function]]", "[[Quadratic probing]]"]
---

# Double hashing

Double hashing is a computer programming technique used in conjunction with open addressing in hash tables to resolve hash collisions, by using a secondary hash of the key as an offset when a collision occurs. Double hashing with open addressing is a classical data structure on a table 
  
    
      
        T
      
    
    
  
.
The double hashing technique uses one hash value as an index into the table and then repeatedly steps forward an interval until the desired value is located, an empty location is reached, or the entire table has been searched; but this interval is set by a second, independent hash function. Unlike the alternative collision-resolution methods of linear probing and quadratic probing, the interval depends on the data, so that values mapping to the same location have different bucket sequences; this minimizes repeated collisions and the effects of clustering.
Given two random, uniform, and independent hash functions 
  
    
      
        
          h
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          h
          
            2
          
        
      
    
    
  
, the 
  
    
      
        i
      
    
    
  
th location in the bucket sequence for value 
  
    
      
        x
      
    
    
  
 in a hash table of 
  
    
      
        
          |
        
        T
        
          |
        
      
    
    
  
 buckets is: 
  
    
      
        h
        i
        ,
        x
        =
        
          h
          
            1
          
        
        x
        +
        i
        ⋅
        
          h
          
            2
          
        
        x
        )
        
          mod
          
            
              |
            
          
        
        T
        
          |
        
        .
      
    
    
  
 The locations can be conveniently calculated by incrementing the previous hash by 
  
    
      
        
          h
          
            2
          
        
        x
      
    
    
  
, i.e. 
  
    
      
        h
        i
        1
        ,
        x
        =
        h
        i
        ,
        x
        +
        
          h
          
            2
          
        
        x
        )
        
          mod
          
            
              |
            
          
        
        T
        
          |
        
        .
      
    
    
  

Generally, 
  
    
      
        
          h
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          h
          
            2
          
        
      
    
    
  
 are selected from a set of universal hash functions; 
  
    
      
        
          h
          
            1
          
        
      
    
    
  
 is selected to have a range of 
  
    
      
        0
        ,
        
          |
        
        T
        
          |
        
        1
      
    
    
  
 and 
  
    
      
        
          h
          
            2
          
        
      
    
    
  
 to have a range of 
  
    
      
        1
        ,
        
          |
        
        T
        
          |
        
        1
      
    
    
  
. Double hashing approximates a random distribution; more precisely, pair-wise independent hash functions yield a probability of 
  
    
      
        n
        
          /
        
        
          |
        
        T
        
          |
        
        
          
            2
          
        
      
    
    
  
 that any pair of keys will follow the same bucket sequence.

## Related

- [[Cuckoo hashing]]
- [[Dynamic perfect hashing]]
- [[Extendible hashing]]
- [[Hopscotch hashing]]
- [[Index mapping]]
- [[Linear hashing]]
- [[Linear probing]]
- [[Locality-sensitive hashing]]
- [[Perfect hash function]]
- [[Quadratic probing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Double_hashing