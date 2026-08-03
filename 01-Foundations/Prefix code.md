---
title: "Prefix code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Prefix_code"
wikipedia_categories: ["Coding theory", "Data compression", "Lossless compression algorithms", "Prefixes"]
related: ["[[Canonical Huffman code]]", "[[Recursive indexing]]", "[[Dynamic Markov compression]]", "[[Grammar-based code]]", "[[Package-merge algorithm]]", "[[Sardinas–Patterson algorithm]]", "[[Shannon's source coding theorem]]", "[[Unary coding]]", "[[Variable-length encoding]]", "[[Algebraic geometry code]]"]
---

# Prefix code

A prefix code is a type of code system distinguished by its possession of the prefix property, which requires that there is no whole code word in the system that is a prefix (initial segment) of any other code word in the system. It is trivially true for fixed-length codes, so only a point of consideration for variable-length codes.
For example, a code with code 
  
    
      
        
          
            a
          
        
        ,
        
          
            bb
          
        
      
    
    
  
 has the prefix property; a code consisting of 
  
    
      
        
          
            a
          
        
        ,
        
          
            b
          
        
        ,
        
          
            ab
          
        
        ,
        
          
            aa
          
        
      
    
    
  
 does not, because a is a prefix of ab and also of aa. A prefix code is a uniquely decodable code: given a complete and accurate sequence, a receiver can identify each word without requiring a special marker between words. However, there are uniquely decodable codes that are not prefix codes; for instance, the reverse of a prefix code is still uniquely decodable (it is a suffix code), but it is not necessarily a prefix code.
Prefix codes are also known as prefix-free codes, prefix condition codes and instantaneous codes. Although Huffman coding is just one of many algorithms for deriving prefix codes, prefix codes are also widely referred to as "Huffman codes", even when the code was not produced by a Huffman algorithm. The term comma-free code is sometimes also applied as a synonym for prefix-free codes but in most mathematical books and articles (e.g.) a comma-free code is used to mean a self-synchronizing code, a subclass of prefix codes.
Using prefix codes, a message can be transmitted as a sequence of concatenated code words, without any out-of-band markers or (alternatively) special markers between words to frame the words in the message. The recipient can decode the message unambiguously, by repeatedly finding and removing sequences that form valid code words. This is not generally possible with codes that lack the prefix property, for example 
  
    
      
        
          
            0
          
        
        ,
        
          
            1
          
        
        ,
        
          
            10
          
        
        ,
        
          
            11
          
        
      
    
    
  
: a receiver reading a 1 at the start of a code word would not know whether that was the complete code word 1, or merely the prefix of the code word 10 or 11; so the string 10 could be interpreted either as a single codeword or as the concatenation of the words 1 then 0.
The variable-length Huffman codes, telephone country codes, the country and publisher parts of ISBNs, the Secondary Synchronization Codes used in the UMTS W-CDMA 3G Wireless Standard, and the instruction sets (machine language) of most computer microarchitectures are prefix codes.
Prefix codes are not error-correcting codes. In practice, a message might first be compressed with a prefix code, and then encoded again with channel coding (including error correction) before transmission.
For every uniquely decodable code there is a prefix code that has the same code word lengths. Kraft's inequality characterizes the sets of code word lengths that are possible in a uniquely decodable code.

## Related

- [[Canonical Huffman code]]
- [[Recursive indexing]]
- [[Dynamic Markov compression]]
- [[Grammar-based code]]
- [[Package-merge algorithm]]
- [[Sardinas–Patterson algorithm]]
- [[Shannon's source coding theorem]]
- [[Unary coding]]
- [[Variable-length encoding]]
- [[Algebraic geometry code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Prefix_code