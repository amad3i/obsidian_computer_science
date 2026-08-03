---
title: "Pumping lemma for regular languages"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Pumping_lemma_for_regular_languages"
wikipedia_categories: ["Finite-state machines", "Formal languages", "Lemmas"]
related: ["[[Interchange lemma]]", "[[Myhill–Nerode theorem]]", "[[Ogden's lemma]]", "[[Pumping lemma for context-free languages]]", "[[Regular language]]", "[[Tree transducer]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]"]
---

# Pumping lemma for regular languages

In the theory of formal languages, the pumping lemma for regular languages is a lemma that describes an essential property of all regular languages. Informally, it says that all sufficiently long strings in a regular language may be pumped—that is, have a middle section of the string repeated an arbitrary number of times—to produce a new string that is also part of the language. The pumping lemma is useful for proving that a specific language is not a regular language, by showing that the language does not have the property.
Specifically, the pumping lemma says that for any regular language 
  
    
      
        L
      
    
    
  
, there exists a constant 
  
    
      
        p
      
    
    
  
 such that any string 
  
    
      
        w
      
    
    
  
 in 
  
    
      
        L
      
    
    
  
 with length at least 
  
    
      
        p
      
    
    
  
 can be split into three substrings 
  
    
      
        x
      
    
    
  
, 
  
    
      
        y
      
    
    
  
 and 
  
    
      
        z
      
    
    
  
  
    
      
        w
        x
        y
        z
      
    
    
  
, with 
  
    
      
        y
      
    
    
  
 being non-empty), such that the strings 
  
    
      
        x
        z
        ,
        x
        y
        z
        ,
        x
        y
        y
        z
        ,
        x
        y
        y
        y
        z
        ,
        .
        .
        .
      
    
    
  
 are also in 
  
    
      
        L
      
    
    
  
. The process of repeating 
  
    
      
        y
      
    
    
  
 zero or more times is known as "pumping". Moreover, the pumping lemma guarantees that the length of 
  
    
      
        x
        y
      
    
    
  
 will be at most 
  
    
      
        p
      
    
    
  
, thus giving a "small" substring 
  
    
      
        x
        y
      
    
    
  
 that has the desired property. 
Languages with a finite number of strings vacuously satisfy the pumping lemma by having 
  
    
      
        p
      
    
    
  
 equal to the maximum string length in 
  
    
      
        L
      
    
    
  
 plus one. By doing so, no strings at all in 
  
    
      
        L
      
    
    
  
 have length at least 
  
    
      
        p
      
    
    
  
.
The pumping lemma was first proven by Michael Rabin and Dana Scott in 1959, and rediscovered shortly after by Yehoshua Bar-Hillel, Micha A. Perles, and Eli Shamir in 1961, as a simplification of their pumping lemma for context-free languages.

## Related

- [[Interchange lemma]]
- [[Myhill–Nerode theorem]]
- [[Ogden's lemma]]
- [[Pumping lemma for context-free languages]]
- [[Regular language]]
- [[Tree transducer]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pumping_lemma_for_regular_languages