---
title: "Predicative programming"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Predicative_programming"
wikipedia_categories: ["Formal methods", "Formal methods stubs", "Formal specification languages", "Logical calculi"]
related: ["[[Refinement calculus]]", "[[Algebraic semantics (computer science)]]", "[[Axiomatic semantics]]", "[[B-Method]]", "[[Formal specification]]", "[[Language of Temporal Ordering Specification]]", "[[PlusCal]]", "[[ProCoS]]", "[[Semantics (programming languages)]]", "[[TLA+]]"]
---

# Predicative programming

Predicative programming is the original name of a formal method for program specification and refinement, more recently called a Practical Theory of Programming, invented by Eric Hehner. The central idea is that each specification is a binary (boolean) expression that is true of acceptable computer behaviors and false of unacceptable behaviors. It follows that refinement is just implication. This is the simplest formal method, and the most general, applying to sequential, parallel, stand-alone, communicating, terminating, nonterminating, natural-time, real-time, deterministic, and probabilistic programs, and includes time and space bounds.
Commands in a programming language are considered to be a special case of specification—those specifications that are compilable. For example, if the program variables are 
  
    
      
        x
      
    
    
  
, 
  
    
      
        y
      
    
    
  
, and 
  
    
      
        z
      
    
    
  
, the command 
  
    
      
        x
      
    
    
  
:= 
  
    
      
        y
      
    
    
  
+1 is equivalent to the specification (binary expression) 
  
    
      
        
          x
          ′
        
      
    
    
  
  
    
      
        y
      
    
    
  
+1 ∧ 
  
    
      
        
          y
          ′
        
      
    
    
  
  
    
      
        y
      
    
    
  
 ∧ 
  
    
      
        
          z
          ′
        
      
    
    
  
  
    
      
        z
      
    
    
  
 in which 
  
    
      
        x
      
    
    
  
, 
  
    
      
        y
      
    
    
  
, and 
  
    
      
        z
      
    
    
  
 represent the values of the program variables before the assignment, and  
  
    
      
        
          x
          ′
        
      
    
    
  
, 
  
    
      
        
          y
          ′
        
      
    
    
  
, and 
  
    
      
        
          z
          ′
        
      
    
    
  
 represent the values of the program variables after the assignment. If the specification is 
  
    
      
        
          x
          ′
        
      
    
    
  
  
    
      
        y
      
    
    
  
, we easily prove (
  
    
      
        x
      
    
    
  
:= 
  
    
      
        y
      
    
    
  
+1) ⇒ (
  
    
      
        
          x
          ′
        
      
    
    
  
  
    
      
        y
      
    
    
  
), which says that 
  
    
      
        x
      
    
    
  
:= 
  
    
      
        y
      
    
    
  
+1 implies, or refines, or implements 
  
    
      
        
          x
          ′
        
      
    
    
  
  
    
      
        y
      
    
    
  
.
Loop proofs are greatly simplified. For example, if 
  
    
      
        x
      
    
    
  
 is an integer variable, to prove that
	while 
  
    
      
        x
      
    
    
  
>0 do 
  
    
      
        x
      
    
    
  
:= 
  
    
      
        x
      
    
    
  
–1 od
refines, or implements the specification 
  
    
      
        x
      
    
    
  
≥0 ⇒ 
  
    
      
        
          x
          ′
        
      
    
    
  
=0, prove
	if 
  
    
      
        x
      
    
    
  
>0 then 
  
    
      
        x
      
    
    
  
:= 
  
    
      
        x
      
    
    
  
–1; (
  
    
      
        x
      
    
    
  
≥0 ⇒ 
  
    
      
        
          x
          ′
        
      
    
    
  
=0) else 
  
    
      
        o
        k
      
    
    
  
 fi  ⇒  (
  
    
      
        x
      
    
    
  
≥0 ⇒ 
  
    
      
        
          x
          ′
        
      
    
    
  
=0)
where  
  
    
      
        o
        k
      
    
    
  
  =  (
  
    
      
        
          x
          ′
        
      
    
    
  
  
    
      
        x
      
    
    
  
) is the empty, or do-nothing command. There is no need for a loop invariant or least fixed point. Loops with multiple intermediate shallow and deep exits work the same way. This simplified form of proof is possible because program commands and specifications can be mixed together meaningfully.
Execution time (upper bounds, lower bounds, exact time) can be proven the same way, just by introducing a time variable. To prove termination, prove the execution time is finite. To prove nontermination, prove the execution time is infinite. For example, if the time variable is 
  
    
      
        t
      
    
    
  
, and time is measured by counting iterations, then to prove that execution of the previous while-loop takes time 
  
    
      
        x
      
    
    
  
 when 
  
    
      
        x
      
    
    
  
 is initially nonnegative, and takes forever when 
  
    
      
        x
      
    
    
  
 is initially negative, prove
	     if 
  
    
      
        x
      
    
    
  
>0 then 
  
    
      
        x
      
    
    
  
:= 
  
    
      
        x
      
    
    
  
–1; 
  
    
      
        t
      
    
    
  
:= 
  
    
      
        t
      
    
    
  
+1; (
  
    
      
        x
      
    
    
  
≥0 ⇒ 
  
    
      
        
          t
          ′
        
      
    
    
  
  
    
      
        t
      
    
    
  
  
    
      
        x
      
    
    
  
) ∧ (
  
    
      
        x
      
    
    
  
<0 ⇒ 
  
    
      
        
          t
          ′
        
      
    
    
  
=∞) else 
  
    
      
        o
        k
      
    
    
  
 fi
	⇒  (
  
    
      
        x
      
    
    
  
≥0 ⇒ 
  
    
      
        
          t
          ′
        
      
    
    
  
  
    
      
        t
      
    
    
  
  
    
      
        x
      
    
    
  
) ∧ (
  
    
      
        x
      
    
    
  
<0 ⇒ 
  
    
      
        
          t
          ′
        
      
    
    
  
=∞)
where 
  
    
      
        o
        k
      
    
    
  
   =   (
  
    
      
        
          x
          ′
        
      
    
    
  
  
    
      
        x
      
    
    
  
 ∧ 
  
    
      
        
          t
          ′
        
      
    
    
  
  
    
      
        t
      
    
    
  
).

## Related

- [[Refinement calculus]]
- [[Algebraic semantics (computer science)]]
- [[Axiomatic semantics]]
- [[B-Method]]
- [[Formal specification]]
- [[Language of Temporal Ordering Specification]]
- [[PlusCal]]
- [[ProCoS]]
- [[Semantics (programming languages)]]
- [[TLA+]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Predicative_programming