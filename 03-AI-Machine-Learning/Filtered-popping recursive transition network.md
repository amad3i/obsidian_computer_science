---
title: "Filtered-popping recursive transition network"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Filtered-popping_recursive_transition_network"
wikipedia_categories: ["Computational linguistics", "Natural language processing"]
related: ["[[ACL Data Collection Initiative]]", "[[Adversarial stylometry]]", "[[Aggregation (linguistics)]]", "[[Arabic Ontology]]", "[[Artificial intelligence content detection]]", "[[Association for Computational Linguistics]]", "[[Automated essay scoring]]", "[[Automatic acquisition of sense-tagged corpora]]", "[[Automatic summarization]]", "[[BulSemCor]]"]
---

# Filtered-popping recursive transition network

A filtered-popping recursive transition network (FPRTN), or simply filtered-popping network (FPN), is a recursive transition network (RTN) extended with a map of states to keys where returning from a subroutine jump requires the acceptor and return states to be mapped to the same key. RTNs are finite-state machines that can be seen as finite-state automata extended with a stack of return states; as well as consuming transitions and 
  
    
      
        ε
      
    
    
  
-transitions, RTNs may define call transitions. These transitions perform a subroutine jump by pushing the transition's target state onto the stack and bringing the machine to the called state. Each time an acceptor state is reached, the return state at the top of the stack is popped out, provided that the stack is not empty, and the machine is brought to this state.
Throughout this article we refer to filtered-popping recursive transition networks as FPNs, though this acronym is ambiguous (e.g.: fuzzy Petri nets). Filtered-popping networks and FPRTNs are unambiguous alternatives.

## Related

- [[ACL Data Collection Initiative]]
- [[Adversarial stylometry]]
- [[Aggregation (linguistics)]]
- [[Arabic Ontology]]
- [[Artificial intelligence content detection]]
- [[Association for Computational Linguistics]]
- [[Automated essay scoring]]
- [[Automatic acquisition of sense-tagged corpora]]
- [[Automatic summarization]]
- [[BulSemCor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Filtered-popping_recursive_transition_network