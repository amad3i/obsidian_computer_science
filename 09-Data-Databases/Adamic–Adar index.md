---
title: "Adamic–Adar index"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Adamic–Adar_index"
wikipedia_categories: ["Data mining", "Index numbers", "Metric geometry stubs", "Similarity measures"]
related: ["[[Jaccard index]]", "[[Simple matching coefficient]]", "[[Action model learning]]", "[[Affinity analysis]]", "[[Agent mining]]", "[[AMiner (database)]]", "[[Anomaly detection]]", "[[Archetypal analysis]]", "[[Argument mining]]", "[[Association rule learning]]"]
---

# Adamic–Adar index

The Adamic–Adar index is a measure introduced in 2003 by Lada Adamic and Eytan Adar to predict links in a social network, according to the amount of shared links between two nodes. It is defined as the sum of the inverse logarithmic degree centrality of the neighbours shared by the two nodes

  
    
      
        A
        x
        ,
        y
        =
        
          ∑
          
            u
            ∈
            N
            x
            ∩
            N
            y
          
        
        
          
            1
            
               
              
                
                  |
                
                N
                u
                
                  |
                
              
            
          
        
      
    
    
  

where 
  
    
      
        N
        u
      
    
    
  
 is the set of nodes adjacent to 
  
    
      
        u
      
    
    
  
. The definition is based on the concept that common elements with very large neighbourhoods are less significant when predicting a connection between two nodes compared with elements shared between a small number of nodes.

## Related

- [[Jaccard index]]
- [[Simple matching coefficient]]
- [[Action model learning]]
- [[Affinity analysis]]
- [[Agent mining]]
- [[AMiner (database)]]
- [[Anomaly detection]]
- [[Archetypal analysis]]
- [[Argument mining]]
- [[Association rule learning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Adamic–Adar_index