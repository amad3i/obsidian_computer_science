---
title: "Time-inhomogeneous hidden Bernoulli model"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Time-inhomogeneous_hidden_Bernoulli_model"
wikipedia_categories: ["Hidden stochastic models", "Speech recognition"]
related: ["[[ACL Data Collection Initiative]]", "[[Acoustic model]]", "[[Apptek]]", "[[Articulatory speech recognition]]", "[[Artificial intelligence content detection]]", "[[Audio mining]]", "[[Audio-visual speech recognition]]", "[[Automated Lip Reading]]", "[[Buckeye Corpus]]", "[[Cache language model]]"]
---

# Time-inhomogeneous hidden Bernoulli model

Time-inhomogeneous hidden Bernoulli model (TI-HBM) is an alternative to hidden Markov model (HMM) for automatic speech recognition. Contrary to HMM, the state transition process in TI-HBM is not a Markov-dependent process, rather it is a generalized Bernoulli (an independent) process. This difference leads to elimination of dynamic programming at state-level in TI-HBM decoding process. Thus, the computational complexity of TI-HBM for probability evaluation and state estimation is 
  
    
      
        O
        N
        L
      
    
    
  
 (instead of 
  
    
      
        O
        
          N
          
            2
          
        
        L
      
    
    
  
 in the HMM case, where 
  
    
      
        N
      
    
    
  
 and 
  
    
      
        L
      
    
    
  
 are number of states and observation sequence length respectively). The TI-HBM is able to model acoustic-unit duration (e.g. phone/word duration) by using a built-in parameter named survival probability. The TI-HBM is simpler and faster than HMM in a phoneme recognition task, but its performance is comparable to HMM.
For details, see  or .

## Related

- [[ACL Data Collection Initiative]]
- [[Acoustic model]]
- [[Apptek]]
- [[Articulatory speech recognition]]
- [[Artificial intelligence content detection]]
- [[Audio mining]]
- [[Audio-visual speech recognition]]
- [[Automated Lip Reading]]
- [[Buckeye Corpus]]
- [[Cache language model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Time-inhomogeneous_hidden_Bernoulli_model