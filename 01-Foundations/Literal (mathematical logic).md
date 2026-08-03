---
title: "Literal (mathematical logic)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Literal_(mathematical_logic)"
wikipedia_categories: ["Logic symbols", "Mathematical logic", "Propositional calculus"]
related: ["[[Double turnstile]]", "[[Glossary of Principia Mathematica]]", "[[List of axiomatic systems in logic]]", "[[Predicate (logic)]]", "[[Tautology (logic)]]", "[[Turnstile (symbol)]]", "[[Absoluteness (logic)]]", "[[Abstract logic]]", "[[Abstract model theory]]", "[[Algebraic semantics (mathematical logic)]]"]
---

# Literal (mathematical logic)

In mathematical logic, a literal is an atomic formula (also known as an atom or prime formula) or its negation. The definition mostly appears in proof theory (of classical logic), e.g. in conjunctive normal form and the method of resolution.
Literals can be divided into two types:

A positive literal is just an atom (e.g., 
  
    
      
        x
      
    
    
  
).
A negative literal is the negation of an atom (e.g., 
  
    
      
        ¬
        x
      
    
    
  
).
The polarity of a literal is positive or negative depending on whether it is a positive or negative literal.
In logics with double negation elimination (where 
  
    
      
        ¬
        ¬
        x
        ≡
        x
      
    
    
  
) the complementary literal or complement of a literal 
  
    
      
        l
      
    
    
  
 can be defined as the literal corresponding to the negation of 
  
    
      
        l
      
    
    
  
. We can write 
  
    
      
        
          
            
              l
              ¯
            
          
        
      
    
    
  
 to denote the complementary literal of 
  
    
      
        l
      
    
    
  
. More precisely, if 
  
    
      
        l
        ≡
        x
      
    
    
  
 then 
  
    
      
        
          
            
              l
              ¯
            
          
        
      
    
    
  
 is 
  
    
      
        ¬
        x
      
    
    
  
 and if 
  
    
      
        l
        ≡
        ¬
        x
      
    
    
  
 then 
  
    
      
        
          
            
              l
              ¯
            
          
        
      
    
    
  
 is 
  
    
      
        x
      
    
    
  
. Double negation elimination occurs in classical logics but not in intuitionistic logic.
In the context of a formula in the conjunctive normal form, a literal is pure if the literal's complement does not appear in the formula.
In Boolean functions, each separate occurrence of a variable, either in inverse or uncomplemented form, is a literal. For example, if 
  
    
      
        A
      
    
    
  
, 
  
    
      
        B
      
    
    
  
 and 
  
    
      
        C
      
    
    
  
 are variables then the expression 
  
    
      
        
          
            
              A
              ¯
            
          
        
        B
        C
      
    
    
  
 contains three literals and the expression 
  
    
      
        
          
            
              A
              ¯
            
          
        
        C
        
          
            
              B
              ¯
            
          
        
        
          
            
              C
              ¯
            
          
        
      
    
    
  
 contains four literals. However, the expression 
  
    
      
        
          
            
              A
              ¯
            
          
        
        C
        
          
            
              B
              ¯
            
          
        
        C
      
    
    
  
 would also be said to contain four literals, because although two of the literals are identical (
  
    
      
        C
      
    
    
  
 appears twice) these qualify as two separate occurrences.

## Related

- [[Double turnstile]]
- [[Glossary of Principia Mathematica]]
- [[List of axiomatic systems in logic]]
- [[Predicate (logic)]]
- [[Tautology (logic)]]
- [[Turnstile (symbol)]]
- [[Absoluteness (logic)]]
- [[Abstract logic]]
- [[Abstract model theory]]
- [[Algebraic semantics (mathematical logic)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Literal_(mathematical_logic)