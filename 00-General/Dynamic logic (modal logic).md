---
title: "Dynamic logic (modal logic)"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_logic_(modal_logic)"
wikipedia_categories: ["Logic in computer science", "Modal logic", "Non-classical logic", "Program logic"]
related: ["[[Agentive logic]]", "[[Combs method]]", "[[Computability logic]]", "[[Constructive logic]]", "[[Fuzzy logic]]", "[[Hennessy–Milner logic]]", "[[Interference freedom]]", "[[Intuitionistic logic]]", "[[Kripke semantics]]", "[[Preferential entailment]]"]
---

# Dynamic logic (modal logic)

In logic, philosophy, and theoretical computer science, dynamic logic is an extension of modal logic capable of encoding properties of computer programs.
A simple example of a statement in dynamic logic is

  
    
      
        
          The ground is dry
        
        →
        
          It rains
        
        
          The ground is wet
        
        ,
      
    
    
  

which states that if the ground is currently dry and it rains, then afterwards the ground will be wet.
The syntax of dynamic logic contains a language of propositions (like "the ground is dry") and a language of actions (like "it rains"). The core modal constructs are 
  
    
      
        a
        p
      
    
    
  
, which states that after performing action a the proposition p should hold, and 
  
    
      
        ⟨
        a
        ⟩
        p
      
    
    
  
, which states that after performing action a it is possible that p holds.
The action language supports operations 
  
    
      
        a
        
          ;
        
        b
      
    
    
  
 (doing one action followed by another), 
  
    
      
        a
        ∪
        b
      
    
    
  
 (doing one action or another), and iteration 
  
    
      
        a
        
        
      
    
    
  
 (doing one action zero or more times). The proposition language supports Boolean operations (and, or, and not). The action logic is expressive enough to encode programs. For an arbitrary program 
  
    
      
        P
      
    
    
  
, precondition 
  
    
      
        φ
      
    
    
  
, and postcondition 
  
    
      
        
          φ
          ′
        
      
    
    
  
, the dynamic logic statement 
  
    
      
        φ
        →
        P
        
          φ
          ′
        
      
    
    
  
 encodes the correctness of the program, making dynamic logic more general than Hoare logic.
Beyond its use in formal verification of programs, dynamic logic has been applied to describe complex behaviors arising in linguistics, philosophy, AI, and other fields.

## Related

- [[Agentive logic]]
- [[Combs method]]
- [[Computability logic]]
- [[Constructive logic]]
- [[Fuzzy logic]]
- [[Hennessy–Milner logic]]
- [[Interference freedom]]
- [[Intuitionistic logic]]
- [[Kripke semantics]]
- [[Preferential entailment]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_logic_(modal_logic)