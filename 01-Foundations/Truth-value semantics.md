---
title: "Truth-value semantics"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Truth-value_semantics"
wikipedia_categories: ["Mathematical logic", "Semantics"]
related: ["[[Double turnstile]]", "[[Game semantics]]", "[[Modal logic]]", "[[Proof-theoretic semantics]]", "[[Semantic theory of truth]]", "[[Semantics (logic)]]", "[[Simplification of disjunctive antecedents]]", "[[Situation theory]]", "[[Tautology (logic)]]", "[[Term logic]]"]
---

# Truth-value semantics

In formal semantics, truth-value semantics is an alternative to Tarskian semantics. It has been primarily championed by Ruth Barcan Marcus, H. Leblanc, and J. Michael Dunn and Nuel Belnap. It is also called the substitution interpretation (of the quantifiers) or substitutional quantification.
The idea of these semantics is that a universal (respectively, existential) quantifier may be read as a conjunction (respectively, disjunction) of formulas in which constants replace the variables in the scope of the quantifier. For example, 
  
    
      
        ∀
        x
        P
        x
      
    
    
  
 may be read (
  
    
      
        P
        a
        ∧
        P
        b
        ∧
        P
        c
        ∧
        …
      
    
    
  
) where 
  
    
      
        a
        ,
        b
        ,
        c
      
    
    
  
 are individual constants replacing all occurrences of 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        P
        x
      
    
    
  
.
The main difference between truth-value semantics and the standard semantics for predicate logic is that there are no domains for truth-value semantics. Only the truth clauses for atomic and for quantificational formulas differ from those of the standard semantics. Whereas in standard semantics atomic formulas like 
  
    
      
        P
        b
      
    
    
  
 or 
  
    
      
        R
        c
        a
      
    
    
  
 are true if and only if (the referent of) 
  
    
      
        b
      
    
    
  
 is a member of the extension of the predicate 
  
    
      
        P
      
    
    
  
, respectively, if and only if the pair 
  
    
      
        c
        ,
        a
      
    
    
  
 is a member of the extension of 
  
    
      
        R
      
    
    
  
, in truth-value semantics the truth-values of atomic formulas are basic. A universal (existential) formula is true if and only if all (some) ground substitution instances of the unquantified subformula are true. Compare this with the standard semantics, which says that a universal (existential) formula is true if and only if for all (some) members of the domain, the formula holds for all (some) of them; for example, 
  
    
      
        ∀
        x
        A
      
    
    
  
 is true (under an interpretation) if and only if for all 
  
    
      
        k
      
    
    
  
 in the domain 
  
    
      
        D
      
    
    
  
, 
  
    
      
        A
        k
        
          /
        
        x
      
    
    
  
 is true (where 
  
    
      
        A
        k
        
          /
        
        x
      
    
    
  
 is the result of substituting 
  
    
      
        k
      
    
    
  
 for all occurrences of 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        A
      
    
    
  
). (Here we are assuming that constants are names for themselves—i.e. they are also members of the domain.)
Truth-value semantics is not without its problems. First, the strong completeness theorem and compactness fail. To see this consider the set 
  
    
      
        F
        1
        ,
        F
        2
        ,
        …
      
    
    
  
. Clearly the formula 
  
    
      
        ∀
        x
        F
        x
      
    
    
  
 is a logical consequence of the set, but it is not a consequence of any finite subset of it (and hence it is not deducible from it). It follows immediately that both compactness and the strong completeness theorem fail for truth-value semantics. This is rectified by a modified definition of logical consequence as given in Dunn and Belnap 1968.
Another problem occurs in free logic. Consider a language with one individual constant 
  
    
      
        c
      
    
    
  
 that is nondesignating and a predicate 
  
    
      
        F
      
    
    
  
 standing for 'does not exist'. Then 
  
    
      
        ∃
        x
        F
        x
      
    
    
  
 is false even though a substitution instance (in fact every such instance under this interpretation) of it is true. To solve this problem we simply add the proviso that an existentially quantified statement is true under an interpretation for at least one substitution instance in which the constant designates something that exists.

## Related

- [[Double turnstile]]
- [[Game semantics]]
- [[Modal logic]]
- [[Proof-theoretic semantics]]
- [[Semantic theory of truth]]
- [[Semantics (logic)]]
- [[Simplification of disjunctive antecedents]]
- [[Situation theory]]
- [[Tautology (logic)]]
- [[Term logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Truth-value_semantics