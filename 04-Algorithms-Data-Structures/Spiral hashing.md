---
title: "Spiral hashing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Spiral_hashing"
wikipedia_categories: ["Hashing", "Search algorithms"]
related: ["[[Cuckoo hashing]]", "[[Double hashing]]", "[[Dynamic perfect hashing]]", "[[Extendible hashing]]", "[[Hopscotch hashing]]", "[[Index mapping]]", "[[Linear hashing]]", "[[Linear probing]]", "[[Locality-sensitive hashing]]", "[[Perfect hash function]]"]
---

# Spiral hashing

Spiral hashing, also known as Spiral Storage is an extensible 
hashing algorithm. As in all hashing schemes, spiral hashing stores records in a varying number of buckets, using a record key for addressing. In an expanding Linear hashing file, buckets are split in a predefined order. This results in adding a new bucket at the end of the file. While this allows gradual reorganization of the file, the expected number of records in the newly created bucket and the bucket from what it splits falls to half the previous number. Several attempts were made to alleviate this sudden drop in space utilization. Martin's spiral storage uses a different approach. The file consists of a number of continuously numbered buckets. The lower-numbered (left) buckets have a higher expected number of records. When the file expands, the left-most bucket is replaced by two buckets on the right. Some variants of this idea exist.
Spiral hashing requires a uniform hash function of the keys of the records into the unit interval 
  
    
      
        0
        ,
        1
      
    
    
  
. If the hash file starts at bucket 
  
    
      
        S
      
    
    
  
, the key 
  
    
      
        k
      
    
    
  
 is mapped into a real number 
  
    
      
        x
        S
        h
        k
        ∈
        S
        ,
        S
        1
      
    
    
  
. The final address is then computed as 
  
    
      
        ⌊
        
          d
          
            x
          
        
        ⌋
      
    
    
  
 where 
  
    
      
        d
      
    
    
  
 is the "extension factor". When 
  
    
      
        S
      
    
    
  
 is incremented, approximately 
  
    
      
        d
      
    
    
  
 new buckets are created on the right. Larson  conducted experiments that showed that Linear hashing still had superior performance over Spiral Hashing.

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

- Wikipedia: https://en.wikipedia.org/wiki/Spiral_hashing