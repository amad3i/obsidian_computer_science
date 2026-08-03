---
title: "Quantum coin flipping"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Quantum_coin_flipping"
wikipedia_categories: ["Information theory", "Quantum cryptography"]
related: ["[[Glossary of quantum computing]]", "[[Quantum capacity]]", "[[Quantum computing]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]"]
---

# Quantum coin flipping

Consider two remote players, connected by a channel, that don't trust each other. The problem of them agreeing on a random bit by exchanging messages over this channel, without relying on any trusted third party, is called the coin flipping problem in cryptography. Quantum coin flipping uses the principles of quantum mechanics to encrypt messages for secure communication. It is a cryptographic primitive which can be used to construct more complex and useful cryptographic protocols, e.g. Quantum Byzantine agreement.
Unlike other types of quantum cryptography (in particular, quantum key distribution), quantum coin flipping is a protocol used between two users who do not trust each other. Consequently, both users (or players) want to win the coin toss and will attempt to cheat in various ways.
In the classical setting, i.e. without quantum communication, one player can (in principle) always cheat against any protocol. There are classical protocols based on commitment schemes, but they assume that the players lack the computing power to break the scheme. In contrast,  quantum coin flipping protocols can resist cheating even by players with unlimited computing power.
The most basic figure of merit for a coin-flipping protocol is given by its bias, a number between 
  
    
      
        0
      
    
    
  
 and 
  
    
      
        1
        
          /
        
        2
      
    
    
  
. The bias of a protocol captures the success probability of an all-powerful cheating player who uses the best conceivable strategy. A protocol with bias 
  
    
      
        0
      
    
    
  
 means that no player can cheat. A protocol with bias 
  
    
      
        1
        
          /
        
        2
      
    
    
  
 means that at least one player can always succeed at cheating. Obviously, the smaller the bias, the better the protocol.
When the communication is over a quantum channel, it has been shown that even the best conceivable protocol can not have a bias less than 
  
    
      
        1
        
          /
        
        
          
            2
          
        
        1
        
          /
        
        2
        ≈
        0.2071
      
    
    
  
.
Consider the case where each player knows the preferred bit of the other. A coin flipping problem which makes this additional assumption constitutes the weaker variant thereof called weak coin flipping (WCF). In the case of classical channels this extra assumption yields no improvement.  On the other hand, it has  been proven that WCF protocols with arbitrarily small biases do exist. However, the best known explicit WCF protocol has bias 
  
    
      
        1
        
          /
        
        6
        ≈
        0.1667
      
    
    
  
.
Although quantum coin flipping offers clear advantages over its classical counterpart in theory, accomplishing it in practice has proven difficult.

## Related

- [[Glossary of quantum computing]]
- [[Quantum capacity]]
- [[Quantum computing]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_coin_flipping