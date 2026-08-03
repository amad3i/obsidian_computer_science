---
title: "Interchange lemma"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Interchange_lemma"
wikipedia_categories: ["Formal languages", "Grammar stubs", "Lemmas"]
related: ["[[Growing context-sensitive grammar]]", "[[Ogden's lemma]]", "[[Pumping lemma for context-free languages]]", "[[Pumping lemma for regular languages]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]"]
---

# Interchange lemma

In the theory of formal languages, the interchange lemma states a necessary condition for a language to be context-free, just like the pumping lemma for context-free languages.
It states that for every context-free language 
  
    
      
        L
      
    
    
  
 there is a 
  
    
      
        c
        0
      
    
    
  
 such that for all 
  
    
      
        n
        ≥
        m
        ≥
        2
      
    
    
  
 for any collection of length 
  
    
      
        n
      
    
    
  
 words 
  
    
      
        R
        ⊂
        L
      
    
    
  
 there is a 
  
    
      
        Z
        {
        
          z
          
            1
          
        
        ,
        …
        ,
        
          z
          
            k
          
        
        ⊂
        R
      
    
    
  
 with 
  
    
      
        k
        ≥
        
          |
        
        R
        
          |
        
        
          /
        
        c
        
          n
          
            2
          
        
      
    
    
  
, and decompositions 
  
    
      
        
          z
          
            i
          
        
        
          w
          
            i
          
        
        
          x
          
            i
          
        
        
          y
          
            i
          
        
      
    
    
  
 such that each of 
  
    
      
        
          |
        
        
          w
          
            i
          
        
        
          |
        
      
    
    
  
, 
  
    
      
        
          |
        
        
          x
          
            i
          
        
        
          |
        
      
    
    
  
, 
  
    
      
        
          |
        
        
          y
          
            i
          
        
        
          |
        
      
    
    
  
 is independent of 
  
    
      
        i
      
    
    
  
, moreover, 
  
    
      
        m
        
          /
        
        2
        
          |
        
        
          x
          
            i
          
        
        
          |
        
        ≤
        m
      
    
    
  
, and the words 
  
    
      
        
          w
          
            i
          
        
        
          x
          
            j
          
        
        
          y
          
            i
          
        
      
    
    
  
 are in 
  
    
      
        L
      
    
    
  
 for every 
  
    
      
        i
      
    
    
  
 and 
  
    
      
        j
      
    
    
  
.
The first application of the interchange lemma was to show that the set of repetitive strings (i.e., strings of the form 
  
    
      
        x
        y
        y
        z
      
    
    
  
 with 
  
    
      
        
          |
        
        y
        
          |
        
        0
      
    
    
  
) over an alphabet of three or more characters is not context-free.

## Related

- [[Growing context-sensitive grammar]]
- [[Ogden's lemma]]
- [[Pumping lemma for context-free languages]]
- [[Pumping lemma for regular languages]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interchange_lemma