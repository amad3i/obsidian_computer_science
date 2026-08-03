---
title: "Linguistic sequence complexity"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Linguistic_sequence_complexity"
wikipedia_categories: ["Bioinformatics", "Nucleic acids"]
related: ["[[In silico PCR]]", "[[K-mer]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]", "[[Adaptive sampling]]", "[[Algae DNA barcoding]]"]
---

# Linguistic sequence complexity

Linguistic sequence complexity (LC) is a measure of the 'vocabulary richness' of a genetic text in gene sequences.
When a nucleotide sequence is written as text using a four-letter alphabet, the repetitiveness of the text, that is, the repetition of its N-grams (words), can be calculated and serves as a measure of sequence complexity. Thus, the more complex a DNA sequence, the richer its oligonucleotide vocabulary, whereas repetitious sequences have relatively lower complexities. Subsequent work improved the original algorithm described in Trifonov (1990), without changing the essence of the linguistic complexity approach.
The meaning of LC may be better understood by regarding the presentation of a sequence as a tree of all subsequences of the given sequence. The most complex sequences have maximally balanced trees, while the measure of imbalance or tree asymmetry serves as a complexity measure. The number of nodes at the tree level i is equal to the actual vocabulary size of words with the length i in a given sequence; the number of nodes in the most balanced tree, which corresponds to the most complex sequence of length N, at the tree level i is either 4i or N-i+1, whichever is smaller. Complexity (C) of a sequence fragment (with a length RW) can be directly calculated as the product of vocabulary-usage measures (Ui):
      
  
    
      
        C
        
          U
          
            1
          
        
        
          U
          
            2
          
        
        .
        .
        .
        
          U
          
            i
          
        
        .
        .
        .
        .
        
          U
          
            w
          
        
      
    
    
  

Vocabulary usage for oligomers of a given size i can be defined as the ratio of the actual vocabulary size of a given sequence to the maximal possible vocabulary size for a sequence of that length. For example, U2 for the sequence ACGGGAAGCTGATTCCA = 14/16, as it contains 14 of 16 possible different dinucleotides; U3 for the same sequence = 15/15, and U4=14/14. For the sequence ACACACACACACACACA, U1=1/2; U2=2/16=0.125, as it has a simple vocabulary of only two dinucleotides; U3 for this sequence = 2/15. k-tuples with k from two to W considered, while W depends on RW. For RW values less than 18, W is equal to 3; for RW less than 67, W is equal to 4; for RW<260, W=5; for RW<1029, W=6, and so on. The value of C provides a measure of sequence complexity in the range 0<C<1 for various DNA sequence fragments of a given length.
This formula is different from the original LC measure in two respects: in the way vocabulary usage Ui is calculated, and because i is not in the range of 2 to N-1 but only up to W. This limitation on the range of Ui makes the algorithm substantially more efficient without loss of power.
In   was used another modified version, wherein linguistic complexity (LC) is defined as the ratio of the number of substrings of any length present in the string to the maximum possible number of substrings. Maximum vocabulary over word sizes 1 to m can be calculated according to the simple formula .
This sequence analysis complexity calculation can be used to search for conserved regions between compared sequences for the detection of low-complexity regions including simple sequence repeats, imperfect direct or inverted repeats, polypurine and polypyrimidine triple-stranded DNA structures, and four-stranded structures (such as G-quadruplexes).

## Related

- [[In silico PCR]]
- [[K-mer]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]
- [[Accession number (bioinformatics)]]
- [[Actino-ugpB RNA motif]]
- [[Adaptive sampling]]
- [[Algae DNA barcoding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linguistic_sequence_complexity