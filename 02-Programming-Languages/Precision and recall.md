---
title: "Precision and recall"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Precision_and_recall"
wikipedia_categories: ["Bioinformatics", "Information retrieval evaluation", "Information science"]
related: ["[[BioCreative]]", "[[Ontology engineering]]", "[[Ontology for Biomedical Investigations]]", "[[Phi coefficient]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]"]
---

# Precision and recall

In classification, precision and recall are performance metrics that apply to data retrieved from a collection, corpus or sample space.
Precision (also called positive predictive value) is the fraction of relevant instances among the retrieved instances. Written as a formula:

  
    
      
        
          Precision
        
        
          
            Relevant retrieved instances
            
              
                All 
              
              
                
                  retrieved
                
              
              
                 instances
              
            
          
        
      
    
    
  

Recall (also known as sensitivity) is the fraction of relevant instances that were retrieved. Written as a formula:

  
    
      
        
          Recall
        
        
          
            Relevant retrieved instances
            
              
                All 
              
              
                
                  relevant
                
              
              
                 instances
              
            
          
        
      
    
    
  

Both precision and recall are therefore based on relevance. 
Consider a computer program for recognizing dogs (the relevant element) in a digital photograph. Upon processing a picture which contains ten cats and twelve dogs, the program identifies eight dogs. Of the eight elements identified as dogs, only five actually are dogs (true positives), while the other three are cats (false positives). Seven dogs were missed (false negatives), and seven cats were correctly excluded (true negatives). The program's precision is then 5/8 (true positives / selected elements) while its recall is 5/12 (true positives / relevant elements).
Adopting a hypothesis-testing approach, where in this case, the null hypothesis is that a given item is irrelevant (not a dog), absence of type I and type II errors (perfect specificity and sensitivity) corresponds respectively to perfect precision (no false positives) and perfect recall (no false negatives).  
More generally, recall is simply the complement of the type II error rate (i.e., one minus the type II error rate). Precision is related to the type I error rate, but in a slightly more complicated way, as it also depends upon the prior distribution of seeing a relevant vs. an irrelevant item.
The above cat and dog example contained 8 − 5 = 3 type I errors (false positives) out of 10 total cats (true negatives), for a type I error rate of 3/10, and 12 − 5 = 7 type II errors (false negatives), for a type II error rate of 7/12.  Precision can be seen as a measure of quality, and recall as a measure of quantity. 
Higher precision means that an algorithm returns more relevant results than irrelevant ones, and high recall means that an algorithm returns most of the relevant results (whether or not irrelevant ones are also returned).

## Related

- [[BioCreative]]
- [[Ontology engineering]]
- [[Ontology for Biomedical Investigations]]
- [[Phi coefficient]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]
- [[Accession number (bioinformatics)]]
- [[Actino-ugpB RNA motif]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Precision_and_recall