---
title: "Conjunctive grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Conjunctive_grammar"
wikipedia_categories: ["Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# Conjunctive grammar

Conjunctive grammars are a class of formal grammars
studied in formal language theory.
They extend the basic type of grammars,
the context-free grammars,
with a conjunction operation.
Besides explicit conjunction,
conjunctive grammars allow implicit disjunction
represented by multiple rules for a single nonterminal symbol,
which is the only logical connective expressible in context-free grammars.
Conjunction can be used, in particular,
to specify intersection of languages.
A further extension of conjunctive grammars
known as Boolean grammars
additionally allows explicit negation.
The rules of a conjunctive grammar are of the form

  
    
      
        A
        →
        
          α
          
            1
          
        
        &
        …
        &
        
          α
          
            m
          
        
      
    
    
  

where 
  
    
      
        A
      
    
    
  
 is a nonterminal and

  
    
      
        
          α
          
            1
          
        
      
    
    
  
, ..., 
  
    
      
        
          α
          
            m
          
        
      
    
    
  

are strings formed of symbols in 
  
    
      
        Σ
      
    
    
  
 and 
  
    
      
        V
      
    
    
  
 (finite sets of terminal and nonterminal symbols respectively).
Informally, such a rule asserts that 
every string 
  
    
      
        w
      
    
    
  
 over 
  
    
      
        Σ
      
    
    
  

that satisfies each of the syntactical conditions represented
by 
  
    
      
        
          α
          
            1
          
        
      
    
    
  
, ..., 
  
    
      
        
          α
          
            m
          
        
      
    
    
  

therefore satisfies the condition defined by 
  
    
      
        A
      
    
    
  
.

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

- Wikipedia: https://en.wikipedia.org/wiki/Conjunctive_grammar