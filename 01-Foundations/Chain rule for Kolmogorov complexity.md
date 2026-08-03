---
title: "Chain rule for Kolmogorov complexity"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Chain_rule_for_Kolmogorov_complexity"
wikipedia_categories: ["Algorithmic information theory", "Computability theory", "Information theory", "Theory of computation"]
related: ["[[Kolmogorov complexity]]", "[[Ackermann function]]", "[[Admissible numbering]]", "[[Algorithmic information theory]]", "[[Busy beaver]]", "[[Chaitin's constant]]", "[[Church–Turing thesis]]", "[[Church–Turing–Deutsch principle]]", "[[Computability]]", "[[Computable function]]"]
---

# Chain rule for Kolmogorov complexity

The chain rule for Kolmogorov complexity is an analogue of the chain rule for information entropy, which states:

  
    
      
        H
        X
        ,
        Y
        =
        H
        X
        +
        H
        Y
        
          |
        
        X
      
    
    
  

That is, the combined randomness of two sequences X and Y is the sum of the randomness of X plus whatever randomness is left in Y once we know X.
This follows immediately from the definitions of conditional and joint entropy, and the fact from probability theory that the joint probability is the product of the marginal and conditional probability:

  
    
      
        P
        X
        ,
        Y
        =
        P
        X
        P
        Y
        
          |
        
        X
      
    
    
  

  
    
      
        ⇒
         
        P
        X
        ,
        Y
        =
         
        P
        X
        +
         
        P
        Y
        
          |
        
        X
      
    
    
  

The equivalent statement for Kolmogorov complexity does not hold exactly; it is true only up to a logarithmic term:

  
    
      
        K
        x
        ,
        y
        =
        K
        x
        +
        K
        y
        
          |
        
        x
        +
        O
        log
         
        K
        x
        ,
        y
        )
      
    
    
  

(An exact version, KP(x, y) = KP(x) + KP(y|x∗) + O(1),
holds for the prefix complexity KP, where x∗ is a shortest program for x.)
It states that the shortest program printing X and Y is obtained by concatenating a shortest program printing X with a program printing Y given X, plus at most a logarithmic factor. The results implies that  algorithmic mutual information, an analogue of mutual information for Kolmogorov complexity is symmetric: ⁠
  
    
      
        I
        x
        :
        y
        =
        I
        y
        :
        x
        +
        O
        log
         
        K
        x
        ,
        y
        )
      
    
    
  
⁠ for all x,y.

## Related

- [[Kolmogorov complexity]]
- [[Ackermann function]]
- [[Admissible numbering]]
- [[Algorithmic information theory]]
- [[Busy beaver]]
- [[Chaitin's constant]]
- [[Church–Turing thesis]]
- [[Church–Turing–Deutsch principle]]
- [[Computability]]
- [[Computable function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Chain_rule_for_Kolmogorov_complexity