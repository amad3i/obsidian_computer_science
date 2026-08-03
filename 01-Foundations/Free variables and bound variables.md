---
title: "Free variables and bound variables"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Free_variables_and_bound_variables"
wikipedia_categories: ["Computer programming", "Logic symbols", "Mathematical notation", "Predicate logic"]
related: ["[[Glossary of Principia Mathematica]]", "[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Big O in probability notation]]", "[[Big O notation]]", "[[Boolean flag]]", "[[Bra–ket notation]]", "[[Breakpoint]]"]
---

# Free variables and bound variables

In mathematics, and in other disciplines involving formal languages, including mathematical logic and computer science, a variable may be said to be either free or bound. Some older books use the terms real variable and apparent variable for free variable and bound variable, respectively. A free variable is a notation (symbol) that specifies places in an expression where substitution may take place and is not a parameter of this or any container expression. The idea is related to a placeholder (a symbol that will later be replaced by some value), or a wildcard character that stands for an unspecified symbol.
In computer programming, the term free variable refers to variables used in a function that are neither local variables nor parameters of that function. The term non-local variable is often a synonym in this context.
An instance of a variable symbol is bound, in contrast, if the value of that variable symbol has been bound to a specific value or range of values in the domain of discourse or universe. This may be achieved through the use of  logical quantifiers, variable-binding operators, or an explicit statement of allowed values for the variable (such as, "...where 
  
    
      
        n
      
    
    
  
 is a positive integer".) 
Since the same variable symbol may appear in multiple places in an expression, some occurrences of the variable symbol may be free while others are bound, hence "free" and "bound" are at first defined for occurrences and then generalized over all occurrences of said variable symbol in the expression.
A variable symbol overall is free if at least one occurrence of it is free.
While the domain of discourse in many contexts is understood, when an explicit range of values for the bound variable has not been given, it may be necessary to specify the domain in order to properly evaluate the expression. For example, consider the following expression in which both variables are bound by logical quantifiers:

  
    
      
        ∀
        y
        
        ∃
        x
        
        
          
            x
            
              
                y
              
            
          
        
      
    
    
  

This expression evaluates to false if the domain of 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
 is the real numbers, but true if the domain is the complex numbers.
The term "dummy variable" is also sometimes used for a bound variable (more commonly in general mathematics than in computer science), but this should not be confused with the identically named but unrelated concept of dummy variable as used in statistics, most commonly in regression analysis.p.17

## Related

- [[Glossary of Principia Mathematica]]
- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Big O in probability notation]]
- [[Big O notation]]
- [[Boolean flag]]
- [[Bra–ket notation]]
- [[Breakpoint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Free_variables_and_bound_variables