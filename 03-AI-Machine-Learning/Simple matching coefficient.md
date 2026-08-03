---
title: "Simple matching coefficient"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Simple_matching_coefficient"
wikipedia_categories: ["Clustering criteria", "Index numbers", "Measure theory", "Similarity measures", "String metrics"]
related: ["[[Jaccard index]]", "[[Adamic–Adar index]]", "[[Similarity measure]]", "[[Adjusted mutual information]]", "[[Automatic clustering algorithms]]", "[[Balanced clustering]]", "[[Category of Markov kernels]]", "[[Category of measurable spaces]]", "[[Damerau–Levenshtein distance]]", "[[Davies–Bouldin index]]"]
---

# Simple matching coefficient

The simple matching coefficient (SMC) or Rand similarity coefficient is a statistic used for comparing the similarity and diversity of sample sets.

Given two objects, A and B, each with n binary attributes, SMC is defined as:

  
    
      
        
          
            
              
                
                  SMC
                
              
              
                
                
                  
                    number of matching attributes
                    total number of attributes
                  
                
              
            
            
              
              
                
                
                  
                    
                      
                        M
                        
                          00
                        
                      
                      
                        M
                        
                          11
                        
                      
                    
                    
                      
                        M
                        
                          00
                        
                      
                      
                        M
                        
                          11
                        
                      
                      
                        M
                        
                          01
                        
                      
                      
                        M
                        
                          10
                        
                      
                    
                  
                
              
            
          
        
      
    
    
  

where

  
    
      
        
          M
          
            00
          
        
      
    
    
  
 is the total number of attributes where A and B both have a value of 0,

  
    
      
        
          M
          
            11
          
        
      
    
    
  
 is the total number of attributes where A and B both have a value of 1,

  
    
      
        
          M
          
            01
          
        
      
    
    
  
 is the total number of attributes where A has value 0 and B has value 1, and

  
    
      
        
          M
          
            10
          
        
      
    
    
  
 is the total number of attributes where A has value 1 and B has value 0.
The simple matching distance (SMD), which measures dissimilarity between sample sets, is given by 
  
    
      
        1
        
          SMC
        
      
    
    
  
.
SMC is linearly related to Hamann similarity: 
  
    
      
        
          SMC
        
        (
        
          Hamann
        
        1
        
          /
        
        2
      
    
    
  
. Also, 
  
    
      
        
          SMC
        
        1
        
          D
          
            2
          
        
        
          /
        
        n
      
    
    
  
, where 
  
    
      
        
          D
          
            2
          
        
      
    
    
  
 is the squared Euclidean distance between the two objects (binary vectors) and n is the number of attributes.
The SMC is very similar to the more popular Jaccard index. The main difference is that the SMC has the term 
  
    
      
        
          M
          
            00
          
        
      
    
    
  
 in its numerator and denominator, whereas the Jaccard index does not. Thus, the SMC counts both mutual presences (when an attribute is present in both sets) and mutual absence (when an attribute is absent in both sets) as matches and compares it to the total number of attributes in the universe, whereas the Jaccard index only counts mutual presence as matches and compares it to the number of attributes that have been chosen by at least one of the two sets.
In market basket analysis, for example, the basket of two consumers who we wish to compare might only contain a small fraction of all the available products in the store, so the SMC will usually return very high values of similarities even when the baskets bear very little resemblance, thus making the Jaccard index a more appropriate measure of similarity in that context. For example, consider a supermarket with 1000 products and two customers. The basket of the first customer contains salt and pepper and the basket of the second contains salt and sugar. In this scenario, the similarity between the two baskets as measured by the Jaccard index would be 1/3, but the similarity becomes 0.998 using the SMC.
In other contexts, where 0 and 1 carry equivalent information (symmetry), the SMC is a better measure of similarity. For example, vectors of demographic variables stored in dummy variables, such as binary gender, would be better compared with the SMC than with the Jaccard index since the impact of gender on similarity should be equal, independently of whether male is defined as a 0 and female as a 1 or the other way around. However, when we have symmetric dummy variables, one could replicate the behaviour of the SMC by splitting the dummies into two binary attributes (in this case, male and female), thus transforming them into asymmetric attributes, allowing the use of the Jaccard index without introducing any bias. By using this trick, the Jaccard index can be considered as making the SMC a fully redundant metric. The SMC remains, however, more computationally efficient in the case of symmetric dummy variables since it does not require adding extra dimensions.
The Jaccard index is also more general than the SMC and can be used to compare other data types than just vectors of binary attributes, such as probability measures.

## Related

- [[Jaccard index]]
- [[Adamic–Adar index]]
- [[Similarity measure]]
- [[Adjusted mutual information]]
- [[Automatic clustering algorithms]]
- [[Balanced clustering]]
- [[Category of Markov kernels]]
- [[Category of measurable spaces]]
- [[Damerau–Levenshtein distance]]
- [[Davies–Bouldin index]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simple_matching_coefficient