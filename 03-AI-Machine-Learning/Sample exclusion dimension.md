---
title: "Sample exclusion dimension"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Sample_exclusion_dimension"
wikipedia_categories: ["Computational learning theory", "Machine learning stubs", "Theoretical computer science stubs"]
related: ["[[Teaching dimension]]", "[[Unique negative dimension]]", "[[Witness set]]", "[[Algorithmic learning theory]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Archetypal analysis]]", "[[Astrostatistics]]", "[[Bayesian learning mechanisms]]", "[[Bondy's theorem]]", "[[Bridging model]]"]
---

# Sample exclusion dimension

In computational learning theory, sample exclusion dimensions arise in the study of exact concept learning with queries.  
In algorithmic learning theory, a concept over a domain X is a Boolean function over X. Here we only consider finite domains. A partial approximation S of a concept c is a Boolean function over 
  
    
      
        Y
        ⊆
        X
      
    
    
  
 such that c is an extension to S.
Let C be a class of concepts and c be a concept (not necessarily in C). Then a specifying set for c w.r.t. C, denoted by S is a partial approximation S of c such that C contains at most one extension to S. If we have observed a specifying set for some concept w.r.t. C, then we have enough information to verify a concept in C with at most one more mind change.
The exclusion dimension, denoted by XD(C), of a concept class is the maximum of the size of the minimum specifying set of c' with respect to C, where c' is a concept not in C.

## Related

- [[Teaching dimension]]
- [[Unique negative dimension]]
- [[Witness set]]
- [[Algorithmic learning theory]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Archetypal analysis]]
- [[Astrostatistics]]
- [[Bayesian learning mechanisms]]
- [[Bondy's theorem]]
- [[Bridging model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sample_exclusion_dimension