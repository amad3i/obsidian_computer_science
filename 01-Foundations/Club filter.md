---
title: "Club filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Club_filter"
wikipedia_categories: ["Set theory"]
related: ["[[Admissible set]]", "[[Almost]]", "[[Benacerraf's identification problem]]", "[[BIT predicate]]", "[[Cabal (set theory)]]", "[[Cantor's diagonal argument]]", "[[Cantor's first set theory article]]", "[[Cantor's theorem]]", "[[Cardinality of the continuum]]", "[[Categorical set theory]]"]
---

# Club filter

In mathematics, particularly in set theory, if 
  
    
      
        κ
      
    
    
  
 is a regular uncountable cardinal then 
  
    
      
        club
         
        κ
        ,
      
    
    
  
 the filter of all sets containing a club subset of 
  
    
      
        κ
        ,
      
    
    
  
 is a 
  
    
      
        κ
      
    
    
  
-complete filter closed under diagonal intersection called the club filter.
To see that this is a filter, note that 
  
    
      
        κ
        ∈
        club
         
        κ
      
    
    
  
 since it is thus both closed and unbounded (see club set). If 
  
    
      
        x
        ∈
        club
         
        κ
      
    
    
  
 then any subset of 
  
    
      
        κ
      
    
    
  
 containing 
  
    
      
        x
      
    
    
  
 is also in 
  
    
      
        club
         
        κ
        ,
      
    
    
  
 since 
  
    
      
        x
        ,
      
    
    
  
 and therefore anything containing it, contains a club set.
It is a 
  
    
      
        κ
      
    
    
  
-complete filter because the intersection of fewer than 
  
    
      
        κ
      
    
    
  
 club sets is a club set. To see this, suppose 
  
    
      
        ⟨
        
          C
          
            i
          
        
        
          ⟩
          
            i
            α
          
        
      
    
    
  
 is a sequence of club sets where 
  
    
      
        α
        κ
        .
      
    
    
  
 Obviously 
  
    
      
        C
        ⋂
        
          C
          
            i
          
        
      
    
    
  
 is closed, since any sequence which appears in 
  
    
      
        C
      
    
    
  
 appears in every 
  
    
      
        
          C
          
            i
          
        
        ,
      
    
    
  
 and therefore its limit is also in every 
  
    
      
        
          C
          
            i
          
        
        .
      
    
    
  
 To show that it is unbounded, take some 
  
    
      
        β
        κ
        .
      
    
    
  
 Let 
  
    
      
        ⟨
        
          β
          
            1
            ,
            i
          
        
        ⟩
      
    
    
  
 be an increasing sequence with 
  
    
      
        
          β
          
            1
            ,
            1
          
        
        β
      
    
    
  
 and 
  
    
      
        
          β
          
            1
            ,
            i
          
        
        ∈
        
          C
          
            i
          
        
      
    
    
  
 for every 
  
    
      
        i
        α
        .
      
    
    
  
 Such a sequence can be constructed, since every 
  
    
      
        
          C
          
            i
          
        
      
    
    
  
 is unbounded. Since 
  
    
      
        α
        κ
      
    
    
  
 and 
  
    
      
        κ
      
    
    
  
 is regular, the limit of this sequence is less than 
  
    
      
        κ
        .
      
    
    
  
 We call it 
  
    
      
        
          β
          
            2
          
        
        ,
      
    
    
  
 and define a new sequence 
  
    
      
        ⟨
        
          β
          
            2
            ,
            i
          
        
        ⟩
      
    
    
  
 similar to the previous sequence. We can repeat this process, getting a sequence of sequences 
  
    
      
        ⟨
        
          β
          
            j
            ,
            i
          
        
        ⟩
      
    
    
  
 where each element of a sequence is greater than every member of the previous sequences. Then for each 
  
    
      
        i
        α
        ,
      
    
    
  
 
  
    
      
        ⟨
        
          β
          
            j
            ,
            i
          
        
        ⟩
      
    
    
  
 is an increasing sequence contained in 
  
    
      
        
          C
          
            i
          
        
        ,
      
    
    
  
 and all these sequences have the same limit (the limit of 
  
    
      
        ⟨
        
          β
          
            j
            ,
            i
          
        
        ⟩
      
    
    
  
). This limit is then contained in every 
  
    
      
        
          C
          
            i
          
        
        ,
      
    
    
  
 and therefore 
  
    
      
        C
        ,
      
    
    
  
 and is greater than 
  
    
      
        β
        .
      
    
    
  

To see that 
  
    
      
        club
         
        κ
      
    
    
  
 is closed under diagonal intersection, let 
  
    
      
        ⟨
        
          C
          
            i
          
        
        ⟩
        ,
      
    
    
  
 
  
    
      
        i
        κ
      
    
    
  
 be a sequence of club sets, and let 
  
    
      
        C
        
          Δ
          
            i
            κ
          
        
        
          C
          
            i
          
        
        .
      
    
    
  
 To show 
  
    
      
        C
      
    
    
  
 is closed, suppose 
  
    
      
        S
        ⊆
        α
        κ
      
    
    
  
 and 
  
    
      
        ⋃
        S
        α
        .
      
    
    
  
 Then for each 
  
    
      
        γ
        ∈
        S
        ,
      
    
    
  
 
  
    
      
        γ
        ∈
        
          C
          
            β
          
        
      
    
    
  
 for all 
  
    
      
        β
        γ
        .
      
    
    
  
  Since each 
  
    
      
        
          C
          
            β
          
        
      
    
    
  
 is closed, 
  
    
      
        α
        ∈
        
          C
          
            β
          
        
      
    
    
  
 for all 
  
    
      
        β
        α
        ,
      
    
    
  
 so 
  
    
      
        α
        ∈
        C
        .
      
    
    
  
 To show 
  
    
      
        C
      
    
    
  
 is unbounded, let 
  
    
      
        α
        κ
        ,
      
    
    
  
 and define a sequence 
  
    
      
        
          ξ
          
            i
          
        
        ,
      
    
    
  
 
  
    
      
        i
        ω
      
    
    
  
 as follows: 
  
    
      
        
          ξ
          
            0
          
        
        α
        ,
      
    
    
  
 and 
  
    
      
        
          ξ
          
            i
            1
          
        
      
    
    
  
 is the minimal element of 
  
    
      
        
          ⋂
          
            γ
            
              ξ
              
                i
              
            
          
        
        
          C
          
            γ
          
        
      
    
    
  
 such that 
  
    
      
        
          ξ
          
            i
            1
          
        
        
          ξ
          
            i
          
        
        .
      
    
    
  
  Such an element exists since by the above, the intersection of 
  
    
      
        
          ξ
          
            i
          
        
      
    
    
  
 club sets is club. Then 
  
    
      
        ξ
        
          ⋃
          
            i
            ω
          
        
        
          ξ
          
            i
          
        
        α
      
    
    
  
 and 
  
    
      
        ξ
        ∈
        C
        ,
      
    
    
  
 since it is in each 
  
    
      
        
          C
          
            i
          
        
      
    
    
  
 with 
  
    
      
        i
        ξ
        .
      
    
    

*(note truncated for size; full article at the source link below)*

## Related

- [[Admissible set]]
- [[Almost]]
- [[Benacerraf's identification problem]]
- [[BIT predicate]]
- [[Cabal (set theory)]]
- [[Cantor's diagonal argument]]
- [[Cantor's first set theory article]]
- [[Cantor's theorem]]
- [[Cardinality of the continuum]]
- [[Categorical set theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Club_filter