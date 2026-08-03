---
title: "Combination"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Combination"
wikipedia_categories: ["Combinatorics"]
related: ["[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]", "[[All-pairs testing]]", "[[Arrangement of hyperplanes]]", "[[Athanasius Kircher]]", "[[Baker–Campbell–Hausdorff formula]]"]
---

# Combination

In mathematics, a combination is a selection of items from a set that has distinct members, such that the order of selection does not matter (unlike permutations). For example, given three fruits, say an apple, an orange and a pear, there are three combinations of two that can be drawn from this set: an apple and a pear; an apple and an orange; or a pear and an orange. More formally, a k-combination of a set S is a subset of k distinct elements of S. So, two combinations are identical if and only if each combination has the same members. (The arrangement of the members in each set does not matter.) If the set has n elements, the number of k-combinations, denoted by 
  
    
      
        C
        n
        ,
        k
      
    
    
  
 or 
  
    
      
        
          C
          
            k
          
          
            n
          
        
      
    
    
  
, is equal to the binomial coefficient:

  
    
      
        
          
            
            
            
              n
              k
            
            
            
          
        
        
          
            
              n
              n
              1
              ⋯
              n
              k
              1
            
            
              k
              k
              1
              ⋯
              1
            
          
        
        ,
      
    
    
  

which using factorial notation can be compactly expressed as

  
    
      
        
          
            
            
            
              n
              k
            
            
            
          
        
        
          
            
              n
              !
            
            
              k
              !
              n
              k
              !
            
          
        
      
    
    
  

whenever 
  
    
      
        n
        ≥
        k
        ≥
        0
      
    
    
  
. This formula can be derived from the fact that each k-combination of a set S of n members has 
  
    
      
        k
        !
      
    
    
  
 permutations so 
  
    
      
        
          P
          
            k
          
          
            n
          
        
        
          C
          
            k
          
          
            n
          
        
        k
        !
      
    
    
  
 or 
  
    
      
        
          C
          
            k
          
          
            n
          
        
        
          P
          
            k
          
          
            n
          
        
        
          /
        
        k
        !
      
    
    
  
. The set of all k-combinations of a set S is often denoted by 
  
    
      
        
          
            
              
              
              
                S
                k
              
              
              
            
          
        
      
    
    
  
.
A combination is a selection of n things taken k at a time without repetition. To refer to combinations in which repetition is allowed, the terms k-combination with repetition, k-multiset, or k-selection, are often used. If, in the above example, it were possible to have two of any one kind of fruit there would be 3 more 2-selections: one with two apples, one with two oranges, and one with two pears.
Although the set of three fruits was small enough to write a complete list of combinations, this becomes impractical as the size of the set increases. For example, a poker hand can be described as a 5-combination (k = 5) of cards from a 52 card deck (n = 52). The 5 cards of the hand are all distinct, and the order of cards in the hand does not matter. There are 2,598,960 such combinations, and the chance of drawing any one hand at random is 1 / 2,598,960.

## Related

- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]
- [[All-pairs testing]]
- [[Arrangement of hyperplanes]]
- [[Athanasius Kircher]]
- [[Baker–Campbell–Hausdorff formula]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Combination