---
title: "♯SAT"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/♯SAT"
wikipedia_categories: ["Combinatorics", "Computational problems", "Satisfiability problems"]
related: ["[[Josephus problem]]", "[[♯P-completeness of 01-permanent]]", "[[1-in-3-SAT]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[AI-complete]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]"]
---

# ♯SAT

In computer science, the Sharp Satisfiability Problem (sometimes called Sharp-SAT, #SAT or model counting) is the problem of counting the number of interpretations that satisfy a given Boolean formula, introduced by Valiant in 1979. In other words, it asks in how many ways the variables of a given Boolean formula can be consistently replaced by the values TRUE or FALSE in such a way that the formula evaluates to TRUE. For example, the formula 
  
    
      
        a
        ∨
        ¬
        b
      
    
    
  
 is satisfiable by three distinct boolean value assignments of the variables, namely, for any of the assignments (
  
    
      
        a
      
    
    
  
 = TRUE,  
  
    
      
        b
      
    
    
  
 = FALSE), (
  
    
      
        a
      
    
    
  
 = FALSE, 
  
    
      
        b
      
    
    
  
 = FALSE), and (
  
    
      
        a
      
    
    
  
 = TRUE, 
  
    
      
        b
      
    
    
  
 = TRUE), we have 
  
    
      
        a
        ∨
        ¬
        b
        
          
            TRUE
          
        
        .
      
    
    
  

#SAT is different from Boolean satisfiability problem (SAT), which asks if there exists a solution to a Boolean formula. Instead, #SAT asks to enumerate all the solutions to a Boolean formula. #SAT is harder than SAT in the sense that, once the total number of solutions to a Boolean formula is known, SAT can be decided in constant time. However, the converse is not true, because knowing a Boolean formula has a solution does not help us to count all the solutions, as there are an exponential number of possibilities.
#SAT is a well-known example of the class of counting problems, known as #P-complete (read as sharp P complete). In other words, every instance of a problem in the complexity class #P can be reduced to an instance of the #SAT problem. This is an important result because many difficult counting problems arise in Enumerative Combinatorics, Statistical physics, Network Reliability, and Artificial intelligence without any known formula. If a problem is shown to be hard, then it provides a complexity theoretic explanation for the lack of nice looking formulas.

## Related

- [[Josephus problem]]
- [[♯P-completeness of 01-permanent]]
- [[1-in-3-SAT]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[AI-complete]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/♯SAT