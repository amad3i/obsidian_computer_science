---
title: "Bloom filters in bioinformatics"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Bloom_filters_in_bioinformatics"
wikipedia_categories: ["Bioinformatics"]
related: ["[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]", "[[Adaptive sampling]]", "[[Algae DNA barcoding]]", "[[Align-m]]", "[[Alignment-free sequence analysis]]"]
---

# Bloom filters in bioinformatics

Bloom filters are space-efficient probabilistic data structures used to test whether an element is a part of a set. Bloom filters require much less space than other data structures for representing sets, however the downside of Bloom filters is that there is a false positive rate when querying the data structure. Since multiple elements may have the same hash values for a number of hash functions, then there is a probability that querying for a non-existent element may return a positive if another element with the same hash values has been added to the Bloom filter. Assuming that the hash function has equal probability of selecting any index of the Bloom filter, the false positive rate of querying a Bloom filter is a function of the number of bits, number of hash functions and number of elements of the Bloom filter. This allows the user to manage the risk of a getting a false positive by compromising on the space benefits of the Bloom filter.
Bloom filters are primarily used in bioinformatics to test the existence of a k-mer in a sequence or set of sequences. The k-mers of the sequence are indexed in a Bloom filter, and any k-mer of the same size can be queried against the Bloom filter. This is a preferable alternative to hashing the k-mers of a sequence with a hash table, particularly when the sequence is very long, since it is very demanding to store large numbers of k-mers in memory.

## Related

- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]
- [[Accession number (bioinformatics)]]
- [[Actino-ugpB RNA motif]]
- [[Adaptive sampling]]
- [[Algae DNA barcoding]]
- [[Align-m]]
- [[Alignment-free sequence analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bloom_filters_in_bioinformatics