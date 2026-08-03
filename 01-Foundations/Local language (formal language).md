---
title: "Local language (formal language)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Local_language_(formal_language)"
wikipedia_categories: ["Combinatorics on words", "Formal languages", "Semigroup theory"]
related: ["[[Free monoid]]", "[[Morphic word]]", "[[Recurrent word]]", "[[Sesquipower]]", "[[Splicing language]]", "[[Unavoidable pattern]]", "[[Alphabet (formal languages)]]", "[[Autocorrelation (words)]]", "[[Compact semigroup]]", "[[Critical exponent of a word]]"]
---

# Local language (formal language)

In mathematics, a local language is a formal language for which membership of a word in the language can be determined by looking at the first and last symbol and each two-symbol substring of the word.  Equivalently, it is a language recognised by a local automaton, a particular kind of deterministic finite automaton.
Formally, a language L over an alphabet A is defined to be local if there are subsets R and S of A and a subset F of A×A such that a word w is in L if and only if the first letter of w is in R, the last letter of w is in S and no factor of length 2 in w is in F.  This corresponds to the regular expression

  
    
      
        R
        
          A
          
          
        
        ∩
        
          A
          
          
        
        S
        ∖
        
          A
          
          
        
        F
        
          A
          
          
        
         
        .
      
    
    
  

More generally, a k-testable language L is one for which membership of a word w in L depends only on the prefix and suffix of length k and the set of factors of w of length k; a language is locally testable if it is k-testable for some k.  A local language is 2-testable.

## Related

- [[Free monoid]]
- [[Morphic word]]
- [[Recurrent word]]
- [[Sesquipower]]
- [[Splicing language]]
- [[Unavoidable pattern]]
- [[Alphabet (formal languages)]]
- [[Autocorrelation (words)]]
- [[Compact semigroup]]
- [[Critical exponent of a word]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Local_language_(formal_language)