---
title: "Modal logic"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Modal_logic"
wikipedia_categories: ["Logic", "Mathematical logic", "Modal logic", "Philosophical logic", "Semantics"]
related: ["[[Simplification of disjunctive antecedents]]", "[[Term logic]]", "[[Game semantics]]", "[[Kripke semantics]]", "[[Proof-theoretic semantics]]", "[[Agentive logic]]", "[[Definable set]]", "[[Double turnstile]]", "[[Geometry of interaction]]", "[[Interior algebra]]"]
---

# Modal logic

Modal logic is a kind of logic used to represent statements about necessity and possibility. In philosophy and related fields
it is used as a tool for understanding concepts such as knowledge, obligation, and causation. For instance, in epistemic modal logic, the formula 
  
    
      
        ◻
        P
      
    
    
  
 can be used to represent the statement that 
  
    
      
        P
      
    
    
  
 is known. In deontic modal logic, that same formula can represent that 
  
    
      
        P
      
    
    
  
 is a moral obligation. Modal logic considers the inferences that modal statements give rise to. For instance, most epistemic modal logics treat the formula 
  
    
      
        ◻
        P
        →
        P
      
    
    
  
 as a tautology, representing the principle that only true statements can count as knowledge. However, this formula is not a tautology in deontic modal logic, since what ought to be true can be false.
Modal logics are formal systems that include unary operators such as 
  
    
      
        ◊
      
    
    
  
 and 
  
    
      
        ◻
      
    
    
  
, representing possibility and necessity respectively. For instance the modal formula 
  
    
      
        ◊
        P
      
    
    
  
 can be read as "possibly 
  
    
      
        P
      
    
    
  
" while 
  
    
      
        ◻
        P
      
    
    
  
 can be read as "necessarily 
  
    
      
        P
      
    
    
  
". In the standard relational semantics for modal logic, formulas are assigned truth values relative to a possible world. A formula's truth value at one possible world can depend on the truth values of other formulas at other accessible possible worlds. In particular, 
  
    
      
        ◊
        P
      
    
    
  
 is true at a world if 
  
    
      
        P
      
    
    
  
 is true at some accessible possible world, while 
  
    
      
        ◻
        P
      
    
    
  
 is true at a world if 
  
    
      
        P
      
    
    
  
 is true at every accessible possible world. A variety of proof systems exist which are sound and complete with respect to the semantics one gets by restricting the accessibility relation. For instance, the deontic modal logic D is sound and complete if one requires the accessibility relation to be serial.
While the intuition behind modal logic dates back to antiquity, the first modal axiomatic systems were developed by C. I. Lewis in 1912. The now-standard relational semantics emerged in the mid twentieth century from work by Arthur Prior, Jaakko Hintikka, and Saul Kripke. Recent developments include alternative topological semantics such as neighborhood semantics as well as applications of the relational semantics beyond its original philosophical motivation. Such applications include game theory, moral and legal theory, web design, multiverse-based set theory, and social epistemology.

## Related

- [[Simplification of disjunctive antecedents]]
- [[Term logic]]
- [[Game semantics]]
- [[Kripke semantics]]
- [[Proof-theoretic semantics]]
- [[Agentive logic]]
- [[Definable set]]
- [[Double turnstile]]
- [[Geometry of interaction]]
- [[Interior algebra]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Modal_logic