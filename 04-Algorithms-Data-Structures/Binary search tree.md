---
title: "Binary search tree"
tags: ["cs", "algorithms-data-structures", "core"]
domain: Algorithms & Data Structures
level: core
source: "https://en.wikipedia.org/wiki/Binary_search_tree"
wikipedia_categories: ["Binary trees", "Search trees"]
related: ["[[AVL tree]]", "[[Red–black tree]]", "[[Binary space partitioning]]", "[[Binary tree]]", "[[Search tree]]"]
---

# Binary search tree

In computer science, a binary search tree (BST), also called an ordered or sorted binary tree, is a rooted binary tree data structure with the key of each internal node being greater than all the keys in the respective node's left subtree and less than the ones in its right subtree. The time complexity of operations on the binary search tree is linear with respect to the height of the tree.
Binary search trees allow binary search for fast lookup, addition, and removal of data items. Since the nodes in a BST are laid out so that each comparison skips about half of the remaining tree, the lookup performance is proportional to that of binary logarithm. BSTs were devised in the 1960s for the problem of efficient storage of labeled data and are attributed to Conway Berners-Lee and David Wheeler.
The performance of a binary search tree is dependent on the order of insertion of the nodes into the tree since arbitrary insertions may lead to degeneracy; several variations of the binary search tree can be built with guaranteed worst-case performance. The basic operations include: search, traversal, insert and delete. BSTs with guaranteed worst-case complexities perform better than an unsorted array, which would require linear search time.
The complexity analysis of BST shows that, on average, the insert, delete and search takes 
  
    
      
        Θ
        log
         
        n
      
    
    
  
 for 
  
    
      
        n
      
    
    
  
 nodes. In the worst case, they degrade to that of a singly linked list: 
  
    
      
        O
        n
      
    
    
  
. To address the boundless increase of the tree height with arbitrary insertions and deletions, self-balancing variants of BSTs are introduced to bound the worst lookup complexity to that of the binary logarithm. AVL trees were the first self-balancing binary search trees, invented in 1962 by Georgy Adelson-Velsky and Evgenii Landis.
Binary search trees can be used to implement abstract data types such as dynamic sets, lookup tables and priority queues, and used in sorting algorithms such as tree sort.

== History ==
The binary search tree algorithm was discovered independently by several researchers, including P.F. Windley, Andrew Donald Booth, Andrew Colin, Thomas N. Hibbard. The algorithm is attributed to Conway Berners-Lee and David Wheeler, who used it for storing labeled data in magnetic tapes in 1960. One of the earliest and popular binary search tree algorithm is that of Hibbard.
The time complexity of a binary search tree increases boundlessly with the tree height if the nodes are inserted in an arbitrary order, therefore self-balancing binary search trees were introduced to bound the height of the tree to 
  
    
      
        O
        log
         
        n
      
    
    
  
. Various height-balanced binary search trees were introduced to confine the tree height, such as AVL trees, Treaps, and red–black trees.

== Overview ==
A binary search tree is a rooted binary tree in which nodes are arranged in strict total order in which the nodes with keys greater than any particular node A is stored on the right sub-trees to that node A and the nodes with keys equal to or less than A are stored on the left sub-trees to A, satisfying the binary search property.
Binary search trees are also efficacious in sortings and search algorithms. However, the search complexity of a BST depends upon the order in which the nodes are inserted and deleted; since in worst case, successive operations in the binary search tree may lead to degeneracy and form a singly linked list (or "unbalanced tree") like structure, thus has the same worst-case complexity as a linked list. 
Binary search trees are also a fundamental data structure used in construction of abstract data structures such as sets, multisets, and associative arrays.

== Operations ==

=== Searching ===
Searching in a binary search tree for a specific key can be programmed recursively or iteratively.
Searching begins by examining the root node. If the tree is nil, the key being searched for does not exist in the tree. Otherwise, if the key equals that of the root, the search is successful and the node is returned. If the key is less than that of the root, the search proceeds by examining the left subtree. Similarly, if the key is greater than that of the root, the search proceeds by examining the right subtree. This process is repeated until the key is found or the remaining subtree is 
  
    
      
        
          nil
        
      
    
    
  
. If the searched key is not found after a 
  
    
      
        
          nil
        
      
    
    
  
 subtree is reached, then the key is not present in the tree.

==== Recursive search ====
The following pseudocode implements the BST search procedure through recursion.

The recursive procedure continues until a 
  
    
      
        
          nil
        
      
    
    
  
 or the 
  
    
      
        
          key
        
      
    
    
  
 being searched for are encountered.

==== Iterative search ====
The recursive version of the search can be "unrolled" into a while loop. On most machines, the iterative version is found to be more efficient.

