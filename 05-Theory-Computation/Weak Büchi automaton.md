---
title: "Weak Büchi automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Weak_Büchi_automaton"
wikipedia_categories: ["Automata (computation)", "Infinite words"]
related: ["[[Abstract machine]]", "[[Alternating timed automaton]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]", "[[Automatic sequence]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[Boolean differential calculus]]", "[[Büchi automaton]]"]
---

# Weak Büchi automaton

In computer science and automata theory, a Weak Büchi automaton is a formalism which represents a set of infinite words. A Weak Büchi automaton is a modification of Büchi automaton such that for all pair of states 
  
    
      
        q
      
    
    
  
 and 
  
    
      
        
          q
          ′
        
      
    
    
  
 belonging to the same strongly connected component,  
  
    
      
        q
      
    
    
  
 is accepting  if and only if 
  
    
      
        
          q
          ′
        
      
    
    
  
 is accepting.
A Büchi automaton accepts a word 
  
    
      
        w
      
    
    
  
 if there exists a run, such that at least one state occurring infinitely often in the final state set 
  
    
      
        F
      
    
    
  
. For Weak Büchi automata, this condition is equivalent to the existence of a run which ultimately stays in the set of accepting states.
Weak Büchi automata are strictly less-expressive than Büchi automata and than Co-Büchi automata.

## Related

- [[Abstract machine]]
- [[Alternating timed automaton]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Augmented transition network]]
- [[Automata theory]]
- [[Automatic sequence]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[Boolean differential calculus]]
- [[Büchi automaton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Weak_Büchi_automaton