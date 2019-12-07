### Algorithms & Data Structures in C++

[![Build Status][1]][2]

[1]: https://travis-ci.org/vaishnav67/algorithms.svg?branch=master

### This is forked from xtaci's repo.

#### Goal:

   1. Classical algorithms implementations.
   2. Based on linux/gcc.
   3. Correct, ease of use and usage of one header file per algorithm.     

#### Convention:

   1.  1 header file per algorithm.
   2.  1 demo per algorithm.
   3.  TAB = 4 space.  set ts=4 in vim
   4.  The output format of the graph is in dot of [Graphviz](http://www.graphviz.org/).org
   	 eg:
   	 ![demograph](demo_graph.png)

#### Implemented:

| Name | File |
|------|------|
|Array shuffle|https://github.com/vaishnav67/algorithms/blob/master/include/shuffle.h |
|Prime test(trial division)|https://github.com/vaishnav67/algorithms/blob/master/include/prime.h|
|Prime test(Miller-Rabin's method)|https://github.com/vaishnav67/algorithms/blob/master/include/prime.h|
|2D Array|https://github.com/vaishnav67/algorithms/blob/master/include/2darray.h|
|Arbitrary Integer|https://github.com/vaishnav67/algorithms/blob/master/include/integer.h|
|Linear congruential generator|https://github.com/vaishnav67/algorithms/blob/master/include/random.h|
|Maximum subarray problem|https://github.com/vaishnav67/algorithms/blob/master/include/max_subarray.h|
|Bit-Set|https://github.com/vaishnav67/algorithms/blob/master/include/bitset.h|
|Queue|https://github.com/vaishnav67/algorithms/blob/master/include/queue.h|
|Stack|https://github.com/vaishnav67/algorithms/blob/master/include/stack.h|
|Binary Heap|https://github.com/vaishnav67/algorithms/blob/master/include/heap.h|
|Fibonacci Heap|https://github.com/vaishnav67/algorithms/blob/master/include/fib-heap.h|
|Priority Queue (list based)|https://github.com/vaishnav67/algorithms/blob/master/include/priority_queue.h|
|Bubble sort|https://github.com/vaishnav67/algorithms/blob/master/include/bubble_sort.h|
|Selection sort|https://github.com/vaishnav67/algorithms/blob/master/include/selection_sort.h|
|Insertion sort|https://github.com/vaishnav67/algorithms/blob/master/include/insertion_sort.h|
|Shell sort|https://github.com/vaishnav67/algorithms/blob/master/include/shell_sort.h|
|Radix sort|https://github.com/vaishnav67/algorithms/blob/master/include/radix_sort.h|
|Quicksort|https://github.com/vaishnav67/algorithms/blob/master/include/quick_sort.h|
|Merge sort|https://github.com/vaishnav67/algorithms/blob/master/include/merge_sort.h|
|Double linked list|https://github.com/vaishnav67/algorithms/blob/master/include/double_linked_list.h|
|Skip list|https://github.com/vaishnav67/algorithms/blob/master/include/skiplist.h|
|Largest common sequence|https://github.com/vaishnav67/algorithms/blob/master/include/lcs.h|
|Binary search tree|https://github.com/vaishnav67/algorithms/blob/master/include/binary_search_tree.h|
|AVL tree|https://github.com/vaishnav67/algorithms/blob/master/include/avl.h|
|Dynamic order statistics|https://github.com/vaishnav67/algorithms/blob/master/include/dos_tree.h|
|Red-black tree|https://github.com/vaishnav67/algorithms/blob/master/include/rbtree.h|
|Interval tree|https://github.com/vaishnav67/algorithms/blob/master/include/interval_tree.h|
|Prefix Tree(Trie)|https://github.com/vaishnav67/algorithms/blob/master/include/trie.h|
|Suffix Tree|https://github.com/vaishnav67/algorithms/blob/master/include/suffix_tree.h|
|B-Tree|https://github.com/vaishnav67/algorithms/blob/master/include/btree.h|
|Suffix Array|https://github.com/vaishnav67/algorithms/blob/master/include/suffix_array.h|
|Hash by multiplication|https://github.com/vaishnav67/algorithms/blob/master/include/hash_multi.h|
|Hash table|https://github.com/vaishnav67/algorithms/blob/master/include/hash_table.h|
|Universal hash function|https://github.com/vaishnav67/algorithms/blob/master/include/universal_hash.h|
|Perfect hash|https://github.com/vaishnav67/algorithms/blob/master/include/perfect_hash.h|
|Java's string hash|https://github.com/vaishnav67/algorithms/blob/master/include/hash_string.h|
|FNV-1a string hash|https://github.com/vaishnav67/algorithms/blob/master/include/hash_string.h|
|SimHash|https://github.com/vaishnav67/algorithms/blob/master/include/simhash.h|
|Bloom Filter|https://github.com/vaishnav67/algorithms/blob/master/include/bloom_filter.h|
|SHA-1 Message Digest Algorithm|https://github.com/vaishnav67/algorithms/blob/master/include/sha1.h|
|MD5|https://github.com/vaishnav67/algorithms/blob/master/include/md5.h|
|Base64|https://github.com/vaishnav67/algorithms/blob/master/include/base64.h|
|Strongly Connected Components(SCC)|https://github.com/vaishnav67/algorithms/blob/master/include/scc.h|
|Prim's minimum spanning tree|https://github.com/vaishnav67/algorithms/blob/master/include/prim_mst.h|
|Kruskal MST|https://github.com/vaishnav67/algorithms/blob/master/include/kruskal_mst.h|
|Breadth First Search|https://github.com/vaishnav67/algorithms/blob/master/include/graph_search.h|
|Depth First Search|https://github.com/vaishnav67/algorithms/blob/master/include/graph_search.h|
|Dijkstra's algorithm|https://github.com/vaishnav67/algorithms/blob/master/include/dijkstra.h|
|Bellman-Ford algorithm|https://github.com/vaishnav67/algorithms/blob/master/include/bellman_ford.h|
|Edmonds-Karp Maximal Flow|https://github.com/vaishnav67/algorithms/blob/master/include/edmonds_karp.h|
|Push–Relabel algorithm|https://github.com/vaishnav67/algorithms/blob/master/include/relabel_to_front.h|
|Huffman Coding|https://github.com/vaishnav67/algorithms/blob/master/include/huffman.h|
|Word segementation|https://github.com/vaishnav67/algorithms/blob/master/include/word_seg.h|
|A\* algorithm|https://github.com/vaishnav67/algorithms/blob/master/include/astar.h|
|K-Means|https://github.com/vaishnav67/algorithms/blob/master/include/k-means.h|
|Knuth–Morris–Pratt algorithm|https://github.com/vaishnav67/algorithms/blob/master/include/kmp.h|
|Disjoint-Set|https://github.com/vaishnav67/algorithms/blob/master/include/disjoint-set.h|
|8-Queue Problem|https://github.com/vaishnav67/algorithms/blob/master/include/8queen.h|
|Palindrome|https://github.com/vaishnav67/algorithms/blob/master/include/palindrome.h|
|LCA using Binary Lifting|https://github.com/vaishnav67/algorithms/blob/master/include/LCA.h|
