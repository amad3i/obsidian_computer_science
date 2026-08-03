---
title: "Association rule learning"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Association_rule_learning"
wikipedia_categories: ["Data management", "Data mining"]
related: ["[[Contrast set learning]]", "[[Abstraction (computer science)]]", "[[Action model learning]]", "[[Adamic–Adar index]]", "[[Address space]]", "[[ADO.NET]]", "[[Affinity analysis]]", "[[Agent mining]]", "[[Altitude3.Net]]", "[[AMiner (database)]]"]
---

# Association rule learning

Association rule learning is a rule-based machine learning method for discovering interesting relations between variables in large databases. It is intended to identify strong rules discovered in databases using some measures of interestingness. In any given transaction with a variety of items, association rules are meant to discover the rules that determine how or why certain items are connected.
Based on the concept of strong rules, Rakesh Agrawal, Tomasz Imieliński and Arun Swami introduced association rules for discovering regularities between products in large-scale transaction data recorded by point-of-sale (POS) systems in supermarkets. For example, the rule 
  
    
      
        
          o
          n
          i
          o
          n
          s
          ,
          p
          o
          t
          a
          t
          o
          e
          s
        
        ⇒
        
          b
          u
          r
          g
          e
          r
        
      
    
    
  
 found in the sales data of a supermarket would indicate that if a customer buys onions and potatoes together, they are likely to also buy hamburger meat. Such information can be used as the basis for decisions about marketing activities such as, e.g., promotional pricing or product placements.
In addition to the above example from market basket analysis, association rules are employed today in many application areas including Web usage mining, intrusion detection, continuous production, and bioinformatics. In contrast with sequence mining, association rule learning typically does not consider the order of items either within a transaction or across transactions.
The association rule algorithm itself consists of various parameters that can make it difficult for those without some expertise in data mining to execute, with many rules that are arduous to understand.

## Related

- [[Contrast set learning]]
- [[Abstraction (computer science)]]
- [[Action model learning]]
- [[Adamic–Adar index]]
- [[Address space]]
- [[ADO.NET]]
- [[Affinity analysis]]
- [[Agent mining]]
- [[Altitude3.Net]]
- [[AMiner (database)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Association_rule_learning