Since the search may proceed till some leaf node, the running time complexity of BST search is 
  
    
      
        O
        h
      
    
    
  
 where 
  
    
      
        h
      
    
    
  
 is the height of the tree. However, the worst case for BST search is 
  
    
      
        O
        n
      
    
    
  
 where 
  
    
      
        n
      
    
    
  
 is the total number of nodes in the BST, because an unbalanced BST may degenerate to a linked list. However, if the BST is height-balanced the height is 
  
    
      
        O
        log
         
        n
      
    
    
  
.

==== Successor and predecessor ====
For certain operations, given a node 
  
    
      
        
          x
        
      
    
    
  
, finding the successor or predecessor of 
  
    
      
        
          x
        
      
    
    
  
 is crucial. Assuming all the keys of a BST are distinct, the successor of a node 
  
    
      
        
          x
        
      
    
    
  
 in a BST is the node with the smallest key greater than 
  
    
      
        
          x
        
      
    
    
  
's key. On the other hand, the predecessor of a node 
  
    
      
        
          x
        
      
    
    
  
 in a BST is the node with the largest key smaller than 
  
    
      
        
          x
        
      
    
    
  
's key. The following pseudocode finds the successor and predecessor of a node 
  
    
      
        
          x
        
      
    
    
  
 in a BST.

Operations such as finding a node in a BST whose key is the maximum or minimum are critical in certain operations, such as determining the successor and predecessor of nodes. Following is the pseudocode for the operations.

=== Insertion ===
Operations such as insertion and deletion cause the BST representation to change dynamically. The data structure must be modified in such a way that the properties of BST continue to hold. New nodes are inserted as leaf nodes in the BST. Following is an iterative implementation of the insertion operation.

The procedure maintains a "trailing pointer" 
  
    
      
        
          y
        
      
    
    
  
 as a parent of 
  
    
      
        
          x
        
      
    
    
  
. After initialization on line 2, the while loop along lines 4-11 causes the pointers to be updated. If 
  
    
      
        
          y
        
      
    
    
  
 is 
  
    
      
        
          nil
        
      
    
    
  
, the BST is empty, thus 
  
    
      
        
          z
        
      
    
    
  
 is inserted as the root node of the binary search tree 
  
    
      
        
          T
        
      
    
    
  
, if it is not 
  
    
      
        
          nil
        
      
    
    
  
, insertion proceeds by comparing the keys to that of 
  
    
      
        
          y
        
      
    
    
  
 on the lines 15-19 and the node is inserted accordingly.

=== Deletion ===

The deletion of a node, say 
  
    
      
        
          Z
        
      
    
    
  
, from the binary search tree 
  
    
      
        
          BST
        
      
    
    
  
 has three cases:

If 
  
    
      
        
          Z
        
      
    
    
  
 is a leaf node, it is replaced by 
  
    
      
        
          NIL
        
      
    
    
  
 as shown in (a).
If 
  
    
      
        
          Z
        
      
    
    
  
 has only one child, the child node of 
  
    
      
        
          Z
        
      
    
    
  
 gets elevated by modifying the parent node of 
  
    
      
        
          Z
        
      
    
    
  
 to point to the child node, consequently taking 
  
    
      
        
          Z
        
      
    
    
  
's position in the tree, as shown in (b) and (c).
If 
  
    
      
        
          Z
        
      
    
    
  
 has both left and right children, the in-order successor of 
  
    
      
        
          Z
        
      
    
    
  
, say 
  
    
      
        
          Y
        
      
    
    
  
, displaces 
  
    
      
        
          Z
        
      
    
    
  
 by following the two cases:
If 
  
    
      
        
          Y
        
      
    
    
  
 is 
  
    
      
        
          Z
        
      
    
    
  
's right child, as shown in (d), 
  
    
      
        
          Y
        
      
    
    
  
 displaces 
  
    
      
        
          Z
        
      
    
    
  
 and 
  
    
      
        
          Y
        
      
    
    
  
's right child remain unchanged.
If 
  
    
      
        
          Y
        
      
    
    
  
 lies within 
  
    
      
        
          Z
        
      
    
    
  
's right subtree but is not 
  
    
      
        
          Z
        
      
    
    
  
's right child, as shown in (e), 
  
    
      
        
          Y
        
      
    
    
  
 first gets replaced by its own right child, and then it displaces 
  
    
      
        
          Z
        
      
    
    
  
's position in the tree.
Alternatively, the in-order predecessor can also be used.
The following pseudocode implements the deletion operation in a binary search tree.

The 
  
    
      
        
          BST-Delete
        
      
    
    
  
 procedure deals with the 3 special cases mentioned above. Lines 2-3 deal with case 1; lines 4-5 deal with case 2 and lines 6-16 for case 3. The helper function 
  
    
      
        
          Shift-Nodes
        
      
    
    
  
 is used within the deletion algorithm for the purpose of replacing the node 
  
    
      
        
          u
        
      
    
    
  
 with 
  
    
      
        
          v
        
      
    
    
  
 in the binary search tree 
  
    
      
        
          BST
        
      
    
    
  
