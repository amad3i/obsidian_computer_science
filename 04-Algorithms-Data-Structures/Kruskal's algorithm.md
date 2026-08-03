---
title: "Kruskal's algorithm"
tags: ["cs", "algorithms-data-structures", "core"]
domain: Algorithms & Data Structures
level: core
source: "https://en.wikipedia.org/wiki/Kruskal's_algorithm"
wikipedia_categories: ["Graph algorithms", "Greedy algorithms", "Spanning tree"]
related: ["[[Prim's algorithm]]", "[[A- search algorithm]]", "[[Borůvka's algorithm]]", "[[Christofides algorithm]]", "[[Dijkstra's algorithm]]", "[[Minimum bottleneck spanning tree]]", "[[Reverse-delete algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]"]
---

# Kruskal's algorithm

Kruskal's algorithm finds a minimum spanning forest of an undirected edge-weighted graph. If the graph is connected, it finds a minimum spanning tree. It is a greedy algorithm that in each step adds to the forest the lowest-weight edge that will not form a cycle. The key steps of the algorithm are sorting and the use of a disjoint-set data structure to detect cycles. Its running time is dominated by the time to sort all of the graph edges by their weight.
A minimum spanning tree of a connected weighted graph is a connected subgraph, without cycles, for which the sum of the weights of all the edges in the subgraph is minimal. For a disconnected graph, a minimum spanning forest is composed of a minimum spanning tree for each connected component.
This algorithm was first published by Joseph Kruskal in 1956, and was rediscovered soon afterward by Loberman & Weinberger (1957). Other algorithms for this problem include Prim's algorithm, Borůvka's algorithm, and the reverse-delete algorithm.

== Algorithm ==
The algorithm performs the following steps:

Create a forest (a set of trees) initially consisting of a separate single-vertex tree for each vertex in the input graph.
Sort the graph edges by weight.
Loop through the edges of the graph, in ascending sorted order by their weight. For each edge:
Test whether adding the edge to the current forest would create a cycle.
If not, add the edge to the forest, combining two trees into a single tree.
At the termination of the algorithm, the forest forms a minimum spanning forest of the graph. If the graph is connected, the forest has a single component and forms a minimum spanning tree.

== Pseudocode ==
The following code is implemented with a disjoint-set data structure. It represents the forest F as a set of undirected edges, and uses the disjoint-set data structure to efficiently determine whether two vertices are part of the same tree.

function Kruskal(Graph G) is
    F:= ∅
    for each v in G.Vertices do
        MAKE-SET(v)

    for each {u, v} in G.Edges ordered by increasing weight({u, v}) do
        if FIND-SET(u) ≠ FIND-SET(v) then
            F := F ∪ { {u, v} }
            UNION(FIND-SET(u), FIND-SET(v))
    return F

== Complexity ==
For a graph with E edges and V vertices, Kruskal's algorithm can be shown to run in time O(E log E) time, with simple data structures. This time bound is often written instead as O(E log V), which is equivalent for graphs with no isolated vertices, because for these graphs V / 2 ≤ E < V2 and the logarithms of V and V2 are again within a constant factor of each other.
To achieve this bound, first sort the edges by weight using a comparison sort in O(E log E) time. Once sorted, it is possible to loop through the edges in sorted order in constant time per edge. Next, use a disjoint-set data structure, with a set of vertices for each component, to keep track of which vertices are in which components. Creating this structure, with a separate set for each vertex, takes V operations and O(V) time. The final iteration through all edges performs two find operations and possibly one union operation per edge. These operations take amortized time O(α(V)) time per operation, giving worst-case total time O(E α(V)) for this loop, where α is the extremely slowly growing inverse Ackermann function. This part of the time bound is much smaller than the time for the sorting step, so the total time for the algorithm can be simplified to the time for the sorting step.
In cases where the edges are already sorted, or where they have small enough integer weight to allow integer sorting algorithms such as counting sort or radix sort to sort them in linear time, the disjoint set operations are the slowest remaining part of the algorithm and the total time is O(E α(V)).

== Example ==

== Proof of correctness ==
The proof consists of two parts. First, it is proved that the algorithm produces a spanning tree. Second, it is proved that the constructed spanning tree is of minimal weight.

=== Spanning tree ===
Let 
  
    
      
        G
      
    
    
  
 be a connected, weighted graph and let 
  
    
      
        Y
      
    
    
  
 be the subgraph of 
  
    
      
        G
      
    
    
  
 produced by the algorithm. 
  
    
      
        Y
      
    
    
  
 cannot have a cycle, as by definition an edge is not added if it results in a cycle. 
  
    
      
        Y
      
    
    
  
 cannot be disconnected, since the first encountered edge that joins two components of 
  
    
      
        Y
      
    
    
  
 would have been added by the algorithm. Thus, 
  
    
      
        Y
      
    
    
  
 is a spanning tree of 
  
    
      
        G
      
    
    
  
