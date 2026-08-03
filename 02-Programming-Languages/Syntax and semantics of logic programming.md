---
title: "Syntax and semantics of logic programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Syntax_and_semantics_of_logic_programming"
wikipedia_categories: ["Logic programming", "Programming language syntax"]
related: ["[[Abductive logic programming]]", "[[Advice taker]]", "[[Answer set programming]]", "[[Artificial intelligence in fraud detection]]", "[[Autoepistemic logic]]", "[[Belief revision]]", "[[BNR Prolog]]", "[[Circumscription (logic)]]", "[[Clause (logic)]]", "[[Closed-world assumption]]"]
---

# Syntax and semantics of logic programming

Logic programming is a programming paradigm that includes languages based on formal logic, including Datalog and Prolog. This article describes the syntax and semantics of the purely declarative subset of these languages. Confusingly, the name "logic programming" also refers to a specific programming language that roughly corresponds to the declarative subset of Prolog. Unfortunately, the term must be used in both senses in this article.
Declarative logic programs consist entirely of rules of the form

Each such rule can be read as an implication:

  
    
      
        
          B
          
            1
          
        
        ∧
        …
        ∧
        
          B
          
            n
          
        
        →
        H
      
    
    
  

meaning "If each 
  
    
      
        
          B
          
            i
          
        
      
    
    
  
 is true, then 
  
    
      
        H
      
    
    
  
 is true". Logic programs compute the set of facts that are implied by their rules.
Many implementations of Datalog, Prolog, and related languages add procedural features such as Prolog's cut operator or extra-logical features such as a foreign function interface. The formal semantics of such extensions are beyond the scope of this article.

## Related

- [[Abductive logic programming]]
- [[Advice taker]]
- [[Answer set programming]]
- [[Artificial intelligence in fraud detection]]
- [[Autoepistemic logic]]
- [[Belief revision]]
- [[BNR Prolog]]
- [[Circumscription (logic)]]
- [[Clause (logic)]]
- [[Closed-world assumption]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Syntax_and_semantics_of_logic_programming