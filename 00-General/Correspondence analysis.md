---
title: "Correspondence analysis"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Correspondence_analysis"
wikipedia_categories: ["Dimension reduction"]
related: ["[[Canonical correspondence analysis]]", "[[Detrended correspondence analysis]]", "[[Feature selection]]", "[[Generalized canonical correlation]]", "[[Generalized multidimensional scaling]]", "[[Independent component analysis]]", "[[Kernel principal component analysis]]", "[[Local tangent space alignment]]", "[[Locality-sensitive hashing]]", "[[Low-rank approximation]]"]
---

# Correspondence analysis

Correspondence analysis (CA) is a multivariate statistical technique proposed by Herman Otto Hartley (Hirschfeld) and later developed by Jean-Paul Benzécri. It is conceptually similar to principal component analysis, but applies to categorical rather than continuous data. In a manner similar to principal component analysis, it provides a means of displaying or summarising a set of data in two-dimensional graphical form. Its aim is to display in a biplot any structure hidden in the multivariate setting of the data table. As such it is a technique from the field of multivariate ordination. Since the variant of CA described here can be applied either with a focus on the rows or on the columns it should in fact be called simple (symmetric) correspondence analysis.
It is traditionally applied to the contingency table of a pair of nominal variables where each cell contains either a count or a zero value. If more than two categorical variables are to be summarized, a variant called multiple correspondence analysis should be chosen instead. CA may also be applied to binary data given the presence/absence coding represents simplified count data i.e. a 1 describes a positive count and 0 stands for a count of zero. Depending on the scores used CA preserves the chi-square distance between either the rows or the columns of the table. Because CA is a descriptive technique, it can be applied to tables regardless of a significant chi-squared test. Although the 
  
    
      
        
          χ
          
            2
          
        
      
    
    
  
 statistic used in inferential statistics and the chi-square distance are computationally related they should not be confused since the latter works as a multivariate statistical distance measure in CA while the 
  
    
      
        
          χ
          
            2
          
        
      
    
    
  
 statistic is in fact a scalar not a metric.

## Related

- [[Canonical correspondence analysis]]
- [[Detrended correspondence analysis]]
- [[Feature selection]]
- [[Generalized canonical correlation]]
- [[Generalized multidimensional scaling]]
- [[Independent component analysis]]
- [[Kernel principal component analysis]]
- [[Local tangent space alignment]]
- [[Locality-sensitive hashing]]
- [[Low-rank approximation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Correspondence_analysis