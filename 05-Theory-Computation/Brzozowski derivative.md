---
title: "Brzozowski derivative"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Brzozowski_derivative"
wikipedia_categories: ["Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# Brzozowski derivative

In theoretical computer science, particularly in formal language theory, the Brzozowski derivative 
  
    
      
        
          u
          
            1
          
        
        S
      
    
    
  
 of a set 
  
    
      
        S
      
    
    
  
 of strings and a string 
  
    
      
        u
      
    
    
  
 is the set of all strings obtainable from a string in 
  
    
      
        S
      
    
    
  
 by cutting off the prefix 
  
    
      
        u
      
    
    
  
. Formally:

  
    
      
        
          u
          
            1
          
        
        S
        {
        v
        ∈
        
          Σ
          
          
        
        ∣
        u
        v
        ∈
        S
      
    
    
  
.
For example,

  
    
      
        
          
            c
          
          
            1
          
        
        
          cat
        
        ,
        
          cow
        
        ,
        
          dog
        
        =
        
          at
        
        ,
        
          ow
        
        .
      
    
    
  

The Brzozowski derivative was introduced under various different names since the late 1950s.
Today it is named after the computer scientist Janusz Brzozowski who investigated its properties and gave an algorithm to compute the derivative of a generalized regular expression.

## Related

- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]
- [[Adaptive grammar]]
- [[Affix grammar]]
- [[Agent Communications Language]]
- [[Algorithmic learning theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Brzozowski_derivative