---
title: "Balanced clustering"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Balanced_clustering"
wikipedia_categories: ["Clustering criteria"]
related: ["[[Adjusted mutual information]]", "[[Automatic clustering algorithms]]", "[[Davies–Bouldin index]]", "[[Determining the number of clusters in a data set]]", "[[Dunn index]]", "[[Elbow method (clustering)]]", "[[Fowlkes–Mallows index]]", "[[Hopkins statistic]]", "[[Jaccard index]]", "[[MinHash]]"]
---

# Balanced clustering

Balanced clustering is a special case of clustering where, in the strictest sense, cluster sizes are constrained to 
  
    
      
        ⌊
        
          
            n
            k
          
        
        ⌋
      
    
    
  
 or 
  
    
      
        ⌈
        
          
            n
            k
          
        
        ⌉
      
    
    
  
, where 
  
    
      
        n
      
    
    
  
 is the number of points and 
  
    
      
        k
      
    
    
  
 is the number of clusters. A typical algorithm is balanced k-means, which minimizes mean square error (MSE). Another type of balanced clustering called balance-driven clustering has a two-objective cost function that minimizes both the imbalance and the MSE. Typical cost functions are ratio cut and Ncut. Balanced clustering can be used for example in scenarios where freight has to be delivered to 
  
    
      
        n
      
    
    
  
 locations with 
  
    
      
        k
      
    
    
  
 cars. It is then preferred that each car delivers to an equal number of locations.

## Related

- [[Adjusted mutual information]]
- [[Automatic clustering algorithms]]
- [[Davies–Bouldin index]]
- [[Determining the number of clusters in a data set]]
- [[Dunn index]]
- [[Elbow method (clustering)]]
- [[Fowlkes–Mallows index]]
- [[Hopkins statistic]]
- [[Jaccard index]]
- [[MinHash]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Balanced_clustering