.

=== Minimality ===
We show that the following proposition P is true by induction: If F is the set of edges chosen at any stage of the algorithm, then there is some minimum spanning tree that contains F and none of the edges rejected by the algorithm.

Clearly P is true at the beginning, when F is empty: any minimum spanning tree will do, and there exists one because a weighted connected graph always has a minimum spanning tree.
Now assume P is true for some non-final edge set F and let T be a minimum spanning tree that contains F.
If the next chosen edge e is also in T, then P is true for F + e.
Otherwise, if e is not in T then T + e has a cycle C. The cycle C contains edges which do not belong to  F + e, since e does not form a cycle when added to F but does in T.  Let f be an edge which is in C but not in F + e.  Note that f also belongs to T, since f belongs to T + e but not F + e. By  P, f has not been considered by the algorithm. f must therefore have a weight at least as large as e. Then T − f + e is a tree, and it has the same or less weight as T. However since T is a minimum spanning tree then T − f + e has the same weight as T, otherwise we get a contradiction and T would not be a minimum spanning tree. So T − f + e is a minimum spanning tree containing F + e and again P holds.
Therefore, by the principle of induction, P holds when F has become a spanning tree, which is only possible if F is a minimum spanning tree itself.

== Parallel algorithm ==
Kruskal's algorithm is inherently sequential and hard to parallelize. It is, however, possible to perform the initial sorting of the edges in parallel or, alternatively, to use a parallel implementation of a binary heap to extract the minimum-weight edge in every iteration.
As parallel sorting is possible in time 
  
    
      
        O
        n
      
    
    
  
 on 
  
    
      
        O
        log
         
        n
      
    
    
  
 processors, the runtime of Kruskal's algorithm can be reduced to O(E α(V)), where α again is the inverse of the single-valued Ackermann function.
A variant of Kruskal's algorithm, named Filter-Kruskal, has been described by Osipov et al. and is better suited for parallelization. The basic idea behind Filter-Kruskal is to partition the edges in a similar way to quicksort and filter out edges that connect vertices of the same tree to reduce the cost of sorting. The following pseudocode demonstrates this.

function filter_kruskal(G) is
    if |G.E| < kruskal_threshold:
        return kruskal(G)
    pivot = choose_random(G.E)
    E≤, E> = partition(G.E, pivot)
    A = filter_kruskal(E≤)
    E> = filter(E>)
    A = A ∪ filter_kruskal(E>)
    return A

function partition(E, pivot) is
    E≤ = ∅, E> = ∅
    foreach (u, v) in E do
        if weight(u, v) ≤ pivot then
            E≤ = E≤ ∪ {(u, v)}
        else
            E> = E> ∪ {(u, v)}
    return E≤, E>

function filter(E) is
    Ef = ∅
    foreach (u, v) in E do
        if find_set(u) ≠ find_set(v) then
            Ef = Ef ∪ {(u, v)}
    return Ef

Filter-Kruskal lends itself better to parallelization as sorting, filtering, and partitioning can easily be performed in parallel by distributing the edges between the processors.
Finally, other variants of a parallel implementation of Kruskal's algorithm have been explored. Examples include a scheme that uses helper threads to remove edges that are definitely not part of the MST in the background, and a variant which runs the sequential algorithm on p subgraphs, then merges those subgraphs until only one, the final MST, remains.

== See also ==
Dijkstra's algorithm
Greedy geometric spanner
Single-linkage clustering

== References ==

Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, and Clifford Stein. Introduction to Algorithms, Second Edition. MIT Press and McGraw-Hill, 2001. ISBN 0-262-03293-7. Section 23.2: The algorithms of Kruskal and Prim, pp. 567–574.
Michael T. Goodrich and Roberto Tamassia. Data Structures and Algorithms in Java, Fourth Edition. John Wiley & Sons, Inc., 2006. ISBN 0-471-73884-0. Section 13.7.1: Kruskal's Algorithm, pp. 632..

== External links ==
Data for the article's example.
Gephi Plugin For Calculating a Minimum Spanning Tree source code.
Kruskal's Algorithm with example and program in c++
Kruskal's Algorithm code in C++ as applied to random numbers
Kruskal's Algorithm code in Python with explanation
Kruskal's Algorithm code in C with Explanation and Example
The Implementation of Kruskal’s Algorithm for Minimum Spanning Tree in a Graph
Comparative Performance Analysis of Kruskal and Prim MST Algorithms

*(note truncated for size; full article at the source link below)*

## Related

- [[Prim's algorithm]]
- [[A- search algorithm]]
- [[Borůvka's algorithm]]
- [[Christofides algorithm]]
- [[Dijkstra's algorithm]]
- [[Minimum bottleneck spanning tree]]
- [[Reverse-delete algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kruskal's_algorithm