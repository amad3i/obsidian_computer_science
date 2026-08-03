---
title: "Fluent (artificial intelligence)"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Fluent_(artificial_intelligence)"
wikipedia_categories: ["Logic in computer science"]
related: ["[[1-in-3-SAT]]", "[[Abstract rewriting system]]", "[[ACM Transactions on Computational Logic]]", "[[Agent verification]]", "[[Agentive logic]]", "[[Algebraic semantics (computer science)]]", "[[Alternating-time temporal logic]]", "[[Assertion (software development)]]", "[[Automated reasoning]]", "[[Axiomatic semantics]]"]
---

# Fluent (artificial intelligence)

In artificial intelligence, a fluent is a condition that can change over time. In logical approaches to reasoning about actions, fluents can be represented in first-order logic by predicates having an argument that depends on time. For example, the condition "the box is on the table", if it can change over time, cannot be represented by 
  
    
      
        
          O
          n
        
        
          b
          o
          x
        
        ,
        
          t
          a
          b
          l
          e
        
      
    
    
  
; a third argument is necessary to the predicate 
  
    
      
        
          O
          n
        
      
    
    
  
 to specify the time: 
  
    
      
        
          O
          n
        
        
          b
          o
          x
        
        ,
        
          t
          a
          b
          l
          e
        
        ,
        t
      
    
    
  
 means that the box is on the table at time 
  
    
      
        t
      
    
    
  
. This representation of fluents is modified in the situation calculus by using the sequence of the past actions in place of the current time.
A fluent can also be represented by a function, dropping the time argument.  For example, that the box is on the table can be represented by 
  
    
      
        o
        n
        b
        o
        x
        ,
        t
        a
        b
        l
        e
      
    
    
  
, where 
  
    
      
        o
        n
      
    
    
  
 is a function and not a predicate. In first-order logic, converting predicates to functions is called reification; for this reason, fluents represented by functions are said to be reified. When using reified fluents, a separate predicate is necessary to tell when a fluent is actually true or not. For example, 
  
    
      
        H
        o
        l
        d
        s
        A
        t
        o
        n
        b
        o
        x
        ,
        t
        a
        b
        l
        e
        ,
        t
      
    
    
  
 means that the box is actually on the table at time 
  
    
      
        t
      
    
    
  
, where the predicate 
  
    
      
        H
        o
        l
        d
        s
        A
        t
      
    
    
  
 is the one that tells when fluents are true. This representation of fluents is used in the event calculus, in the fluent calculus, and in the features and fluents logics.
Some fluents can be represented as functions in a different way. For example, the position of a box can be represented by a function 
  
    
      
        o
        n
        b
        o
        x
        ,
        t
      
    
    
  
 whose value is the object the box is standing on at time 
  
    
      
        t
      
    
    
  
. Conditions that can be represented in this way are called functional fluents. Statements about the values of such functions can be given in first-order logic with equality using literals such as 
  
    
      
        o
        n
        b
        o
        x
        ,
        t
        =
        t
        a
        b
        l
        e
      
    
    
  
. Some fluents are represented this way in the situation calculus.

## Related

- [[1-in-3-SAT]]
- [[Abstract rewriting system]]
- [[ACM Transactions on Computational Logic]]
- [[Agent verification]]
- [[Agentive logic]]
- [[Algebraic semantics (computer science)]]
- [[Alternating-time temporal logic]]
- [[Assertion (software development)]]
- [[Automated reasoning]]
- [[Axiomatic semantics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fluent_(artificial_intelligence)