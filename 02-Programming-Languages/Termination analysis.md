---
title: "Termination analysis"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Termination_analysis"
wikipedia_categories: ["Static program analysis"]
related: ["[[Alias analysis]]", "[[Array-access analysis]]", "[[Call graph]]", "[[Code motion]]", "[[Dependence analysis]]", "[[Escape analysis]]", "[[Extended static checking]]", "[[Hoare logic]]", "[[Infer Static Analyzer]]", "[[Live-variable analysis]]"]
---

# Termination analysis

In computer science, termination analysis is program analysis which attempts to determine whether the evaluation of a given program halts for each input. This means to determine whether the input program computes a total function.
It is closely related to the halting problem, which is to determine whether a given program halts for a given input and which is undecidable. The termination analysis is even more difficult than the halting problem: the termination analysis in the model of Turing machines as the model of programs implementing computable functions would have the goal of deciding whether a given Turing machine is a total Turing machine, and this problem is at level 
  
    
      
        
          Π
          
            2
          
          
            0
          
        
      
    
    
  
 of the arithmetical hierarchy and thus is strictly more difficult than the halting problem.
Now as the question whether a computable function is total is not semi-decidable, each sound termination analyzer (i.e. an affirmative answer is never given for a non-terminating program) is incomplete, i.e. must fail in determining termination for infinitely many terminating programs, either by running forever or halting with an indefinite answer.

## Related

- [[Alias analysis]]
- [[Array-access analysis]]
- [[Call graph]]
- [[Code motion]]
- [[Dependence analysis]]
- [[Escape analysis]]
- [[Extended static checking]]
- [[Hoare logic]]
- [[Infer Static Analyzer]]
- [[Live-variable analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Termination_analysis