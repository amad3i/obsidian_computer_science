---
title: "Hierarchical clustering"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Hierarchical_clustering"
wikipedia_categories: ["Cluster analysis algorithms", "Network analysis"]
related: ["[[Automatic clustering algorithms]]", "[[BIRCH]]", "[[Canopy clustering algorithm]]", "[[Centrality]]", "[[Clique percolation method]]", "[[Cluster-weighted modeling]]", "[[Cobweb (clustering)]]", "[[Constrained clustering]]", "[[Data stream clustering]]", "[[DBSCAN]]"]
---

# Hierarchical clustering

In data mining and statistics, hierarchical clustering (also called hierarchical cluster analysis or HCA) is a method of cluster analysis that seeks to build a hierarchy of clusters. Strategies for hierarchical clustering generally fall into two categories:

Agglomerative: Agglomerative clustering, often referred to as a "bottom-up" approach, begins with each data point as an individual cluster. At each step, the algorithm merges the two most similar clusters based on a chosen distance metric (e.g., Euclidean distance) and linkage criterion (e.g., single-linkage, complete-linkage). This process continues until all data points are combined into a single cluster or a stopping criterion is met. Agglomerative methods are more commonly used due to their simplicity and computational efficiency for small to medium-sized datasets.
Divisive: Divisive clustering, known as a "top-down" approach, starts with all data points in a single cluster and recursively splits the cluster into smaller ones. At each step, the algorithm selects a cluster and divides it into two or more subsets, often using a criterion such as maximizing the distance between resulting clusters. Divisive methods are less common but can be useful when the goal is to identify large, distinct clusters first.
In general, the merges and splits are determined in a greedy manner. The results of hierarchical clustering are usually presented in a dendrogram. 
Hierarchical clustering has the distinct advantage that any valid measure of distance can be used. In fact, the observations themselves are not required: all that is used is a matrix of distances. On the other hand, except for the special case of single-linkage distance, none of the algorithms (except exhaustive search in 
  
    
      
        
          
            O
          
        
        
          2
          
            n
          
        
      
    
    
  
) can be guaranteed to find the optimum solution.

## Related

- [[Automatic clustering algorithms]]
- [[BIRCH]]
- [[Canopy clustering algorithm]]
- [[Centrality]]
- [[Clique percolation method]]
- [[Cluster-weighted modeling]]
- [[Cobweb (clustering)]]
- [[Constrained clustering]]
- [[Data stream clustering]]
- [[DBSCAN]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hierarchical_clustering