. This procedure handles the deletion (and substitution) of 
  
    
      
        
          u
        
      
    
    
  
 from 
  
    
      
        
          BST
        
      
    
    
  
.

== Traversal ==

A BST can be traversed through three basic algorithms: inorder, preorder, and postorder tree walks.

Inorder tree walk: Nodes from the left subtree get visited first, followed by the root node and right subtree. Such a traversal visits all the nodes in the order of non-decreasing key sequence.
Preorder tree walk: The root node gets visited first, followed by left and right subtrees.
Postorder tree walk: Nodes from the left subtree get visited first, followed by the right subtree, and finally, the root.
Following is a recursive implementation of the tree walks.

== Balanced binary search trees ==

Without rebalancing, insertions or deletions in a binary search tree may lead to degeneration, resulting in a height 
  
    
      
        n
      
    
    
  
 of the tree (where 
  
    
      
        n
      
    
    
  
 is number of items in a tree), so that the lookup performance is deteriorated to that of a linear search. Keeping the search tree balanced and height bounded by 
  
    
      
        O
        log
         
        n
      
    
    
  
 is a key to the usefulness of the binary search tree. This can be achieved by "self-balancing" mechanisms during the updation operations to the tree designed to maintain the tree height to the binary logarithmic complexity.

=== Height-balanced trees ===
A tree is height-balanced if the heights of the left sub-tree and right sub-tree are guaranteed to be related by a constant factor. This property was introduced by the AVL tree and continued by the red–black tree. The heights of all the nodes on the path from the root to the modified leaf node have to be observed and possibly corrected on every insert and delete operation to the tree.

=== Weight-balanced trees ===

In a weight-balanced tree, the criterion of a balanced tree is the number of leaves of the subtrees. The weights of the left and right subtrees differ at most by 
  
    
      
        1
      
    
    
  
. However, the difference is bound by a ratio 
  
    
      
        α
      
    
    
  
 of the weights, since a strong balance condition of 
  
    
      
        1
      
    
    
  
 cannot be maintained with 
  
    
      
        O
        log
         
        n
      
    
    
  
 rebalancing work during insert and delete operations. The 
  
    
      
        α
      
    
    
  
-weight-balanced trees gives an entire family of balance conditions, where each left and right subtrees have each at least a fraction of 
  
    
      
        α
      
    
    
  
 of the total weight of the subtree.

=== Types ===
There are several self-balanced binary search trees, including T-tree, treap, red-black tree, B-tree, 2–3 tree, and Splay tree.

== Examples of applications ==

=== Sort ===

Binary search trees are used in sorting algorithms such as tree sort, where all the elements are inserted at once and the tree is traversed at an in-order fashion. BSTs are also used in quicksort.

=== Priority queue operations ===

Binary search trees are used in implementing priority queues, using the node's key as priorities. Adding new elements to the queue follows the regular BST insertion operation but the removal operation depends on the type of priority queue:

If it is an ascending order priority queue, removal of an element with the lowest priority is done through leftward traversal of the BST.
If it is a descending order priority queue, removal of an element with the highest priority is done through rightward traversal of the BST.

== See also ==

== References ==

== Further reading ==
 This article incorporates public domain material from Paul E. Black. "Binary Search Tree". Dictionary of Algorithms and Data Structures. NIST.
Cormen, Thomas H.; Leiserson, Charles E.; Rivest, Ronald L.; Stein, Clifford (2001). "12: Binary search trees, 15.5: Optimal binary search trees". Introduction to Algorithms (2nd ed.). MIT Press. pp. 253–272, 356–363. ISBN 0-262-03293-7.
Jarc, Duane J. (3 December 2005). "Binary Tree Traversals". Interactive Data Structure Visualizations. University of Maryland. Archived from the original on 27 February 2014. Retrieved 30 April 2006.
Knuth, Donald (1997). "6.2.2: Binary Tree Searching". The Art of Computer Programming. Vol. 3: "Sorting and Searching" (3rd ed.). Addison-Wesley. pp. 426–458. ISBN 0-201-89685-0.
Long, Sean. "Binary Search Tree" (PPT). Data Structures and Algorithms Visualization-A PowerPoint Slides Based Approach. SUNY Oneonta.
Parlante, Nick (2001). "Binary Trees". CS Education Library. Stanford University. Archived from the original on 2022-01-30.

== External links ==

 Ben Pfaff: An Introduction to Binary Search Trees and Balanced Trees. (PDF; 1675 kB) 2004.
Binary Search Tree Visualization

*(note truncated for size; full article at the source link below)*

## Related

- [[AVL tree]]
- [[Red–black tree]]
- [[Binary space partitioning]]
- [[Binary tree]]
- [[Search tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Binary_search_tree