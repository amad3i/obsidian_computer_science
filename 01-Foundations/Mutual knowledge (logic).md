---
title: "Mutual knowledge (logic)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Mutual_knowledge_(logic)"
wikipedia_categories: ["Concepts in epistemology", "Epistemic logic", "Game theory"]
related: ["[[Common knowledge (logic)]]", "[[Rational ignorance]]", "[[Ambiguity aversion]]", "[[Analytic narrative]]", "[[Asynchrony (game theory)]]", "[[Aumann's agreement theorem]]", "[[Authority distribution]]", "[[Autoepistemic logic]]", "[[Backward induction]]", "[[Banzhaf power index]]"]
---

# Mutual knowledge (logic)

Mutual knowledge is a fundamental concept about information in game theory, (epistemic) logic, and epistemology.  An event is mutual knowledge if all agents know that the event occurred. However, mutual knowledge by itself implies nothing about what agents know about other agents' knowledge: i.e. it is possible that an event is mutual knowledge but that each agent is unaware that the other agents know it has occurred. Common knowledge is a related but stronger notion; any event that is common knowledge is also mutual knowledge.
The philosopher Stephen Schiffer, in his book Meaning, developed a notion he called "mutual knowledge" which functions quite similarly to David K. Lewis's "common knowledge".
Communications (verbal or non-verbal) can turn mutual knowledge into common knowledge. For example, in the Muddy Children Puzzle with two children (Alice and Bob, 
  
    
      
        G
        {
        a
        ,
        b
      
    
    
  
), if they both have muddy face (viz. 
  
    
      
        
          M
          
            a
          
        
        ∧
        
          M
          
            b
          
        
      
    
    
  
), both of them know that there is at least one muddy face. Written formally, let 
  
    
      
        p
        [
        ∃
        x
        
        ∈
        
        G
        
          M
          
            x
          
        
        ]
      
    
    
  
, and then we have 
  
    
      
        
          K
          
            a
          
        
        p
        ∧
        
          K
          
            b
          
        
        p
      
    
    
  
. However, neither of them know that the other child knows (
  
    
      
        ¬
        
          K
          
            a
          
        
        
          K
          
            b
          
        
        p
        ∧
        ¬
        
          K
          
            b
          
        
        
          K
          
            a
          
        
        p
      
    
    
  
), which makes 
  
    
      
        p
        [
        ∃
        x
        
        ∈
        
        G
        
          M
          
            x
          
        
        ]
      
    
    
  
 mutual knowledge. Now suppose if Alice tells Bob that she knows 
  
    
      
        p
      
    
    
  
 (so that 
  
    
      
        
          K
          
            a
          
        
        p
      
    
    
  
 becomes common knowledge, i.e. 
  
    
      
        
          C
          
            G
          
        
        
          K
          
            a
          
        
        p
      
    
    
  
), and then Bob tells Alice that he knows 
  
    
      
        p
      
    
    
  
 as well (so that 
  
    
      
        
          K
          
            b
          
        
        p
      
    
    
  
 becomes common knowledge, i.e. 
  
    
      
        
          C
          
            G
          
        
        
          K
          
            b
          
        
        p
      
    
    
  
), this will turn 
  
    
      
        p
      
    
    
  
 into common knowledge (
  
    
      
        
          C
          
            G
          
        
        
          E
          
            G
          
        
        p
        ⇒
        
          C
          
            G
          
        
        p
      
    
    
  
), which is equivalent to the effect of a public announcement "there is at least one muddy face".

## Related

- [[Common knowledge (logic)]]
- [[Rational ignorance]]
- [[Ambiguity aversion]]
- [[Analytic narrative]]
- [[Asynchrony (game theory)]]
- [[Aumann's agreement theorem]]
- [[Authority distribution]]
- [[Autoepistemic logic]]
- [[Backward induction]]
- [[Banzhaf power index]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mutual_knowledge_(logic)