![dsa roadmap](https://github.com/user-attachments/assets/7a083dae-0e0d-4fa7-a566-005569258345)
<p align="center">
  <img src="https://github.com/user-attachments/assets/de3a9a26-fafa-4ddf-b276-af74bf8614ac" alt="DSA Roadmap" width="90%">
</p>




This repository contains **detailed, concept-oriented theory notes and leetcode problems** on **Data Structures and Algorithms (DSA)**.  
The goal is to explain **every concept clearly**, from **basic to advanced**, with **proper definitions, types, explanations, and complexities**, all in **one single file**.

This is ideal for:
- Beginners learning DSA from scratch
- Students preparing for placements and interviews
- Anyone revising core Computer Science fundamentals

---

## 🎯 Recommended Learning Resources

You may follow any one DSA playlist along with these notes:
## 📚 Best DSA Playlists (Choose Any One)

1.) **Striver's A2Z DSA Course / Playlist**  
👉 [Striver's A2Z DSA Course / Playlist](https://youtube.com/playlist?list=PLgUwDviBIf0oF6QL8m22w1hIDC1vJ_BHz&si=MTF_66tGoeIcGMFc)

2.) **Kunal Kushwaha's DSA Playlist (Java)**  
👉 [Kunal Kushwaha's DSA Playlist](https://youtube.com/playlist?list=PL9gnSGHSqcnr_DxHsP7AW9ftq0AtAyYqJ&si=49OSFypplevYrlU_)

3.) **Love Babbar's DSA Playlist (C++)**  
👉 [Love Babbar's DSA Playlist](https://youtube.com/playlist?list=PLDzeHZWIZsTryvtXdMr6rPh4IDexB5NIA&si=zwfnuxgTzmerU0KH)

4.) **Apna College / Apni Kaksha DSA Playlist (C++ & Java)**  
👉 [Apna College / Apni Kaksha Playlist](https://youtube.com/playlist?list=PLfqMhTWNBTe137I_EPQd34TsgV6IO55pt&si=4lU4XmjLpF-8sIFy)


---

# 🧱 PART 1: LINEAR DATA STRUCTURES

---

## 📌 Arrays

### What is an Array?

An **array** is a linear data structure that stores elements of the **same data type** in **contiguous memory locations**.  
Each element is accessed using an **index**, allowing fast and direct access.

---

### Why Arrays Are Used?

Arrays are widely used because they:
- Provide **O(1)** access time using indices
- Use memory efficiently due to contiguous allocation
- Are easy to traverse, search, and sort
- Act as a base for many advanced data structures

---

### Types of Arrays

- **One-Dimensional Array** – Stores elements in a single linear sequence  
- **Multi-Dimensional Array** – Stores data in the form of rows and columns (e.g., matrices)  
- **Dynamic Array** – Automatically resizes during runtime to handle variable data size  

---

### Array Operations & Complexity

| Operation  | Time Complexity |
|----------|----------------|
| Access   | O(1)           |
| Search   | O(n)           |
| Insert   | O(n)           |
| Delete   | O(n)           |

---

## 📌 Linked List

### What is a Linked List?

A **linked list** is a linear data structure where elements are stored in **nodes**, and each node contains:
- **Data** – the actual value
- **Pointer** – reference to the next node

Unlike arrays, linked lists do not require contiguous memory.

---

### Why Linked Lists Are Used?

Linked lists are preferred when:
- Dynamic memory allocation is needed
- Frequent insertions and deletions are required
- Memory wastage due to fixed size arrays must be avoided

---

### Types of Linked Lists

- **Singly Linked List** – Each node points only to the next node  
- **Doubly Linked List** – Each node points to both previous and next nodes  
- **Circular Linked List** – The last node points back to the first node  

---

### Linked List Complexity

| Operation  | Time Complexity |
|----------|----------------|
| Access   | O(n)           |
| Insert   | O(1)*          |
| Delete   | O(1)*          |

\* When the node reference is already known.

---

## 📌 Stack

### What is a Stack?

A **stack** is a linear data structure that follows the **Last In, First Out (LIFO)** principle, meaning the most recently added element is removed first.

---

### Stack Operations

- **Push** – Adds an element to the top  
- **Pop** – Removes the top element  
- **Peek** – Returns the top element without removing it  
- **isEmpty** – Checks whether the stack is empty  

---

### Applications of Stack

Stacks are commonly used in:
- Function call management
- Expression evaluation
- Undo/Redo operations
- Syntax parsing

---

### Stack Complexity

| Operation | Time |
|---------|------|
| Push    | O(1) |
| Pop     | O(1) |

---

## 📌 Queue

### What is a Queue?

A **queue** is a linear data structure that follows the **First In, First Out (FIFO)** principle, where the first inserted element is removed first.

---

### Types of Queues

- **Simple Queue** – Insertion at rear and deletion from front  
- **Circular Queue** – Last position connects back to the first to optimize space  
- **Priority Queue** – Elements are processed based on priority  
- **Deque** – Insertion and deletion are allowed at both ends  

---

### Applications of Queue

Queues are used in:
- CPU scheduling
- Breadth First Search (BFS)
- Request handling systems

---

### Queue Complexity

| Operation | Time |
|---------|------|
| Enqueue | O(1) |
| Dequeue | O(1) |

---

# 🌳 PART 2: NON-LINEAR DATA STRUCTURES

---

## 🌲 Tree Data Structure

### What is a Tree?

A **tree** is a non-linear hierarchical data structure consisting of nodes connected by edges.  
It starts from a **root node** and branches into child nodes, forming a structure similar to an inverted tree.

There exists **only one path** between any two nodes.

---

### Tree Terminology

- **Root** – Topmost node  
- **Parent** – Node having children  
- **Child** – Node derived from parent  
- **Leaf** – Node with no children  
- **Height** – Longest path from root to leaf  

---

### Types of Trees

- **Binary Tree** – Each node has at most two children  
- **Binary Search Tree (BST)** – Left subtree contains smaller values, right contains larger  
- **Complete Binary Tree** – All levels filled except possibly the last, filled left to right  
- **Perfect Binary Tree** – All internal nodes have two children and all leaves are at same level  
- **N-ary Tree** – Each node can have at most N children  

---

### Tree Complexity (Balanced BST)

| Operation | Time |
|---------|------|
| Search  | O(log n) |
| Insert  | O(log n) |

---

## 🌐 Graph Data Structure

### What is a Graph?

A **graph** is a non-linear data structure consisting of a set of **vertices (nodes)** and **edges** that connect pairs of vertices.

Unlike trees, graphs:
- Do not have a root node
- Can contain cycles
- Can have multiple paths between nodes

---

### Types of Graphs

- **Directed Graph** – Edges have a direction  
- **Undirected Graph** – Edges have no direction  
- **Weighted Graph** – Edges carry weights or costs  
- **Unweighted Graph** – All edges have equal weight  
- **Cyclic Graph** – Contains at least one cycle  
- **Acyclic Graph** – Does not contain cycles  
- **Connected Graph** – Every node is reachable from another  
- **Disconnected Graph** – Some nodes are isolated  

---

### Graph Traversal Techniques

- **Breadth First Search (BFS)** – Explores nodes level by level using a queue  
- **Depth First Search (DFS)** – Explores deeply before backtracking using recursion or stack  

---

### Important Graph Concepts

- Cycle Detection – Identifying loops in graphs  
- Topological Sorting – Linear ordering of nodes in a DAG  
- Minimum Spanning Tree – Connecting all nodes with minimum edge weight  
- Shortest Path Algorithms – Finding minimum distance between nodes  
- Strongly Connected Components – Groups of mutually reachable nodes  

---

# ⚙️ PART 3: ALGORITHMS

---

## 🔍 Searching Algorithms

### Linear Search

Linear search checks elements one by one until the target element is found.

- Best Case: O(1)
- Worst Case: O(n)
- Space Complexity: O(1)

---

### Binary Search

Binary search works on **sorted data** by repeatedly dividing the search space in half.

- Best Case: O(1)
- Worst Case: O(log n)
- Space Complexity: O(1)

---

## 🔃 Sorting Algorithms

### Bubble Sort
Repeatedly swaps adjacent elements if they are in the wrong order.

- Best Case: O(n)
- Worst Case: O(n²)
- Space Complexity: O(1)

---

### Selection Sort
Selects the minimum element and places it in the correct position.

- Time Complexity: O(n²)
- Space Complexity: O(1)

---

### Insertion Sort
Builds the sorted array one element at a time.

- Best Case: O(n)
- Worst Case: O(n²)
- Space Complexity: O(1)

---

### Merge Sort
Divides the array, sorts subarrays, and merges them.

- Time Complexity: O(n log n)
- Space Complexity: O(n)

---

### Quick Sort
Partitions the array using a pivot element.

- Average Case: O(n log n)
- Worst Case: O(n²)
- Space Complexity: O(n)

---

## 🔁 Recursion

Recursion is a technique where a function calls itself to solve a problem by reducing it to smaller subproblems.

It consists of:
- **Base Case** – Stops recursion
- **Recursive Case** – Function calls itself
- **Call Stack** – Stores function calls

---

## 🔙 Backtracking

Backtracking is a recursive technique that explores all possible solutions and reverses decisions when constraints are violated.

It is used in:
- Constraint satisfaction problems
- Decision-based algorithms
- Optimization problems

---

## 🧠 Dynamic Programming

Dynamic Programming is an optimization technique that reduces time complexity by storing results of overlapping subproblems.

---

### Core Properties of DP

- **Optimal Substructure** – Optimal solution depends on optimal subproblems  
- **Overlapping Subproblems** – Same subproblems are solved repeatedly  

---

### DP Approaches

- **Memoization (Top-Down)** – Uses recursion with caching  
- **Tabulation (Bottom-Up)** – Builds solution iteratively from base cases  

---

## 🚀 Final Words

Mastering **DSA theory** builds the foundation for:
- Writing efficient code
- Cracking interviews
- Understanding system design


# 📕 Advanced Data Structures & Algorithms – Complete Theory

This document contains **advanced and supporting DSA concepts** that complement the main README.  
Together, both files form a **complete DSA theory reference** from **basic → advanced**, suitable for interviews, academics, and real-world understanding.

---

# 🧩 MATHEMATICAL & FOUNDATIONAL CONCEPTS

---

## 📌 Time Complexity Analysis

### What is Time Complexity?
Time complexity describes how the **execution time of an algorithm grows** with respect to input size `n`.

### Common Time Complexities
- **O(1)** – Constant time, independent of input size  
- **O(log n)** – Logarithmic growth, common in divide & conquer  
- **O(n)** – Linear growth  
- **O(n log n)** – Efficient sorting algorithms  
- **O(n²)** – Nested loops  
- **O(2ⁿ)** – Exponential, brute force  
- **O(n!)** – Factorial, permutation-based algorithms  

---

## 📌 Space Complexity

### What is Space Complexity?
Space complexity measures the **extra memory** used by an algorithm besides input storage.

### Types
- **Auxiliary Space** – Extra space used by algorithm  
- **Input Space** – Space taken by input itself  

---

## 📌 Asymptotic Notations

- **Big-O (O)** – Upper bound (worst case)  
- **Omega (Ω)** – Lower bound (best case)  
- **Theta (Θ)** – Tight bound (average/exact growth)  

---

# 🧠 ADVANCED DATA STRUCTURES

---

## 📌 Heap

### What is a Heap?
A **heap** is a specialized complete binary tree used for **priority-based processing**.

### Types of Heap
- **Min Heap** – Parent node is smaller than its children  
- **Max Heap** – Parent node is greater than its children  

### Applications
- Priority Queue
- Scheduling
- Heap Sort
- Dijkstra’s Algorithm

### Time Complexity
- Insert: O(log n)
- Delete: O(log n)
- Get Min/Max: O(1)

---

## 📌 Hashing & Hash Tables

### What is Hashing?
Hashing maps data to a fixed-size value using a **hash function**, enabling fast access.

### Hash Table
A data structure that stores key–value pairs using hashing.

### Collision Handling Techniques
- **Chaining** – Store multiple elements at same index  
- **Open Addressing** – Find next empty slot  

### Complexity
- Average Case: O(1)
- Worst Case: O(n)

---

## 📌 Trie (Prefix Tree)

### What is a Trie?
A **Trie** is a tree-based structure used for storing strings efficiently using prefixes.

### Characteristics
- Each node represents a character
- Paths represent words

### Applications
- Autocomplete
- Spell checking
- Dictionary implementation

### Complexity
- Insert/Search: O(length of word)

---

## 📌 Disjoint Set Union (DSU)

### What is DSU?
DSU is a data structure that keeps track of elements partitioned into **disjoint sets**.

### Operations
- **Find** – Identify set representative  
- **Union** – Merge two sets  

### Optimizations
- Path Compression
- Union by Rank

### Application
- Cycle detection
- Kruskal’s Algorithm

---

# 🌐 ADVANCED GRAPH CONCEPTS

---

## 📌 Shortest Path Algorithms

- **Dijkstra’s Algorithm** – Finds shortest path in weighted graph without negative edges  
- **Bellman-Ford Algorithm** – Handles negative edge weights  
- **Floyd-Warshall Algorithm** – All-pairs shortest paths  

---

## 📌 Minimum Spanning Tree (MST)

### What is MST?
A subset of edges connecting all vertices with **minimum total weight**.

### Algorithms
- **Prim’s Algorithm** – Grows MST from a starting node  
- **Kruskal’s Algorithm** – Selects edges by increasing weight  

---

## 📌 Graph Properties

- **Articulation Point** – Node whose removal increases components  
- **Bridge** – Edge whose removal disconnects graph  
- **Euler Path** – Path visiting every edge exactly once  
- **Euler Circuit** – Euler path that starts and ends at same node  

---

# 🧮 ALGORITHMIC PARADIGMS

---

## 📌 Divide and Conquer

### Definition
Breaks problem into smaller subproblems, solves them independently, and combines results.

### Examples
- Merge Sort
- Quick Sort
- Binary Search

---

## 📌 Greedy Algorithms

### Definition
Makes the **locally optimal choice** at each step.

### Characteristics
- Fast
- Not always optimal globally

### Applications
- Activity Selection
- Huffman Encoding
- MST Algorithms

---

## 📌 Sliding Window Technique

### Definition
Maintains a window over input to reduce nested loops.

### Types
- Fixed Window – Constant size  
- Variable Window – Expands and shrinks dynamically  

---

## 📌 Two Pointer Technique

### Definition
Uses two indices to traverse data efficiently.

### Common Uses
- Sorted arrays
- Pair problems
- Palindrome checking

---

## 📌 Prefix Sum Technique

### Definition
Precomputes cumulative sums to answer range queries efficiently.

### Benefit
Reduces repeated computation.

---

# 🧠 ADVANCED DYNAMIC PROGRAMMING CONCEPTS

---

## 📌 DP State Design

Defines:
- What to store
- Dimensions of DP table
- Transition rules

---

## 📌 Bitmasking in DP

### What is Bitmask DP?
Uses bits to represent subsets and states efficiently.

### Applications
- Subset problems
- Traveling Salesman Problem
- State compression

---

## 📌 Optimization Techniques

- Space Optimization
- Rolling Arrays
- State Compression

---

# 🔐 STRING ALGORITHMS

---

## 📌 String Matching Algorithms

- **Naive String Matching** – Brute force approach  
- **KMP Algorithm** – Uses prefix table for efficiency  
- **Rabin-Karp Algorithm** – Uses hashing  
- **Z Algorithm** – Pattern matching using Z-array  

---

## 📌 Palindrome Techniques

- Expand Around Center
- Manacher’s Algorithm

---

# 🧠 FINAL NOTES

With this file and the main README combined, you now have:

✔ Complete DSA theory  
✔ Beginner → Advanced coverage  
✔ Interview-ready concepts  
✔ Clean, readable documentation  



⭐ If this repository helped you, consider starring it and sharing it with others.

# LeetCode-Topic-wise-Problems to Crack any interviews.

## 🧠 Hashing Problems ---

### 🟢 Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1 | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy |
| 2 | [Jewels and Stones](https://leetcode.com/problems/jewels-and-stones/) | Easy |
| 3 | [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Easy |
| 4 | [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy |
| 5 | [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Easy |
| 6 | [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy |
| 7 | [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Easy |
| 8 | [Happy Number](https://leetcode.com/problems/happy-number/) | Easy |
| 9 | [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/) | Easy |
| 10 | [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Easy |
| 11 | [Majority Element](https://leetcode.com/problems/majority-element/) | Easy |
| 12 | [Find the Difference](https://leetcode.com/problems/find-the-difference/) | Easy |
| 13 | [Ransom Note](https://leetcode.com/problems/ransom-note/) | Easy |
| 14 | [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | Easy |
| 15 | [Check if Two String Arrays are Equivalent](https://leetcode.com/problems/check-if-two-string-arrays-are-equivalent/) | Easy |
| 16 | [Determine if Two Strings Are Close](https://leetcode.com/problems/determine-if-two-strings-are-close/) | Easy |
| 17 | [Unique Number of Occurrences](https://leetcode.com/problems/unique-number-of-occurrences/) | Easy |
| 18 | [Longest Harmonious Subsequence](https://leetcode.com/problems/longest-harmonious-subsequence/) | Easy |
| 19 | [Count Common Words With One Occurrence](https://leetcode.com/problems/count-common-words-with-one-occurrence/) | Easy |
| 20 | [Set Mismatch](https://leetcode.com/problems/set-mismatch/) | Easy |
| 21 | [Keyboard Row](https://leetcode.com/problems/keyboard-row/) | Easy |
| 22 | [Count the Number of Consistent Strings](https://leetcode.com/problems/count-the-number-of-consistent-strings/) | Easy |
| 23 | [Word Pattern](https://leetcode.com/problems/word-pattern/) | Easy |
| 24 | [Sum of Unique Elements](https://leetcode.com/problems/sum-of-unique-elements/) | Easy |
| 25 | [Find Common Characters](https://leetcode.com/problems/find-common-characters/) | Easy |
| 26 | [Max Number of Words You Can Type](https://leetcode.com/problems/maximum-number-of-words-you-can-type/) | Easy |
| 27 | [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Easy |
| 28 | [Most Common Word](https://leetcode.com/problems/most-common-word/) | Easy |
| 29 | [Check if Every Letter Appears Once](https://leetcode.com/problems/check-if-every-letter-appears-once/) | Easy |
| 30 | [Check if Word Equals Summation of Two Words](https://leetcode.com/problems/check-if-word-equals-summation-of-two-words/) | Easy |

---

### 🟡 Medium.

| NO | Problem | Difficulty |
|----|---------|------------|
| 1 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 2 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium |
| 3 | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium |
| 4 | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Medium |
| 5 | [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium |
| 6 | [Group Shifted Strings](https://leetcode.com/problems/group-shifted-strings/) | Medium |
| 7 | [Minimum Index Sum of Two Lists](https://leetcode.com/problems/minimum-index-sum-of-two-lists/) | Medium |
| 8 | [Contiguous Array](https://leetcode.com/problems/contiguous-array/) | Medium |
| 9 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 10 | [Find Duplicate Subtrees](https://leetcode.com/problems/find-duplicate-subtrees/) | Medium |
| 11 | [Equal Row and Column Pairs](https://leetcode.com/problems/equal-row-and-column-pairs/) | Medium |
| 12 | [Largest Substring Between Two Equal Characters](https://leetcode.com/problems/largest-substring-between-two-equal-characters/) | Medium |
| 13 | [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | Medium |
| 14 | [Index Pairs of a String](https://leetcode.com/problems/index-pairs-of-a-string/) | Medium |
| 15 | [Count Nice Pairs in an Array](https://leetcode.com/problems/count-nice-pairs-in-an-array/) | Medium |
| 16 | [Replace Words](https://leetcode.com/problems/replace-words/) | Medium |
| 17 | [Maximum Equal Frequency](https://leetcode.com/problems/maximum-equal-frequency/) | Medium |
| 18 | [Number of Good Pairs](https://leetcode.com/problems/number-of-good-pairs/) | Medium |
| 19 | [Minimum Operations to Reduce X to Zero](https://leetcode.com/problems/minimum-operations-to-reduce-x-to-zero/) | Medium |
| 20 | [Find the Most Competitive Subsequence](https://leetcode.com/problems/find-the-most-competitive-subsequence/) | Medium |
| 21 | [Max Number of K-Sum Pairs](https://leetcode.com/problems/max-number-of-k-sum-pairs/) | Medium |
| 22 | [Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium |
| 23 | [Number of Submatrices That Sum to Target](https://leetcode.com/problems/number-of-submatrices-that-sum-to-target/) | Medium |
| 24 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Medium |
| 25 | [Path Crossing](https://leetcode.com/problems/path-crossing/) | Medium |
| 26 | [Number of Boomerangs](https://leetcode.com/problems/number-of-boomerangs/) | Medium |
| 27 | [Diagonal Traverse II](https://leetcode.com/problems/diagonal-traverse-ii/) | Medium |
| 28 | [Find K-Length Substrings With No Repeated Characters](https://leetcode.com/problems/find-k-length-substrings-with-no-repeated-characters/) | Medium |
| 29 | [Most Frequent Even Element](https://leetcode.com/problems/most-frequent-even-element/) | Medium |
| 30 | [Find All Groups of Farmland](https://leetcode.com/problems/find-all-groups-of-farmland/) | Medium |

---

### 🔴 Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard |
| 2 | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard |
| 3 | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Hard |
| 4 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 5 | [Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Hard |
| 6 | [Count Different Palindromic Subsequences](https://leetcode.com/problems/count-different-palindromic-subsequences/) | Hard |
| 7 | [Substring with Largest Variance](https://leetcode.com/problems/substring-with-largest-variance/) | Hard |
| 8 | [Concatenated Words](https://leetcode.com/problems/concatenated-words/) | Hard |
| 9 | [Smallest Rectangle Enclosing Black Pixels](https://leetcode.com/problems/smallest-rectangle-enclosing-black-pixels/) | Hard |
| 10 | [Number of Valid Words for Each Puzzle](https://leetcode.com/problems/number-of-valid-words-for-each-puzzle/) | Hard |
| 11 | [Minimum Incompatibility](https://leetcode.com/problems/minimum-incompatibility/) | Hard |
| 12 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 13 | [Split Array into Consecutive Subsequences](https://leetcode.com/problems/split-array-into-consecutive-subsequences/) | Hard |
| 14 | [Smallest String With Swaps](https://leetcode.com/problems/smallest-string-with-swaps/) | Hard |
| 15 | [Avoid Flood in The City](https://leetcode.com/problems/avoid-flood-in-the-city/) | Hard |
| 16 | [Form Array by Concatenating Subarrays of Another Array](https://leetcode.com/problems/form-array-by-concatenating-subarrays-of-another-array/) | Hard |
| 17 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 18 | [Max Sum of Rectangle No Larger Than K](https://leetcode.com/problems/max-sum-of-rectangle-no-larger-than-k/) | Hard |
| 19 | [Maximize Score After N Operations](https://leetcode.com/problems/maximize-score-after-n-operations/) | Hard |
| 20 | [Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard |
| 21 | [Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Hard |
| 22 | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 23 | [Strobogrammatic Number III](https://leetcode.com/problems/strobogrammatic-number-iii/) | Hard |
| 24 | [Minimize Malware Spread II](https://leetcode.com/problems/minimize-malware-spread-ii/) | Hard |
| 25 | [Parallel Courses III](https://leetcode.com/problems/parallel-courses-iii/) | Hard |
| 26 | [Design Search Autocomplete System](https://leetcode.com/problems/design-search-autocomplete-system/) | Hard |
| 27 | [Student Attendance Record II](https://leetcode.com/problems/student-attendance-record-ii/) | Hard |
| 28 | [Strange Printer](https://leetcode.com/problems/strange-printer/) | Hard |
| 29 | [Minimum Genetic Mutation](https://leetcode.com/problems/minimum-genetic-mutation/) | Hard |
| 30 | [Word Squares](https://leetcode.com/problems/word-squares/) | Hard |

---


## Arrays 

### 🟢 Easy

| No. | Problem | Difficulty | 
|-----|---------|------------|
| 1 | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy |
| 2 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | 
| 3 | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy |
| 4 | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Easy |
| 5 | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy |
| 6 | [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Easy |
| 7 | [Single Number](https://leetcode.com/problems/single-number/) | Easy |
| 8 | [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy |
| 9 | [Plus One](https://leetcode.com/problems/plus-one/) | Easy |
| 10 | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy |
| 11 | [Rotate Array](https://leetcode.com/problems/rotate-array/) | Easy |
| 12 | [Find the Difference](https://leetcode.com/problems/find-the-difference/) | Easy |
| 13 | [Maximum Product of Two Elements in an Array](https://leetcode.com/problems/maximum-product-of-two-elements-in-an-array/) | Easy |
| 14 | [Build Array from Permutation](https://leetcode.com/problems/build-array-from-permutation/) | Easy |
| 15 | [Concatenation of Array](https://leetcode.com/problems/concatenation-of-array/) | Easy |
| 16 | [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | Easy |
| 17 | [Richest Customer Wealth](https://leetcode.com/problems/richest-customer-wealth/) | Easy |
| 18 | [Shuffle the Array](https://leetcode.com/problems/shuffle-the-array/) | Easy |
| 19 | [Kids With the Greatest Number of Candies](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/) | Easy |
| 20 | [How Many Numbers Are Smaller Than the Current Number](https://leetcode.com/problems/how-many-numbers-are-smaller-than-the-current-number/) | Easy |
| 21 | [Smaller Numbers Than Current](https://leetcode.com/problems/how-many-numbers-are-smaller-than-the-current-number/) | Easy |
| 22 | [Create Target Array in the Given Order](https://leetcode.com/problems/create-target-array-in-the-given-order/) | Easy |
| 23 | [Check If N and Its Double Exist](https://leetcode.com/problems/check-if-n-and-its-double-exist/) | Easy |
| 24 | [Replace Elements with Greatest Element on Right Side](https://leetcode.com/problems/replace-elements-with-greatest-element-on-right-side/) | Easy |
| 25 | [Remove Element](https://leetcode.com/problems/remove-element/) | Easy |
| 26 | [Valid Mountain Array](https://leetcode.com/problems/valid-mountain-array/) | Easy |
| 27 | [Third Maximum Number](https://leetcode.com/problems/third-maximum-number/) | Easy |
| 28 | [Missing Number](https://leetcode.com/problems/missing-number/) | Easy |
| 29 | [Find Numbers with Even Number of Digits](https://leetcode.com/problems/find-numbers-with-even-number-of-digits/) | Easy |
| 30 | [Check if Array Is Sorted and Rotated](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/) | Easy |

---

### 🟡 Medium

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [3Sum](https://leetcode.com/problems/3sum/) | Medium |
| 2 | [Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/) | Medium |
| 3 | [Rotate Image](https://leetcode.com/problems/rotate-image/) | Medium |
| 4 | [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | Medium |
| 5 | [Jump Game](https://leetcode.com/problems/jump-game/) | Medium |
| 6 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium |
| 7 | [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium |
| 8 | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium |
| 9 | [Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium |
| 10 | [Majority Element II](https://leetcode.com/problems/majority-element-ii/) | Medium |
| 11 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 12 | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium |
| 13 | [Next Permutation](https://leetcode.com/problems/next-permutation/) | Medium |
| 14 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Medium |
| 15 | [Find All Duplicates in an Array](https://leetcode.com/problems/find-all-duplicates-in-an-array/) | Medium |
| 16 | [Missing Ranges](https://leetcode.com/problems/missing-ranges/) | Medium |
| 17 | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Medium |
| 18 | [Minimum Operations to Reduce X to Zero](https://leetcode.com/problems/minimum-operations-to-reduce-x-to-zero/) | Medium |
| 19 | [Longest Subarray of 1's After Deleting One Element](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element/) | Medium |
| 20 | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium |
| 21 | [Wiggle Sort II](https://leetcode.com/problems/wiggle-sort-ii/) | Medium |
| 22 | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Medium |
| 23 | [Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/) | Medium |
| 24 | [Maximum Length of Repeated Subarray](https://leetcode.com/problems/maximum-length-of-repeated-subarray/) | Medium |
| 25 | [Monotonic Array](https://leetcode.com/problems/monotonic-array/) | Medium |
| 26 | [Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium |
| 27 | [Wiggle Subsequence](https://leetcode.com/problems/wiggle-subsequence/) | Medium |
| 28 | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium |
| 29 | [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) | Medium |
| 30 | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |

---

### 🔴 Hard

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [First Missing Positive](https://leetcode.com/problems/first-missing-positive/) | Hard |
| 2 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard |
| 3 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Hard |
| 4 | [Insert Interval](https://leetcode.com/problems/insert-interval/) | Hard |
| 5 | [Maximum Gap](https://leetcode.com/problems/maximum-gap/) | Hard |
| 6 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 7 | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 8 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 9 | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 10 | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard |
| 11 | [Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/) | Hard |
| 12 | [Burst Balloons](https://leetcode.com/problems/burst-balloons/) | Hard |
| 13 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 14 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 15 | [Max Sum of Rectangle No Larger Than K](https://leetcode.com/problems/max-sum-of-rectangle-no-larger-than-k/) | Hard |
| 16 | [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard |
| 17 | [Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) | Hard |
| 18 | [Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) | Hard |
| 19 | [Number of Subsequences That Satisfy the Given Sum Condition](https://leetcode.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition/) | Hard |
| 20 | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Hard |
| 21 | [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard |
| 22 | [Race Car](https://leetcode.com/problems/race-car/) | Hard |
| 23 | [Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard |
| 24 | [Shortest Subarray with Sum at Least K](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) | Hard |
| 25 | [132 Pattern](https://leetcode.com/problems/132-pattern/) | Hard |
| 26 | [Find the Longest Valid Obstacle Course at Each Position](https://leetcode.com/problems/find-the-longest-valid-obstacle-course-at-each-position/) | Hard |
| 27 | [K Empty Slots](https://leetcode.com/problems/k-empty-slots/) | Hard |
| 28 | [Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard |
| 29 | [Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/) | Hard |
| 30 | [Longest Substring of All Vowels in Order](https://leetcode.com/problems/longest-substring-of-all-vowels-in-order/) | Hard |



## Strings

### 🟢 Easy

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy |
| 2 | [Reverse String](https://leetcode.com/problems/reverse-string/) | Easy |
| 3 | [Implement strStr()](https://leetcode.com/problems/implement-strstr/) | Easy |
| 4 | [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Easy |
| 5 | [To Lower Case](https://leetcode.com/problems/to-lower-case/) | Easy |
| 6 | [Check If Two String Arrays are Equivalent](https://leetcode.com/problems/check-if-two-string-arrays-are-equivalent/) | Easy |
| 7 | [Defanging an IP Address](https://leetcode.com/problems/defanging-an-ip-address/) | Easy |
| 8 | [Determine if String Halves Are Alike](https://leetcode.com/problems/determine-if-string-halves-are-alike/) | Easy |
| 9 | [Shuffle String](https://leetcode.com/problems/shuffle-string/) | Easy |
| 10 | [Goal Parser Interpretation](https://leetcode.com/problems/goal-parser-interpretation/) | Easy |
| 11 | [Number of Segments in a String](https://leetcode.com/problems/number-of-segments-in-a-string/) | Easy |
| 12 | [Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/) | Easy |
| 13 | [Count and Say](https://leetcode.com/problems/count-and-say/) | Easy |
| 14 | [Length of Last Word](https://leetcode.com/problems/length-of-last-word/) | Easy |
| 15 | [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy |
| 16 | [Jewels and Stones](https://leetcode.com/problems/jewels-and-stones/) | Easy |
| 17 | [Replace All Digits with Characters](https://leetcode.com/problems/replace-all-digits-with-characters/) | Easy |
| 18 | [Final Value of Variable After Performing Operations](https://leetcode.com/problems/final-value-of-variable-after-performing-operations/) | Easy |
| 19 | [Sort String](https://leetcode.com/problems/sort-string/) | Easy |
| 20 | [Make The String Great](https://leetcode.com/problems/make-the-string-great/) | Easy |
| 21 | [Check if a Word Occurs As a Prefix](https://leetcode.com/problems/check-if-a-word-occurs-as-a-prefix-of-any-word-in-a-sentence/) | Easy |
| 22 | [Split a String in Balanced Strings](https://leetcode.com/problems/split-a-string-in-balanced-strings/) | Easy |
| 23 | [Truncate Sentence](https://leetcode.com/problems/truncate-sentence/) | Easy |
| 24 | [Max Words Found in Sentences](https://leetcode.com/problems/maximum-number-of-words-found-in-sentences/) | Easy |
| 25 | [Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately/) | Easy |
| 26 | [Binary String Has One Segment of Ones](https://leetcode.com/problems/check-if-binary-string-has-at-most-one-segment-of-ones/) | Easy |
| 27 | [Ransom Note](https://leetcode.com/problems/ransom-note/) | Easy |
| 28 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy |
| 29 | [Detect Capital](https://leetcode.com/problems/detect-capital/) | Easy |
| 30 | [Palindrome Number](https://leetcode.com/problems/palindrome-number/) | Easy |

---

### 🟡 Medium

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium |
| 2 | [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Medium |
| 3 | [Zigzag Conversion](https://leetcode.com/problems/zigzag-conversion/) | Medium |
| 4 | [Multiply Strings](https://leetcode.com/problems/multiply-strings/) | Medium |
| 5 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium |
| 6 | [String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/) | Medium |
| 7 | [Integer to Roman](https://leetcode.com/problems/integer-to-roman/) | Medium |
| 8 | [Roman to Integer](https://leetcode.com/problems/roman-to-integer/) | Medium |
| 9 | [Word Pattern](https://leetcode.com/problems/word-pattern/) | Medium |
| 10 | [Remove All Adjacent Duplicates in String II](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string-ii/) | Medium |
| 11 | [Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium |
| 12 | [Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) | Medium |
| 13 | [Decode String](https://leetcode.com/problems/decode-string/) | Medium |
| 14 | [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium |
| 15 | [Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) | Medium |
| 16 | [Valid Palindrome II](https://leetcode.com/problems/valid-palindrome-ii/) | Medium |
| 17 | [All Binary Codes of Size K](https://leetcode.com/problems/check-if-a-string-contains-all-binary-codes-of-size-k/) | Medium |
| 18 | [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) | Medium |
| 19 | [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium |
| 20 | [Repeated Substring Pattern](https://leetcode.com/problems/repeated-substring-pattern/) | Medium |
| 21 | [Flip String to Monotone Increasing](https://leetcode.com/problems/flip-string-to-monotone-increasing/) | Medium |
| 22 | [Next Greater Element III](https://leetcode.com/problems/next-greater-element-iii/) | Medium |
| 23 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Medium |
| 24 | [Custom Sort String](https://leetcode.com/problems/custom-sort-string/) | Medium |
| 25 | [Find and Replace Pattern](https://leetcode.com/problems/find-and-replace-pattern/) | Medium |
| 26 | [Buddy Strings](https://leetcode.com/problems/buddy-strings/) | Medium |
| 27 | [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) | Medium |
| 28 | [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/) | Medium |
| 29 | [Minimum Steps to Make Two Strings Anagram](https://leetcode.com/problems/minimum-number-of-steps-to-make-two-strings-anagram/) | Medium |
| 30 | [Design Add and Search Words Data Structure](https://leetcode.com/problems/add-and-search-word-data-structure-design/) | Medium |

---

### 🔴 Hard

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Edit Distance](https://leetcode.com/problems/edit-distance/) | Hard |
| 2 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard |
| 3 | [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |
| 4 | [Interleaving String](https://leetcode.com/problems/interleaving-string/) | Hard |
| 5 | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Hard |
| 6 | [Basic Calculator](https://leetcode.com/problems/basic-calculator/) | Hard |
| 7 | [Basic Calculator III](https://leetcode.com/problems/basic-calculator-iii/) | Hard |
| 8 | [Shortest Palindrome](https://leetcode.com/problems/shortest-palindrome/) | Hard |
| 9 | [Strong Password Checker](https://leetcode.com/problems/strong-password-checker/) | Hard |
| 10 | [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard |
| 11 | [Min Swaps to Make String Balanced](https://leetcode.com/problems/minimum-number-of-swaps-to-make-the-string-balanced/) | Hard |
| 12 | [Smallest Good Base](https://leetcode.com/problems/smallest-good-base/) | Hard |
| 13 | [The Number of Good Subsets](https://leetcode.com/problems/the-number-of-good-subsets/) | Hard |
| 14 | [Scramble String](https://leetcode.com/problems/scramble-string/) | Hard |
| 15 | [Count Different Palindromic Subsequences](https://leetcode.com/problems/count-different-palindromic-subsequences/) | Hard |
| 16 | [Max Unique Substrings](https://leetcode.com/problems/split-a-string-into-the-max-number-of-unique-substrings/) | Hard |
| 17 | [Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/) | Hard |
| 18 | [Parse Lisp Expression](https://leetcode.com/problems/parse-lisp-expression/) | Hard |
| 19 | [Remove Sub-Folders from Filesystem](https://leetcode.com/problems/remove-sub-folders-from-the-filesystem/) | Hard |
| 20 | [Min Difficulty of Job Schedule](https://leetcode.com/problems/minimum-difficulty-of-a-job-schedule/) | Hard |
| 21 | [Form Target String With Dictionary](https://leetcode.com/problems/number-of-ways-to-form-a-target-string-given-a-dictionary/) | Hard |
| 22 | [Lexicographically Smallest Equivalent String](https://leetcode.com/problems/lexicographically-smallest-equivalent-string/) | Hard |
| 23 | [Min Cost to Change Final Expression](https://leetcode.com/problems/minimum-cost-to-change-the-final-value-of-expression/) | Hard |
| 24 | [Chunked Palindrome Decomposition](https://leetcode.com/problems/longest-chunked-palindrome-decomposition/) | Hard |
| 25 | [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Hard |
| 26 | [Encoded String Matching](https://leetcode.com/problems/encoded-string-matching/) | Hard |
| 27 | [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Hard |
| 28 | [Brace Expansion II](https://leetcode.com/problems/brace-expansion-ii/) | Hard |
| 29 | [Matching Subsequences](https://leetcode.com/problems/number-of-matching-subsequences/) | Hard |
| 30 | [Search Autocomplete System](https://leetcode.com/problems/design-search-autocomplete-system/) | Hard |



## **Searching**

### 🟢 Easy
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Binary Search](https://leetcode.com/problems/binary-search/) | Easy |
| 2   | [Search Insert Position](https://leetcode.com/problems/search-insert-position/) | Easy |
| 3   | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy |
| 4   | [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Easy |
| 5   | [First Bad Version](https://leetcode.com/problems/first-bad-version/) | Easy |
| 6   | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy |
| 7   | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Easy |
| 8   | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 9   | [Sorted Array to Binary Search Tree](https://leetcode.com/problems/sorted-array-to-binary-search-tree/) | Easy |
| 10  | [Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square/) | Easy |
| 11  | [Majority Element](https://leetcode.com/problems/majority-element/) | Easy |
| 12  | [Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/) | Easy |
| 13  | [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) | Easy |
| 14  | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy |
| 15  | [Two Sum II - Input Array is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Easy |
| 16  | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Easy |
| 17  | [Happy Number](https://leetcode.com/problems/happy-number/) | Easy |
| 18  | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy |
| 19  | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy |
| 20  | [Binary Search on Answer](https://leetcode.com/problems/binary-search-on-answer/) | Easy |
| 21  | [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy |
| 22  | [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) | Easy |
| 23  | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Easy |
| 24  | [Plus One](https://leetcode.com/problems/plus-one/) | Easy |
| 25  | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy |
| 26  | [Remove Element](https://leetcode.com/problems/remove-element/) | Easy |
| 27  | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 28  | [Array Partition I](https://leetcode.com/problems/array-partition-i/) | Easy |
| 29  | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy |
| 30  | [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Easy |

---

### 🟡 Medium
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium |
| 2   | [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium |
| 3   | [Search 2D Matrix](https://leetcode.com/problems/search-2d-matrix/) | Medium |
| 4   | [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Medium |
| 5   | [Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium |
| 6   | [Find the Kth Smallest Element in an Array](https://leetcode.com/problems/find-the-kth-smallest-element-in-an-array/) | Medium |
| 7   | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 8   | [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium |
| 9   | [Binary Search Tree to Greater Sum Tree](https://leetcode.com/problems/binary-search-tree-to-greater-sum-tree/) | Medium |
| 10  | [Square Root of a Number](https://leetcode.com/problems/sqrtx/) | Medium |
| 11  | [Find the Missing Number](https://leetcode.com/problems/find-the-missing-number/) | Medium |
| 12  | [Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Medium |
| 13  | [Search for a Range](https://leetcode.com/problems/search-for-a-range/) | Medium |
| 14  | [Smallest Range I](https://leetcode.com/problems/smallest-range-i/) | Medium |
| 15  | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium |
| 16  | [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | Medium |
| 17  | [Binary Search on Answer](https://leetcode.com/problems/binary-search-on-answer/) | Medium |
| 18  | [Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/) | Medium |
| 19  | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium |
| 20  | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 21  | [Find the Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 22  | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 23  | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium |
| 24  | [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Medium |
| 25  | [Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium |
| 26  | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Medium |
| 27  | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Medium |
| 28  | [Wiggle Subsequence](https://leetcode.com/problems/wiggle-subsequence/) | Medium |
| 29  | [Combination Sum III](https://leetcode.com/problems/combination-sum-iii/) | Medium |
| 30  | [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium |
| 31  | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Medium |
| 32  | [Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/) | Medium |
| 33  | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Medium |

---

### 🔴 Hard
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 2   | [Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/) | Hard |
| 3   | [Maximum Value of K Coins From Piles](https://leetcode.com/problems/maximum-value-of-k-coins-from-piles/) | Hard |
| 4   | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 5   | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Hard |
| 6   | [Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Hard |
| 7   | [Longest Substring with At Most Two Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/) | Hard |
| 8   | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard |
| 9   | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 10  | [Find the Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Hard |
| 11  | [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Hard |
| 12  | [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Hard |
| 13  | [Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Hard |
| 14  | [Search in 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/) | Hard |
| 15  | [Maximum Subarray Sum with One Deletion](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/) | Hard |
| 16  | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Hard |
| 17  | [Median of Two Sorted Arrays II](https://leetcode.com/problems/median-of-two-sorted-arrays-ii/) | Hard |
| 18  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 19  | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 20  | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard |
| 21  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 22  | [Number of Longest Increasing Subsequence](https://leetcode.com/problems/number-of-longest-increasing-subsequence/) | Hard |
| 23  | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Hard |
| 24  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 25  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 26  | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 27  | [Smallest Range](https://leetcode.com/problems/smallest-range/) | Hard |
| 28  | [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard |
| 29  | [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Hard |
| 30  | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Hard |


## **Sorting**


### 🟢 Easy

| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Sort Colors](https://leetcode.com/problems/sort-colors/) | Easy |
| 2   | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy |
| 3   | [Sort Array By Parity](https://leetcode.com/problems/sort-array-by-parity/) | Easy |
| 4   | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy |
| 5   | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 6   | [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Easy |
| 7   | [Sort List](https://leetcode.com/problems/sort-list/) | Easy |
| 8   | [Largest Number](https://leetcode.com/problems/largest-number/) | Easy |
| 9   | [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Easy |
| 10  | [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy |
| 11  | [Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/) | Easy |
| 12  | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy |
| 13  | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Easy |
| 14  | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy |
| 15  | [Array Partition I](https://leetcode.com/problems/array-partition-i/) | Easy |
| 16  | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Easy |
| 17  | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy |
| 18  | [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | Easy |
| 19  | [Palindrome Permutation](https://leetcode.com/problems/palindrome-permutation/) | Easy |
| 20  | [Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Easy |
| 21  | [Single Number](https://leetcode.com/problems/single-number/) | Easy |
| 22  | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy |
| 23  | [Rotate Array](https://leetcode.com/problems/rotate-array/) | Easy |
| 24  | [Plus One](https://leetcode.com/problems/plus-one/) | Easy |
| 25  | [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) | Easy |
| 26  | [Search Insert Position](https://leetcode.com/problems/search-insert-position/) | Easy |
| 27  | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 28  | [Sort Array By Parity II](https://leetcode.com/problems/sort-array-by-parity-ii/) | Easy |
| 29  | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy |
| 30  | [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Easy |

---

### 🟡 Medium

| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 2   | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 3   | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Medium |
| 4   | [Sort List](https://leetcode.com/problems/sort-list/) | Medium |
| 5   | [Quick Sort](https://leetcode.com/problems/quick-sort/) | Medium |
| 6   | [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) | Medium |
| 7   | [Find the Kth Smallest Element in an Array](https://leetcode.com/problems/find-the-kth-smallest-element-in-an-array/) | Medium |
| 8   | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 9   | [Counting Elements](https://leetcode.com/problems/counting-elements/) | Medium |
| 10  | [H-Index II](https://leetcode.com/problems/h-index-ii/) | Medium |
| 11  | [Largest Number](https://leetcode.com/problems/largest-number/) | Medium |
| 12  | [Rearrange Array Elements by Sign](https://leetcode.com/problems/rearrange-array-elements-by-sign/) | Medium |
| 13  | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Medium |
| 14  | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Medium |
| 15  | [N-Queens](https://leetcode.com/problems/n-queens/) | Medium |
| 16  | [Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/) | Medium |
| 17  | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Medium |
| 18  | [H-Index III](https://leetcode.com/problems/h-index-iii/) | Medium |
| 19  | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium |
| 20  | [Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Medium |
| 21  | [Counting Sort](https://leetcode.com/problems/counting-sort/) | Medium |
| 22  | [Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium |
| 23  | [Find the Missing Number](https://leetcode.com/problems/find-the-missing-number/) | Medium |
| 24  | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 25  | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium |
| 26  | [Search for a Range](https://leetcode.com/problems/search-for-a-range/) | Medium |
| 27  | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Medium |
| 28  | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Medium |
| 29  | [Find the Kth Largest Element in an Array](https://leetcode.com/problems/find-the-kth-largest-element-in-an-array/) | Medium |
| 30  | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium |
| 31  | [Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/) | Medium |

---

### 🔴 Hard

| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard |
| 2   | [N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard |
| 3   | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 4   | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 5   | [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Hard |
| 6   | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Hard |
| 7   | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 8   | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Hard |
| 9   | [Largest Sum of Averages](https://leetcode.com/problems/largest-sum-of-averages/) | Hard |
| 10  | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 11  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 12  | [Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Hard |
| 13  | [Median of Two Sorted Arrays II](https://leetcode.com/problems/median-of-two-sorted-arrays-ii/) | Hard |
| 14  | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard |
| 15  | [Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard |
| 16  | [Smallest Range](https://leetcode.com/problems/smallest-range/) | Hard |
| 17  | [Find the Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Hard |
| 18  | [Sort List](https://leetcode.com/problems/sort-list/) | Hard |
| 19  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 20  | [Find the Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Hard |
| 21  | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Hard |
| 22  | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 23  | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Hard |
| 24  | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Hard |
| 25  | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard |
| 26  | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Hard |
| 27  | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Hard |
| 28  | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 29  | [Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/) | Hard |
| 30  | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 31  | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Hard |
| 32  | [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Hard |
| 33  | [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard |
| 34  | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 35  | [The K Weakest Rows in a Matrix](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix/) | Hard |
| 36  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 37  | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 38  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |

---
# Sorting Techniques

### 1. **Bubble Sort**
Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The process is repeated until the list is sorted.

- **LeetCode Problem**: [Bubble Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)

---

### 2. **Selection Sort**
Selection Sort is an in-place comparison sorting algorithm. It works by repeatedly finding the minimum element from the unsorted part and putting it at the beginning.

- **LeetCode Problem**: [Selection Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)

---

### 3. **Insertion Sort**
Insertion Sort builds the final sorted array one item at a time. It works similarly to the way you might sort playing cards in your hands. It picks elements one by one and places them in the correct position.

- **LeetCode Problem**: [Insertion Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)

---

### 4. **Merge Sort**
Merge Sort is a divide-and-conquer algorithm that divides the array into two halves, sorts them, and then merges them back together. It is known for its consistent performance.

- **LeetCode Problem**: [Merge Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n log n)
- **Space Complexity**: O(n)

---

### 5. **Quick Sort**
Quick Sort is another divide-and-conquer algorithm. It selects a pivot element and partitions the array into two sub-arrays. It recursively sorts the sub-arrays.

- **LeetCode Problem**: [Quick Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n log n) on average, O(n²) in the worst case
- **Space Complexity**: O(log n)

---

### 6. **Heap Sort**
Heap Sort uses a binary heap data structure. It builds a max heap from the array, then repeatedly extracts the maximum element from the heap and rebuilds the heap.

- **LeetCode Problem**: [Heap Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n log n)
- **Space Complexity**: O(1)

---

### 7. **Counting Sort**
Counting Sort is an integer sorting algorithm that counts the occurrences of each element in the array and then uses this count to place elements in the sorted order.

- **LeetCode Problem**: [Counting Sort](https://leetcode.com/problems/counting-elements/)
- **Time Complexity**: O(n + k), where k is the range of the numbers
- **Space Complexity**: O(k)

---

### 8. **Radix Sort**
Radix Sort is a non-comparative integer sorting algorithm. It processes the numbers digit by digit, starting from the least significant digit to the most significant one.

- **LeetCode Problem**: [Radix Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(nk), where n is the number of elements and k is the number of digits
- **Space Complexity**: O(n + k)

---

### 9. **Bucket Sort**
Bucket Sort divides the array into several "buckets" and then sorts each bucket individually. It is most effective when the input is uniformly distributed over a range.

- **LeetCode Problem**: [Bucket Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n + k), where n is the number of elements and k is the number of buckets
- **Space Complexity**: O(n + k)

---

### 10. **Tim Sort**
Tim Sort is a hybrid sorting algorithm derived from Merge Sort and Insertion Sort. It is the default sorting algorithm in Python and Java.

- **LeetCode Problem**: [Tim Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n log n)
- **Space Complexity**: O(n)

---

### 11. **Shell Sort**
Shell Sort is a generalized version of Insertion Sort. It allows the exchange of items that are far apart, reducing the total number of swaps compared to regular Insertion Sort.

- **LeetCode Problem**: [Shell Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n log n) (depending on the gap sequence)
- **Space Complexity**: O(1)

---

### 12. **Cocktail Shaker Sort**
Cocktail Shaker Sort is a variation of Bubble Sort. It sorts in both directions on each pass through the list, improving performance by reducing the number of passes.

- **LeetCode Problem**: [Cocktail Shaker Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)

---

### 13. **Gnome Sort**
Gnome Sort is a comparison-based sorting algorithm that is similar to Insertion Sort but with a different approach. It moves an element backward if it is larger than the previous one.

- **LeetCode Problem**: [Gnome Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)

---

### 14. **Pigeonhole Sort**
Pigeonhole Sort is similar to Counting Sort. It sorts by determining the number of "pigeonholes" (buckets) based on the range of the elements and placing them in the correct holes.

- **LeetCode Problem**: [Pigeonhole Sort](https://leetcode.com/problems/sort-an-array/)
- **Time Complexity**: O(n + N), where n is the number of elements and N is the range of numbers
- **Space Complexity**: O(n + N)

---




## Backtracking

### 🟢 Easy

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Subsets](https://leetcode.com/problems/subsets/) | Easy |
| 2 | [Letter Case Permutation](https://leetcode.com/problems/letter-case-permutation/) | Easy |
| 3 | [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Easy |
| 4 | [Combination Sum III](https://leetcode.com/problems/combination-sum-iii/) | Easy |
| 5 | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Easy |
| 6 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | Easy |
| 7 | [Subset Sum](https://leetcode.com/problems/subset-sum/) | Easy |
| 8 | [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Easy |
| 9 | [Permutations](https://leetcode.com/problems/permutations/) | Easy |
| 10 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Easy |
| 11 | [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Easy |
| 12 | [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Easy |
| 13 | [Subsets II](https://leetcode.com/problems/subsets-ii/) | Easy |
| 14 | [Word Search](https://leetcode.com/problems/word-search/) | Easy |
| 15 | [Path Sum](https://leetcode.com/problems/path-sum/) | Easy |
| 16 | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Easy |
| 17 | [Split Array into Fibonacci Sequence](https://leetcode.com/problems/split-array-into-fibonacci-sequence/) | Easy |
| 18 | [Find All Possible Recipes from Given Supplies](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/) | Easy |
| 19 | [Permute Unique](https://leetcode.com/problems/permute-unique/) | Easy |
| 20 | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Easy |
| 21 | [Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Easy |
| 22 | [Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | Easy |
| 23 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy |
| 24 | [Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy |
| 25 | [Permutations II](https://leetcode.com/problems/permutations-ii/) | Easy |
| 26 | [Minesweeper](https://leetcode.com/problems/minesweeper/) | Easy |
| 27 | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Easy |
| 28 | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy |
| 29 | [Combination Sum III](https://leetcode.com/problems/combination-sum-iii/) | Easy |
| 30 | [Climbing Stairs II](https://leetcode.com/problems/climbing-stairs-ii/) | Easy |

### 🟡 Medium

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Permutations](https://leetcode.com/problems/permutations/) | Medium |
| 2 | [Combinations](https://leetcode.com/problems/combinations/) | Medium |
| 3 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium |
| 4 | [Word Search](https://leetcode.com/problems/word-search/) | Medium |
| 5 | [Subsets](https://leetcode.com/problems/subsets/) | Medium |
| 6 | [Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium |
| 7 | [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Medium |
| 8 | [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium |
| 9 | [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Medium |
| 10 | [Subset Sum](https://leetcode.com/problems/subset-sum/) | Medium |
| 11 | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Medium |
| 12 | [N-Queens](https://leetcode.com/problems/n-queens/) | Medium |
| 13 | [Sum of Subset](https://leetcode.com/problems/sum-of-subset/) | Medium |
| 14 | [Combination Sum III](https://leetcode.com/problems/combination-sum-iii/) | Medium |
| 15 | [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Medium |
| 16 | [Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Medium |
| 17 | [Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Medium |
| 18 | [Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium |
| 19 | [Find Unique Paths](https://leetcode.com/problems/find-unique-paths/) | Medium |
| 20 | [Find Minimum Number of Coins](https://leetcode.com/problems/find-minimum-number-of-coins/) | Medium |
| 21 | [Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium |
| 22 | [Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees-ii/) | Medium |
| 23 | [Permutation Sequence](https://leetcode.com/problems/permutation-sequence/) | Medium |
| 24 | [Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/) | Medium |
| 25 | [Subsets III](https://leetcode.com/problems/subsets-iii/) | Medium |
| 26 | [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | Medium |
| 27 | [Count Subsets with Sum](https://leetcode.com/problems/count-subsets-with-sum/) | Medium |
| 28 | [Evaluate Expressions](https://leetcode.com/problems/evaluate-expressions/) | Medium |
| 29 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Medium |
| 30 | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Medium |

### 🔴 Hard

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [N-Queens](https://leetcode.com/problems/n-queens/) | Hard |
| 2 | [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard |
| 3 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 4 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard |
| 5 | [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |
| 6 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 7 | [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard |
| 8 | [Solve N-Queens II](https://leetcode.com/problems/solve-n-queens-ii/) | Hard |
| 9 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 10 | [Scramble String](https://leetcode.com/problems/scramble-string/) | Hard |
| 11 | [Split Array into Consecutive Subsequences](https://leetcode.com/problems/split-array-into-consecutive-subsequences/) | Hard |
| 12 | [Regular Expression Matching II](https://leetcode.com/problems/regular-expression-matching-ii/) | Hard |
| 13 | [Edit Distance](https://leetcode.com/problems/edit-distance/) | Hard |
| 14 | [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard |
| 15 | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 16 | [Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Hard |
| 17 | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Hard |
| 18 | [Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard |
| 19 | [Matrix Chain Multiplication](https://leetcode.com/problems/matrix-chain-multiplication/) | Hard |
| 20 | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 21 | [Integer Break](https://leetcode.com/problems/integer-break/) | Hard |
| 22 | [Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Hard |
| 23 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 24 | [Word Ladder III](https://leetcode.com/problems/word-ladder-iii/) | Hard |
| 25 | [Scramble String II](https://leetcode.com/problems/scramble-string-ii/) | Hard |
| 26 | [Express the Words in a String](https://leetcode.com/problems/express-the-words-in-a-string/) | Hard |
| 27 | [Minimum Distance Between Two Words](https://leetcode.com/problems/minimum-distance-between-two-words/) | Hard |
| 28 | [Distinct Subsequences II](https://leetcode.com/problems/distinct-subsequences-ii/) | Hard |
| 29 | [Minimum Window Substring II](https://leetcode.com/problems/minimum-window-substring-ii/) | Hard |
| 30 | [Maximum Length of Repeated Subarray](https://leetcode.com/problems/maximum-length-of-repeated-subarray/) | Hard |


## Recursion

### 🟢 Easy

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy |
| 2 | [Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes/) | Easy |
| 3 | [Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) | Easy |
| 4 | [Power of Two](https://leetcode.com/problems/power-of-two/) | Easy |
| 5 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy |
| 6 | [Sum of Natural Numbers](https://leetcode.com/problems/sum-of-natural-numbers/) | Easy |
| 7 | [Find GCD](https://leetcode.com/problems/find-gcd/) | Easy |
| 8 | [Print Binary Representation](https://leetcode.com/problems/print-binary-representation/) | Easy |
| 9 | [Count Steps](https://leetcode.com/problems/count-steps/) | Easy |
| 10 | [Array to String](https://leetcode.com/problems/array-to-string/) | Easy |
| 11 | [Sum of Digits](https://leetcode.com/problems/sum-of-digits/) | Easy |
| 12 | [String Length](https://leetcode.com/problems/string-length/) | Easy |
| 13 | [Convert Binary to Decimal](https://leetcode.com/problems/convert-binary-to-decimal/) | Easy |
| 14 | [Simple Reverse](https://leetcode.com/problems/simple-reverse/) | Easy |
| 15 | [Print Fibonacci Sequence](https://leetcode.com/problems/print-fibonacci-sequence/) | Easy |
| 16 | [Count Unique Values](https://leetcode.com/problems/count-unique-values/) | Easy |
| 17 | [Odd Even Check](https://leetcode.com/problems/odd-even-check/) | Easy |
| 18 | [Sum of Even Numbers](https://leetcode.com/problems/sum-of-even-numbers/) | Easy |
| 19 | [Sum of Odd Numbers](https://leetcode.com/problems/sum-of-odd-numbers/) | Easy |
| 20 | [Sum of Powers](https://leetcode.com/problems/sum-of-powers/) | Easy |
| 21 | [Sum of Array Elements](https://leetcode.com/problems/sum-of-array-elements/) | Easy |
| 22 | [Find Max in Array](https://leetcode.com/problems/find-max-in-array/) | Easy |
| 23 | [Find Minimum in Array](https://leetcode.com/problems/find-minimum-in-array/) | Easy |
| 24 | [Print Reverse of Array](https://leetcode.com/problems/print-reverse-of-array/) | Easy |
| 25 | [Sum of Odd Indexed Elements](https://leetcode.com/problems/sum-of-odd-indexed-elements/) | Easy |
| 26 | [Sum of Even Indexed Elements](https://leetcode.com/problems/sum-of-even-indexed-elements/) | Easy |
| 27 | [Find Median of Array](https://leetcode.com/problems/find-median-of-array/) | Easy |
| 28 | [Reverse Sentence](https://leetcode.com/problems/reverse-sentence/) | Easy |
| 29 | [Max Subarray Sum](https://leetcode.com/problems/max-subarray-sum/) | Easy |
| 30 | [Find Element in Sorted Array](https://leetcode.com/problems/find-element-in-sorted-array/) | Easy |

### 🟡 Medium

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium |
| 2 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium |
| 3 | [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium |
| 4 | [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium |
| 5 | [Permutations](https://leetcode.com/problems/permutations/) | Medium |
| 6 | [Combinations](https://leetcode.com/problems/combinations/) | Medium |
| 7 | [Subsets](https://leetcode.com/problems/subsets/) | Medium |
| 8 | [Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium |
| 9 | [Word Break](https://leetcode.com/problems/word-break/) | Medium |
| 10 | [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Medium |
| 11 | [Subsets III](https://leetcode.com/problems/subsets-iii/) | Medium |
| 12 | [Count Sorted Vowel Strings](https://leetcode.com/problems/count-sorted-vowel-strings/) | Medium |
| 13 | [Count Palindromes](https://leetcode.com/problems/count-palindromes/) | Medium |
| 14 | [Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium |
| 15 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 16 | [Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Medium |
| 17 | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Medium |
| 18 | [Decode Ways](https://leetcode.com/problems/decode-ways/) | Medium |
| 19 | [Balanced Parentheses](https://leetcode.com/problems/balanced-parentheses/) | Medium |
| 20 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 21 | [Find All Possible Combinations](https://leetcode.com/problems/find-all-possible-combinations/) | Medium |
| 22 | [Recursive Sort](https://leetcode.com/problems/recursive-sort/) | Medium |
| 23 | [Reverse List in Pairs](https://leetcode.com/problems/reverse-list-in-pairs/) | Medium |
| 24 | [String Subsets](https://leetcode.com/problems/string-subsets/) | Medium |
| 25 | [Word Ladder](https://leetcode.com/problems/word-ladder/) | Medium |
| 26 | [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Medium |
| 27 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium |
| 28 | [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Medium |
| 29 | [Coin Change](https://leetcode.com/problems/coin-change/) | Medium |
| 30 | [Climbing Stairs II](https://leetcode.com/problems/climbing-stairs-ii/) | Medium |

### 🔴 Hard

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 2 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard |
| 3 | [N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard |
| 4 | [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |
| 5 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 6 | [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard |
| 7 | [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard |
| 8 | [Solve N-Queens](https://leetcode.com/problems/solve-n-queens/) | Hard |
| 9 | [Edit Distance](https://leetcode.com/problems/edit-distance/) | Hard |
| 10 | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 11 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 12 | [Scramble String](https://leetcode.com/problems/scramble-string/) | Hard |
| 13 | [Scramble String II](https://leetcode.com/problems/scramble-string-ii/) | Hard |
| 14 | [Matrix Chain Multiplication](https://leetcode.com/problems/matrix-chain-multiplication/) | Hard |
| 15 | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 16 | [Distinct Subsequences II](https://leetcode.com/problems/distinct-subsequences-ii/) | Hard |
| 17 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 18 | [Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Hard |
| 19 | [Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Hard |
| 20 | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Hard |
| 21 | [Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard |
| 22 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Hard |
| 23 | [Number of Unique Binary Search Trees II](https://leetcode.com/problems/number-of-unique-binary-search-trees-ii/) | Hard |
| 24 | [Interleaving String](https://leetcode.com/problems/interleaving-string/) | Hard |
| 25 | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard |
| 26 | [Minimum Number of Refueling Stops](https://leetcode.com/problems/minimum-number-of-refueling-stops/) | Hard |
| 27 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 28 | [All Paths From Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/) | Hard |
| 29 | [Palindrome Partitioning III](https://leetcode.com/problems/palindrome-partitioning-iii/) | Hard |
| 30 | [Largest Number At Least Twice of Others](https://leetcode.com/problems/largest-number-at-least-twice-of-others/) | Hard |


## Stack

### 🟢 Easy

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy |
| 2 | [Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/) | Easy |
| 3 | [Valid Parenthesis String](https://leetcode.com/problems/valid-parenthesis-string/) | Easy |
| 4 | [Min Stack](https://leetcode.com/problems/min-stack/) | Easy |
| 5 | [Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/) | Easy |
| 6 | [Reverse String](https://leetcode.com/problems/reverse-string/) | Easy |
| 7 | [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy |
| 8 | [Reverse Polish Notation](https://leetcode.com/problems/reverse-polish-notation/) | Easy |
| 9 | [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Easy |
| 10 | [Implement Stack with Linked List](https://leetcode.com/problems/implement-stack-with-linked-list/) | Easy |
| 11 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Easy |
| 12 | [Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Easy |
| 13 | [Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Easy |
| 14 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy |
| 15 | [Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Easy |
| 16 | [Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Easy |
| 17 | [Simplify Path](https://leetcode.com/problems/simplify-path/) | Easy |
| 18 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Easy |
| 19 | [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Easy |
| 20 | [Remove Element](https://leetcode.com/problems/remove-element/) | Easy |
| 21 | [Stack using Arrays](https://leetcode.com/problems/stack-using-arrays/) | Easy |
| 22 | [Path with Maximum Gold](https://leetcode.com/problems/path-with-maximum-gold/) | Easy |
| 23 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy |
| 24 | [Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/) | Easy |
| 25 | [Largest Number At Least Twice of Others](https://leetcode.com/problems/largest-number-at-least-twice-of-others/) | Easy |
| 26 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 27 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Easy |
| 28 | [Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Easy |
| 29 | [Level Order Traversal](https://leetcode.com/problems/level-order-traversal/) | Easy |
| 30 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Easy |

### 🟡 Medium

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Medium |
| 2 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Medium |
| 3 | [Daily Temperature](https://leetcode.com/problems/daily-temperature/) | Medium |
| 4 | [Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/) | Medium |
| 5 | [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium |
| 6 | [Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/) | Medium |
| 7 | [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium |
| 8 | [Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/) | Medium |
| 9 | [Decode String](https://leetcode.com/problems/decode-string/) | Medium |
| 10 | [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Medium |
| 11 | [Insert Interval](https://leetcode.com/problems/insert-interval/) | Medium |
| 12 | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Medium |
| 13 | [Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) | Medium |
| 14 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Medium |
| 15 | [LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium |
| 16 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Medium |
| 17 | [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Medium |
| 18 | [Path with Maximum Gold](https://leetcode.com/problems/path-with-maximum-gold/) | Medium |
| 19 | [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Medium |
| 20 | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium |
| 21 | [Flatten 2D Vector](https://leetcode.com/problems/flatten-2d-vector/) | Medium |
| 22 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Medium |
| 23 | [Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/) | Medium |
| 24 | [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium |
| 25 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 26 | [Decode Ways II](https://leetcode.com/problems/decode-ways-ii/) | Medium |
| 27 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Medium |
| 28 | [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) | Medium |
| 29 | [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Medium |
| 30 | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium |

### 🔴 Hard

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 2 | [Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard |
| 3 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 4 | [Basic Calculator III](https://leetcode.com/problems/basic-calculator-iii/) | Hard |
| 5 | [Super Egg Drop](https://leetcode.com/problems/super-egg-drop/) | Hard |
| 6 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 7 | [Matrix Chain Multiplication](https://leetcode.com/problems/matrix-chain-multiplication/) | Hard |
| 8 | [Largest Number At Least Twice of Others](https://leetcode.com/problems/largest-number-at-least-twice-of-others/) | Hard |
| 9 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 10 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 11 | [Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Hard |
| 12 | [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard |
| 13 | [Find All Possible Combinations](https://leetcode.com/problems/find-all-possible-combinations/) | Hard |
| 14 | [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard |
| 15 | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 16 | [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard |
| 17 | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Hard |
| 18 | [K-th Largest in an Array](https://leetcode.com/problems/k-th-largest-in-an-array/) | Hard |
| 19 | [Shortest Distance from All Buildings](https://leetcode.com/problems/shortest-distance-from-all-buildings/) | Hard |
| 20 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Hard |
| 21 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 22 | [Decode Ways II](https://leetcode.com/problems/decode-ways-ii/) | Hard |
| 23 | [Minimum Cost to Merge Stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/) | Hard |
| 24 | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 25 | [Super Egg Drop](https://leetcode.com/problems/super-egg-drop/) | Hard |
| 26 | [Minimum Stack](https://leetcode.com/problems/minimum-stack/) | Hard |
| 27 | [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard |
| 28 | [Find All Possible Combinations](https://leetcode.com/problems/find-all-possible-combinations/) | Hard |
| 29 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 30 | [Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/) | Hard |


## Queue

### 🟢 Easy

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy |
| 2 | [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Easy |
| 3 | [Circular Queue](https://leetcode.com/problems/circular-queue/) | Easy |
| 4 | [Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Easy |
| 5 | [Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) | Easy |
| 6 | [Count Primes](https://leetcode.com/problems/count-primes/) | Easy |
| 7 | [Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) | Easy |
| 8 | [Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/) | Easy |
| 9 | [Queue using Two Stacks](https://leetcode.com/problems/queue-using-two-stacks/) | Easy |
| 10 | [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy |
| 11 | [My Circular Queue](https://leetcode.com/problems/my-circular-queue/) | Easy |
| 12 | [Push Dominoes](https://leetcode.com/problems/push-dominoes/) | Easy |
| 13 | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | Easy |
| 14 | [Matrix Reshape](https://leetcode.com/problems/matrix-reshape/) | Easy |
| 15 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy |
| 16 | [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy |
| 17 | [Flood Fill](https://leetcode.com/problems/flood-fill/) | Easy |
| 18 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy |
| 19 | [Number of Islands II](https://leetcode.com/problems/number-of-islands-ii/) | Easy |
| 20 | [Reverse Integer](https://leetcode.com/problems/reverse-integer/) | Easy |

### 🟡 Medium

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium |
| 2 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Medium |
| 3 | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Medium |
| 4 | [Design Snake Game](https://leetcode.com/problems/design-snake-game/) | Medium |
| 5 | [My Queue](https://leetcode.com/problems/my-queue/) | Medium |
| 6 | [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Medium |
| 7 | [Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls/) | Medium |
| 8 | [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) | Medium |
| 9 | [Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) | Medium |
| 10 | [Course Schedule](https://leetcode.com/problems/course-schedule/) | Medium |
| 11 | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium |
| 12 | [Reorder List](https://leetcode.com/problems/reorder-list/) | Medium |
| 13 | [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium |
| 14 | [Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) | Medium |
| 15 | [Implement Trie](https://leetcode.com/problems/implement-trie/) | Medium |
| 16 | [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Medium |
| 17 | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium |

### 🔴 Hard

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 2 | [Super Egg Drop](https://leetcode.com/problems/super-egg-drop/) | Hard |
| 3 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 4 | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Hard |
| 5 | [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Hard |
| 6 | [Find All Possible Combinations](https://leetcode.com/problems/find-all-possible-combinations/) | Hard |
| 7 | [Minimum Stack](https://leetcode.com/problems/minimum-stack/) | Hard |
| 8 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 9 | [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Hard |
| 10 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 11 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Hard |
| 12 | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 13 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Hard |
| 14 | [Matrix Chain Multiplication](https://leetcode.com/problems/matrix-chain-multiplication/) | Hard |
| 15 | [Shortest Distance from All Buildings](https://leetcode.com/problems/shortest-distance-from-all-buildings/) | Hard |
| 16 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 17 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 18 | [Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Hard |
| 19 | [Decode Ways II](https://leetcode.com/problems/decode-ways-ii/) | Hard |
| 20 | [Super Egg Drop](https://leetcode.com/problems/super-egg-drop/) | Hard |
| 21 | [Queue Reconstruct by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Hard |
| 22 | [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Hard |
| 23 | [Design Hit Counter](https://leetcode.com/problems/design-hit-counter/) | Hard |
| 24 | [Design a Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Hard |
| 25 | [Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) | Hard |
| 26 | [Design a Stack with Increment Operation](https://leetcode.com/problems/design-a-stack-with-increment-operation/) | Hard |
| 27 | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard |
| 28 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Hard |
| 29 | [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard |
| 30 | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Hard |



## Linked List
### 🟢 Easy

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy |
| 2 | [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy |
| 3 | [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy |
| 4 | [Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy |
| 5 | [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy |
| 6 | [Convert Binary Number in a Linked List to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/) | Easy |
| 7 | [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy |
| 8 | [Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list/) | Easy |
| 9 | [Design Linked List](https://leetcode.com/problems/design-linked-list/) | Easy |
| 10 | [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Easy |
| 11 | [Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Easy |
| 12 | [Two Sum IV - Input is a BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) | Easy |
| 13 | [Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Easy |
| 14 | [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Easy |
| 15 | [Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Easy |
| 16 | [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Easy |
| 17 | [Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Easy |
| 18 | [Delete the Middle Node of a Linked List](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/) | Easy |
| 19 | [Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/) | Easy |
| 20 | [Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Easy |
| 21 | [Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Easy |
| 22 | [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Easy |
| 23 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 24 | [Check if Linked List is Palindrome](https://leetcode.com/problems/palindrome-linked-list/) | Easy |
| 25 | [Find Middle of Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy |
| 26 | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Easy |
| 27 | [Find Intersection Node](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Easy |
| 28 | [Rotate List](https://leetcode.com/problems/rotate-list/) | Easy |
| 29 | [Reverse Nodes in K Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Easy |
| 30 | [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Easy |


### 🟡 Medium

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium |
| 2 | [Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Medium |
| 3 | [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium |
| 4 | [Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Medium |
| 5 | [Partition List](https://leetcode.com/problems/partition-list/) | Medium |
| 6 | [Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | Medium |
| 7 | [Rotate List](https://leetcode.com/problems/rotate-list/) | Medium |
| 8 | [Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium |
| 9 | [Sort List](https://leetcode.com/problems/sort-list/) | Medium |
| 10 | [Reorder List](https://leetcode.com/problems/reorder-list/) | Medium |
| 11 | [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Medium |
| 12 | [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Medium |
| 13 | [Linked List Random Node](https://leetcode.com/problems/linked-list-random-node/) | Medium |
| 14 | [Remove Zero Sum Consecutive Nodes from Linked List](https://leetcode.com/problems/remove-zero-sum-consecutive-nodes-from-linked-list/) | Medium |
| 15 | [Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/) | Medium |
| 16 | [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Medium |
| 17 | [LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium |
| 18 | [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Medium |
| 19 | [Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium |
| 20 | [Design Browser History](https://leetcode.com/problems/design-browser-history/) | Medium |
| 21 | [Merge In Between Linked Lists](https://leetcode.com/problems/merge-in-between-linked-lists/) | Medium |
| 22 | [Design Linked List](https://leetcode.com/problems/design-linked-list/) | Medium |
| 23 | [Split Linked List in Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Medium |
| 24 | [Design Front Middle Back Queue](https://leetcode.com/problems/design-front-middle-back-queue/) | Medium |
| 25 | [Linked List in Binary Tree](https://leetcode.com/problems/linked-list-in-binary-tree/) | Medium |
| 26 | [Insert into a Sorted Circular Linked List](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list/) | Medium |
| 27 | [Maximum Twin Sum of a Linked List](https://leetcode.com/problems/maximum-twin-sum-of-a-linked-list/) | Medium |
| 28 | [Swapping Nodes in a Linked List](https://leetcode.com/problems/swapping-nodes-in-a-linked-list/) | Medium |
| 29 | [Remove Nodes From Linked List](https://leetcode.com/problems/remove-nodes-from-linked-list/) | Medium |
| 30 | [Double a Number Represented as a Linked List](https://leetcode.com/problems/double-a-number-represented-as-a-linked-list/) | Medium |


### 🔴 Hard

| No. | Problem | Difficulty |
|-----|---------|------------|
| 1 | [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Hard |
| 2 | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard |
| 3 | [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | Hard |
| 4 | [LRU Cache](https://leetcode.com/problems/lru-cache/) | Hard |
| 5 | [Design Skiplist](https://leetcode.com/problems/design-skiplist/) | Hard |
| 6 | [Linked List in Binary Tree](https://leetcode.com/problems/linked-list-in-binary-tree/) | Hard |
| 7 | [Remove Zero Sum Consecutive Nodes from Linked List](https://leetcode.com/problems/remove-zero-sum-consecutive-nodes-from-linked-list/) | Hard |
| 8 | [Split Linked List into Parts](https://leetcode.com/problems/split-linked-list-in-parts/) | Hard |
| 9 | [Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | Hard |
| 10 | [Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | Hard |
| 11 | [Sort List](https://leetcode.com/problems/sort-list/) | Hard |
| 12 | [Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) | Hard |
| 13 | [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Hard |
| 14 | [Reorder List](https://leetcode.com/problems/reorder-list/) | Hard |
| 15 | [Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Hard |
| 16 | [Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/) | Hard |
| 17 | [Next Greater Node In Linked List](https://leetcode.com/problems/next-greater-node-in-linked-list/) | Hard |
| 18 | [Merge Nodes in Between Zeros](https://leetcode.com/problems/merge-nodes-in-between-zeros/) | Hard |
| 19 | [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Hard |
| 20 | [Design Linked List](https://leetcode.com/problems/design-linked-list/) | Hard |
| 21 | [Swapping Nodes in a Linked List](https://leetcode.com/problems/swapping-nodes-in-a-linked-list/) | Hard |
| 22 | [Maximum Twin Sum of a Linked List](https://leetcode.com/problems/maximum-twin-sum-of-a-linked-list/) | Hard |
| 23 | [Remove Nodes From Linked List](https://leetcode.com/problems/remove-nodes-from-linked-list/) | Hard |
| 24 | [Double a Number Represented as a Linked List](https://leetcode.com/problems/double-a-number-represented-as-a-linked-list/) | Hard |
| 25 | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Hard |
| 26 | [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Hard |
| 27 | [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Hard |
| 28 | [Delete the Middle Node of a Linked List](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/) | Hard |
| 29 | [Partition List](https://leetcode.com/problems/partition-list/) | Hard |
| 30 | [Rotate List](https://leetcode.com/problems/rotate-list/) | Hard |



## 🌳 Trees

### 🟢 Easy
| No. | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy |
| 2   | [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy |
| 3   | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy |
| 4   | [Path Sum](https://leetcode.com/problems/path-sum/) | Easy |
| 5   | [Same Tree](https://leetcode.com/problems/same-tree/) | Easy |
| 6   | [Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy |
| 7   | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy |
| 8   | [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy |
| 9   | [Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/) | Easy |
| 10  | [Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/) | Easy |
| 11  | [Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees/) | Easy |
| 12  | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Easy |
| 13  | [Count Univalue Subtrees](https://leetcode.com/problems/count-univalue-subtrees/) | Easy |
| 14  | [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/) | Easy |
| 15  | [Cousins in Binary Tree](https://leetcode.com/problems/cousins-in-binary-tree/) | Easy |
| 16  | [Univalued Binary Tree](https://leetcode.com/problems/univalued-binary-tree/) | Easy |
| 17  | [Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt/) | Easy |
| 18  | [Find Mode in Binary Search Tree](https://leetcode.com/problems/find-mode-in-binary-search-tree/) | Easy |
| 19  | [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Easy |
| 20  | [N-ary Tree Preorder Traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal/) | Easy |
| 21  | [N-ary Tree Postorder Traversal](https://leetcode.com/problems/n-ary-tree-postorder-traversal/) | Easy |
| 22  | [Find Bottom Left Tree Value](https://leetcode.com/problems/find-bottom-left-tree-value/) | Easy |
| 23  | [Two Sum IV - Input is a BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) | Easy |
| 24  | [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Easy |
| 25  | [Minimum Absolute Difference in BST](https://leetcode.com/problems/minimum-absolute-difference-in-bst/) | Easy |
| 26  | [Second Minimum Node In a Binary Tree](https://leetcode.com/problems/second-minimum-node-in-a-binary-tree/) | Easy |
| 27  | [Closest Binary Search Tree Value](https://leetcode.com/problems/closest-binary-search-tree-value/) | Easy |
| 28  | [Increasing Order Search Tree](https://leetcode.com/problems/increasing-order-search-tree/) | Easy |
| 29  | [Lowest Common Ancestor of a BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | Easy |
| 30  | [Trim a Binary Search Tree](https://leetcode.com/problems/trim-a-binary-search-tree/) | Easy |

---


### 🟡 Medium
| No. | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/) | Medium |
| 2   | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Medium |
| 3   | [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | Medium |
| 4   | [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Medium |
| 5   | [Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Medium |
| 6   | [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium |
| 7   | [Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) | Medium |
| 8   | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium |
| 9   | [Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | Medium |
| 10  | [Vertical Order Traversal of a Binary Tree](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | Medium |
| 11  | [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | Medium |
| 12  | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium |
| 13  | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Medium |
| 14  | [Find Leaves of Binary Tree](https://leetcode.com/problems/find-leaves-of-binary-tree/) | Medium |
| 15  | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Medium |
| 16  | [Largest BST Subtree](https://leetcode.com/problems/largest-bst-subtree/) | Medium |
| 17  | [Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) | Medium |
| 18  | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Medium |
| 19  | [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Medium |
| 20  | [Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/) | Medium |
| 21  | [Sum of Node with Even-Valued Grandparent](https://leetcode.com/problems/sum-of-nodes-with-even-valued-grandparent/) | Medium |
| 22  | [Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Medium |
| 23  | [Binary Tree Longest Consecutive Sequence](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence/) | Medium |
| 24  | [Binary Tree Maximum Width](https://leetcode.com/problems/binary-tree-maximum-width/) | Medium |
| 25  | [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Medium |
| 26  | [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Medium |
| 27  | [Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees/) | Medium |
| 28  | [Find Bottom Left Tree Value](https://leetcode.com/problems/find-bottom-left-tree-value/) | Medium |
| 29  | [Kth Largest Element in a BST](https://leetcode.com/problems/kth-largest-element-in-a-bst/) | Medium |
| 30  | [All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) | Medium |

---


### 🔴 Hard
| No. | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard |
| 2   | [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Hard |
| 3   | [Binary Tree Longest Consecutive Sequence](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence/) | Hard |
| 4   | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 5   | [Largest BST Subtree](https://leetcode.com/problems/largest-bst-subtree/) | Hard |
| 6   | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Hard |
| 7   | [Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) | Hard |
| 8   | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Hard |
| 9   | [Kth Largest Element in a Binary Search Tree](https://leetcode.com/problems/kth-largest-element-in-a-binary-search-tree/) | Hard |
| 10  | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard |
| 11  | [Find Bottom Left Tree Value](https://leetcode.com/problems/find-bottom-left-tree-value/) | Hard |
| 12  | [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Hard |
| 13  | [Maximum Binary Tree](https://leetcode.com/problems/maximum-binary-tree/) | Hard |
| 14  | [Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Hard |
| 15  | [Binary Tree Vertical Order Traversal](https://leetcode.com/problems/binary-tree-vertical-order-traversal/) | Hard |
| 16  | [Count Univalue Subtrees](https://leetcode.com/problems/count-univalue-subtrees/) | Hard |
| 17  | [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Hard |
| 18  | [Binary Search Tree to Greater Sum Tree](https://leetcode.com/problems/binary-search-tree-to-greater-sum-tree/) | Hard |
| 19  | [Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Hard |
| 20  | [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Hard |
| 21  | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Hard |
| 22  | [Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Hard |
| 23  | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Hard |
| 24  | [Find Mode in Binary Search Tree](https://leetcode.com/problems/find-mode-in-binary-search-tree/) | Hard |
| 25  | [Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt/) | Hard |
| 26  | [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Hard |
| 27  | [Find Leaves of Binary Tree](https://leetcode.com/problems/find-leaves-of-binary-tree/) | Hard |
| 28  | [Vertical Order Traversal](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | Hard |
| 29  | [Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) | Hard |
| 30  | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard |

---

## **Binary Search Tree (BST)**

### 🟢 Easy
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/) | Easy |
| 2   | [Lowest Common Ancestor of a BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | Easy |
| 3   | [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Easy |
| 4   | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Easy |
| 5   | [Closest Binary Search Tree Value](https://leetcode.com/problems/closest-binary-search-tree-value/) | Easy |
| 6   | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Easy |
| 7   | [Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/) | Easy |
| 8   | [Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Easy |
| 9   | [Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) | Easy |
| 10  | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy |
| 11  | [Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees/) | Easy |
| 12  | [Find Mode in Binary Search Tree](https://leetcode.com/problems/find-mode-in-binary-search-tree/) | Easy |
| 13  | [Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Easy |
| 14  | [Binary Search](https://leetcode.com/problems/binary-search/) | Easy |
| 15  | [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy |
| 16  | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Easy |
| 17  | [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy |
| 18  | [Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Easy |
| 19  | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy |
| 20  | [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy |
| 21  | [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Easy |
| 22  | [Same Tree](https://leetcode.com/problems/same-tree/) | Easy |
| 23  | [Convert Sorted List to Binary Search Tree](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/) | Easy |
| 24  | [Maximum Depth of N-ary Tree](https://leetcode.com/problems/maximum-depth-of-n-ary-tree/) | Easy |
| 25  | [Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy |
| 26  | [Check Completeness of a Binary Tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree/) | Easy |
| 27  | [Path Sum](https://leetcode.com/problems/path-sum/) | Easy |
| 28  | [Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees/) | Easy |
| 29  | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 30  | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy |

---

### 🟡 Medium
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | Medium |
| 2   | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium |
| 3   | [Kth Largest Element in a BST](https://leetcode.com/problems/kth-largest-element-in-a-bst/) | Medium |
| 4   | [Trim a Binary Search Tree](https://leetcode.com/problems/trim-a-binary-search-tree/) | Medium |
| 5   | [Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/) | Medium |
| 6   | [Lowest Common Ancestor of a BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | Medium |
| 7   | [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Medium |
| 8   | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium |
| 9   | [Find Mode in Binary Search Tree](https://leetcode.com/problems/find-mode-in-binary-search-tree/) | Medium |
| 10  | [Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) | Medium |
| 11  | [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Medium |
| 12  | [Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt/) | Medium |
| 13  | [Binary Search Tree to Greater Sum Tree](https://leetcode.com/problems/binary-search-tree-to-greater-sum-tree/) | Medium |
| 14  | [Largest BST Subtree](https://leetcode.com/problems/largest-bst-subtree/) | Medium |
| 15  | [Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Medium |
| 16  | [Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/) | Medium |
| 17  | [Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor/) | Medium |
| 18  | [Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) | Medium |
| 19  | [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Medium |
| 20  | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Medium |
| 21  | [Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | Medium |
| 22  | [Inorder Successor in BST](https://leetcode.com/problems/inorder-successor-in-bst/) | Medium |
| 23  | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Medium |
| 24  | [Find Kth Largest Element in a Binary Search Tree](https://leetcode.com/problems/find-kth-largest-element-in-a-binary-search-tree/) | Medium |
| 25  | [Find Bottom Left Tree Value](https://leetcode.com/problems/find-bottom-left-tree-value/) | Medium |
| 26  | [Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) | Medium |
| 27  | [Increasing Order Search Tree](https://leetcode.com/problems/increasing-order-search-tree/) | Medium |
| 28  | [Convert Binary Search Tree to Sorted Doubly Linked List](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/) | Medium |
| 29  | [Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/) | Medium |
| 30  | [Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/) | Medium |

---

### 🔴 Hard
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Binary Search Tree to Greater Sum Tree](https://leetcode.com/problems/binary-search-tree-to-greater-sum-tree/) | Hard |
| 2   | [Maximum Binary Tree](https://leetcode.com/problems/maximum-binary-tree/) | Hard |
| 3   | [Largest BST Subtree](https://leetcode.com/problems/largest-bst-subtree/) | Hard |
| 4   | [Recover Binary Search Tree](https://leetcode.com/problems/recover-binary-search-tree/) | Hard |
| 5   | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard |
| 6   | [Kth Largest Element in a Binary Search Tree](https://leetcode.com/problems/kth-largest-element-in-a-binary-search-tree/) | Hard |
| 7   | [Binary Tree Vertical Order Traversal](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/) | Hard |
| 8   | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard |
| 9   | [Find the Duplicate Subtrees](https://leetcode.com/problems/find-duplicate-subtrees/) | Hard |
| 10  | [Binary Tree Pruning](https://leetcode.com/problems/binary-tree-pruning/) | Hard |
| 11  | [Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/) | Hard |
| 12  | [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/) | Hard |
| 13  | [Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) | Hard |
| 14  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 15  | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Hard |
| 16  | [Maximum Path Sum in Binary Tree](https://leetcode.com/problems/maximum-path-sum/) | Hard |
| 17  | [Path Sum IV](https://leetcode.com/problems/path-sum-iv/) | Hard |
| 18  | [Smallest Range II](https://leetcode.com/problems/smallest-range-ii/) | Hard |
| 19  | [Falling Squares](https://leetcode.com/problems/falling-squares/) | Hard |
| 20  | [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard |
| 21  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 22  | [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Hard |
| 23  | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Hard |
| 24  | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard |
| 25  | [Jump Game IV](https://leetcode.com/problems/jump-game-iv/) | Hard |
| 26  | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Hard |
| 27  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 28  | [Simplify Path](https://leetcode.com/problems/simplify-path/) | Hard |
| 29  | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Hard |
| 30  | [K-th Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Hard |

# Heap Problems

## 🟢 Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Easy |
| 2  | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Easy |
| 3  | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Easy |
| 4  | [Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Easy |
| 5  | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Easy |
| 6  | [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Easy |
| 7  | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Easy |
| 8  | [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Easy |
| 9  | [Rearrange String k Distance Apart](https://leetcode.com/problems/rearrange-string-k-distance-apart/) | Easy |
| 10 | [Find the Kth Largest Integer in the Array](https://leetcode.com/problems/find-the-kth-largest-integer-in-the-array/) | Easy |
| 11 | [Minimum Cost to Connect Sticks](https://leetcode.com/problems/minimum-cost-to-connect-sticks/) | Easy |
| 12 | [Priority Queue with Deletion](https://leetcode.com/problems/priority-queue-with-deletion/) | Easy |
| 13 | [Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/) | Easy |
| 14 | [Heap Sort](https://leetcode.com/problems/heap-sort/) | Easy |
| 15 | [Max Heap](https://leetcode.com/problems/max-heap/) | Easy |
| 16 | [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Easy |
| 17 | [Sort List](https://leetcode.com/problems/sort-list/) | Easy |
| 18 | [Reorganize String](https://leetcode.com/problems/reorganize-string/) | Easy |
| 19 | [Find Kth Largest Sum](https://leetcode.com/problems/find-kth-largest-sum/) | Easy |
| 20 | [Minimum Cost to Hire K Workers](https://leetcode.com/problems/minimum-cost-to-hire-k-workers/) | Easy |
| 21 | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Easy |
| 22 | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy |
| 23 | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Easy |
| 24 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Easy |
| 25 | [Design a Min-Heap](https://leetcode.com/problems/design-a-min-heap/) | Easy |
| 26 | [Frequency of Most Frequent Element](https://leetcode.com/problems/frequency-of-most-frequent-element/) | Easy |
| 27 | [Kth Smallest Element in Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-sorted-matrix/) | Easy |
| 28 | [Get Kth Largest Element from Array](https://leetcode.com/problems/get-kth-largest-element-from-array/) | Easy |
| 29 | [Smallest Range II](https://leetcode.com/problems/smallest-range-ii/) | Easy |
| 30 | [Smallest Range](https://leetcode.com/problems/smallest-range/) | Easy |

## 🟡 Medium

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 2  | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium |
| 3  | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Medium |
| 4  | [Find Kth Smallest Element in Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-sorted-matrix/) | Medium |
| 5  | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Medium |
| 6  | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Medium |
| 7  | [Kth Largest Sum in Two Sorted Arrays](https://leetcode.com/problems/kth-largest-sum-in-two-sorted-arrays/) | Medium |
| 8  | [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium |
| 9  | [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Medium |
| 10 | [Design a Heap Data Structure](https://leetcode.com/problems/design-a-heap-data-structure/) | Medium |
| 11 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 12 | [Reorganize String](https://leetcode.com/problems/reorganize-string/) | Medium |
| 13 | [Maximize the Sweetness of the Subarray](https://leetcode.com/problems/maximize-the-sweetness-of-the-subarray/) | Medium |
| 14 | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Medium |
| 15 | [Find Kth Largest Element in a Sorted Array](https://leetcode.com/problems/find-kth-largest-element-in-a-sorted-array/) | Medium |
| 16 | [Min Stack](https://leetcode.com/problems/min-stack/) | Medium |
| 17 | [Find the Kth Largest Integer in the Array](https://leetcode.com/problems/find-the-kth-largest-integer-in-the-array/) | Medium |
| 18 | [Kth Largest Element in a Binary Search Tree](https://leetcode.com/problems/kth-largest-element-in-a-binary-search-tree/) | Medium |
| 19 | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium |
| 20 | [Design a Min Heap](https://leetcode.com/problems/design-a-min-heap/) | Medium |
| 21 | [Design Twitter](https://leetcode.com/problems/design-twitter/) | Medium |
| 22 | [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Medium |
| 23 | [Find Kth Smallest Sum](https://leetcode.com/problems/find-kth-smallest-sum/) | Medium |
| 24 | [Max Heap Operations](https://leetcode.com/problems/max-heap-operations/) | Medium |
| 25 | [Smallest Range](https://leetcode.com/problems/smallest-range/) | Medium |
| 26 | [Heap Sort](https://leetcode.com/problems/heap-sort/) | Medium |
| 27 | [Sort List](https://leetcode.com/problems/sort-list/) | Medium |
| 28 | [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium |
| 29 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Medium |
| 30 | [Min Cost to Connect Sticks](https://leetcode.com/problems/min-cost-to-connect-sticks/) | Medium |

## 🔴 Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 2  | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard |
| 3  | [Kth Largest Element in a Sorted Matrix](https://leetcode.com/problems/kth-largest-element-in-a-sorted-matrix/) | Hard |
| 4  | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 5  | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Hard |
| 6  | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard |
| 7  | [Find Kth Largest Sum in Two Sorted Arrays](https://leetcode.com/problems/kth-largest-sum-in-two-sorted-arrays/) | Hard |
| 8  | [Design a Heap Data Structure](https://leetcode.com/problems/design-a-heap-data-structure/) | Hard |
| 9  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 10 | [Count of Subarrays with Sum 0](https://leetcode.com/problems/count-of-subarrays-with-sum-0/) | Hard |
| 11 | [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/) | Hard |
| 12 | [Design LFU Cache](https://leetcode.com/problems/design-lfu-cache/) | Hard |
| 13 | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Hard |
| 14 | [Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Hard |
| 15 | [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard |
| 16 | [Maximize the Sweetness of the Subarray](https://leetcode.com/problems/maximize-the-sweetness-of-the-subarray/) | Hard |
| 17 | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard |
| 18 | [Rearrange String k Distance Apart](https://leetcode.com/problems/rearrange-string-k-distance-apart/) | Hard |
| 19 | [Design Search Autocomplete System](https://leetcode.com/problems/design-search-autocomplete-system/) | Hard |
| 20 | [Find Kth Largest Element in a Stream](https://leetcode.com/problems/find-kth-largest-element-in-a-stream/) | Hard |
| 21 | [Largest Number At Least Twice of Others](https://leetcode.com/problems/largest-number-at-least-twice-of-others/) | Hard |
| 22 | [Kth Largest Element in a BST](https://leetcode.com/problems/kth-largest-element-in-a-bst/) | Hard |
| 23 | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 24 | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 25 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard |
| 26 | [Find Kth Largest Sum](https://leetcode.com/problems/find-kth-largest-sum/) | Hard |
| 27 | [Smallest Range](https://leetcode.com/problems/smallest-range/) | Hard |
| 28 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 29 | [First Missing Positive](https://leetcode.com/problems/first-missing-positive/) | Hard |
| 30 | [Find Kth Largest Element in the Array](https://leetcode.com/problems/find-kth-largest-element-in-the-array/) | Hard |


## **Graph Problems**

### 🟢 Easy

| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Breadth-First Search (BFS) Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Easy |
| 2   | [Depth-First Search (DFS) Traversal](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | Easy |
| 3   | [Check if a Graph is Bipartite](https://leetcode.com/problems/is-graph-bipartite/) | Easy |
| 4   | [Find the Degree of a Vertex](https://leetcode.com/problems/degree-of-an-array/) | Easy |
| 5   | [Number of Connected Components](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | Easy |
| 6   | [Detect Cycle in an Undirected Graph](https://leetcode.com/problems/graph-valid-tree/) | Easy |
| 7   | [Detect Cycle in a Directed Graph](https://leetcode.com/problems/course-schedule/) | Easy |
| 8   | [Path Finding in a Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) | Easy |
| 9   | [Graph Representation (Adjacency List)](https://leetcode.com/problems/clone-graph/) | Easy |
| 10  | [Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | Easy |
| 11  | [Topological Sort (DFS-based)](https://leetcode.com/problems/course-schedule/) | Easy |
| 12  | [Shortest Path in Unweighted Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) | Easy |
| 13  | [Clone a Graph](https://leetcode.com/problems/clone-graph/) | Easy |
| 14  | [Flood Fill Algorithm (DFS/BFS)](https://leetcode.com/problems/flood-fill/) | Easy |
| 15  | [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/) | Easy |
| 16  | [Level Order Traversal of Binary Tree](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Easy |
| 17  | [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/) | Easy |
| 18  | [Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees/) | Easy |
| 19  | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy |
| 20  | [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Easy |
| 21  | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | Easy |
| 22  | [Same Tree](https://leetcode.com/problems/same-tree/) | Easy |
| 23  | [Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/) | Easy |
| 24  | [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy |
| 25  | [Path Sum II](https://leetcode.com/problems/path-sum-ii/) | Easy |
| 26  | [Find Mode in Binary Search Tree](https://leetcode.com/problems/find-mode-in-binary-search-tree/) | Easy |
| 27  | [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/) | Easy |
| 28  | [Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/) | Easy |
| 29  | [Same Tree](https://leetcode.com/problems/same-tree/) | Easy |
| 30  | [Search in Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Easy |

---

### 🟡 Medium

| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) | Medium |
| 2   | [Course Schedule](https://leetcode.com/problems/course-schedule/) | Medium |
| 3   | [Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) | Medium |
| 4   | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium |
| 5   | [Clone Graph](https://leetcode.com/problems/clone-graph/) | Medium |
| 6   | [Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/) | Medium |
| 7   | [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) | Medium |
| 8   | [Word Ladder](https://leetcode.com/problems/word-ladder/) | Medium |
| 9   | [Graph Traversal (DFS/BFS)](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | Medium |
| 10  | [Topological Sort using BFS (Kahn's Algorithm)](https://leetcode.com/problems/course-schedule-ii/) | Medium |
| 11  | [Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | Medium |
| 12  | [Dijkstra’s Algorithm](https://leetcode.com/problems/network-delay-time/) | Medium |
| 13  | [Network Delay Time](https://leetcode.com/problems/network-delay-time/) | Medium |
| 14  | [Minimum Cost to Connect All Points](https://leetcode.com/problems/minimum-cost-to-connect-all-points/) | Medium |
| 15  | [Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/) | Medium |
| 16  | [Find the Town Judge](https://leetcode.com/problems/find-the-town-judge/) | Medium |
| 17  | [Count Connected Components in Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | Medium |
| 18  | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Medium |
| 19  | [All Paths from Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/) | Medium |
| 20  | [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/) | Medium |
| 21  | [Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/) | Medium |
| 22  | [Course Schedule III](https://leetcode.com/problems/course-schedule-iii/) | Medium |
| 23  | [Possible Bipartition](https://leetcode.com/problems/possible-bipartition/) | Medium |
| 24  | [Minimum Spanning Tree](https://leetcode.com/problems/minimum-spanning-tree/) | Medium |
| 25  | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Medium |
| 26  | [Zombie in Matrix](https://leetcode.com/problems/rotting-oranges/) | Medium |
| 27  | [Graph DFS and BFS](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) | Medium |
| 28  | [All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/) | Medium |
| 29  | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Medium |
| 30  | [Dijkstra’s Algorithm Implementation](https://leetcode.com/problems/network-delay-time/) | Medium |

---

### 🔴 Hard

| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Maximal Network Rank](https://leetcode.com/problems/maximal-network-rank/) | Hard |
| 2   | [Word Ladder III](https://leetcode.com/problems/word-ladder-iii/) | Hard |
| 3   | [Smallest String with Swaps](https://leetcode.com/problems/smallest-string-with-swaps/) | Hard |
| 4   | [Minimum Number of Vertices to Reach All Nodes](https://leetcode.com/problems/minimum-number-of-vertices-to-reach-all-nodes/) | Hard |
| 5   | [Find Minimum Time to Finish All Jobs](https://leetcode.com/problems/minimum-time-to-finish-all-jobs/) | Hard |
| 6   | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 7   | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Hard |
| 8   | [Max Flow](https://leetcode.com/problems/maximum-flow/) | Hard |
| 9   | [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard |
| 10  | [Falling Squares](https://leetcode.com/problems/falling-squares/) | Hard |
| 11  | [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Hard |
| 12  | [Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) | Hard |
| 13  | [Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Hard |
| 14  | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard |
| 15  | [Maximum Path Sum in Binary Tree](https://leetcode.com/problems/maximum-path-sum/) | Hard |
| 16  | [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Hard |
| 17  | [Matrix Chain Multiplication](https://leetcode.com/problems/matrix-chain-multiplication/) | Hard |
| 18  | [Word Ladder IV](https://leetcode.com/problems/word-ladder-iv/) | Hard |
| 19  | [Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/) | Hard |
| 20  | [Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/) | Hard |
| 21  | [Traveling Salesman Problem](https://leetcode.com/problems/traveling-salesman-problem/) | Hard |
| 22  | [Minimum Cost to Make at Least One Valid Path in a Grid](https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/) | Hard |
| 23  | [Longest Path with Different Adjacent Characters](https://leetcode.com/problems/longest-path-with-different-adjacent-characters/) | Hard |
| 24  | [Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) | Hard |
| 25  | [Find the Cheapest Price Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | Hard |
| 26  | [Reconstruct Graph](https://leetcode.com/problems/reconstruct-graph/) | Hard |
| 27  | [Remove Invalid Parentheses](https://leetcode.com/problems/remove-invalid-parentheses/) | Hard |
| 28  | [Maximal Network Rank](https://leetcode.com/problems/maximal-network-rank/) | Hard |
| 29  | [Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard |
| 30  | [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/) | Hard |



## **Greedy**

### 🟢 Easy
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Assign Cookies](https://leetcode.com/problems/assign-cookies/) | Easy |
| 2   | [Jump Game](https://leetcode.com/problems/jump-game/) | Easy |
| 3   | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy |
| 4   | [House Robber](https://leetcode.com/problems/house-robber/) | Easy |
| 5   | [Non-decreasing Array](https://leetcode.com/problems/non-decreasing-array/) | Easy |
| 6   | [Largest Number](https://leetcode.com/problems/largest-number/) | Easy |
| 7   | [Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/) | Easy |
| 8   | [Gas Station](https://leetcode.com/problems/gas-station/) | Easy |
| 9   | [Candy](https://leetcode.com/problems/candy/) | Easy |
| 10  | [Partition Labels](https://leetcode.com/problems/partition-labels/) | Easy |
| 11  | [Distribute Candies](https://leetcode.com/problems/distribute-candies/) | Easy |
| 12  | [Fruit Into Baskets](https://leetcode.com/problems/fruit-into-baskets/) | Easy |
| 13  | [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | Easy |
| 14  | [Car Pooling](https://leetcode.com/problems/car-pooling/) | Easy |
| 15  | [Smallest Range I](https://leetcode.com/problems/smallest-range-i/) | Easy |
| 16  | [Rearrange Array Elements by Sign](https://leetcode.com/problems/rearrange-array-elements-by-sign/) | Easy |
| 17  | [Find the Town Judge](https://leetcode.com/problems/find-the-town-judge/) | Easy |
| 18  | [Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/) | Easy |
| 19  | [Monotonic Array](https://leetcode.com/problems/monotonic-array/) | Easy |
| 20  | [Number of Students Doing Homework at a Given Time](https://leetcode.com/problems/number-of-students-doing-homework-at-a-given-time/) | Easy |
| 21  | [Sum of Even Numbers After Queries](https://leetcode.com/problems/sum-of-even-numbers-after-queries/) | Easy |
| 22  | [Finding Users With Valid E-Mails](https://leetcode.com/problems/finding-users-with-valid-e-mails/) | Easy |
| 23  | [Count Items Matching a Rule](https://leetcode.com/problems/count-items-matching-a-rule/) | Easy |
| 24  | [Length of Last Word](https://leetcode.com/problems/length-of-last-word/) | Easy |
| 25  | [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy |
| 26  | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Easy |
| 27  | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Easy |
| 28  | [Rotate Array](https://leetcode.com/problems/rotate-array/) | Easy |
| 29  | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy |
| 30  | [Palindrome Number](https://leetcode.com/problems/palindrome-number/) | Easy |

---

### 🟡 Medium
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium |
| 2   | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 3   | [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Medium |
| 4   | [Task Scheduler](https://leetcode.com/problems/task-scheduler/) | Medium |
| 5   | [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) | Medium |
| 6   | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium |
| 7   | [Candy Crush](https://leetcode.com/problems/candy-crush/) | Medium |
| 8   | [Can Place Flowers](https://leetcode.com/problems/can-place-flowers/) | Medium |
| 9   | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 10  | [Minimum Cost to Connect Sticks](https://leetcode.com/problems/minimum-cost-to-connect-sticks/) | Medium |
| 11  | [Gas Station](https://leetcode.com/problems/gas-station/) | Medium |
| 12  | [Jump Game III](https://leetcode.com/problems/jump-game-iii/) | Medium |
| 13  | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium |
| 14  | [Insert Interval](https://leetcode.com/problems/insert-interval/) | Medium |
| 15  | [Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium |
| 16  | [Distribute Candies](https://leetcode.com/problems/distribute-candies/) | Medium |
| 17  | [Rearrange Words in a Sentence](https://leetcode.com/problems/rearrange-words-in-a-sentence/) | Medium |
| 18  | [Minimum Cost to Hire K Workers](https://leetcode.com/problems/minimum-cost-to-hire-k-workers/) | Medium |
| 19  | [Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/) | Medium |
| 20  | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium |
| 21  | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium |
| 22  | [Course Schedule III](https://leetcode.com/problems/course-schedule-iii/) | Medium |
| 23  | [Best Time to Buy and Sell Stock III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/) | Medium |
| 24  | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Medium |
| 25  | [Account Merge](https://leetcode.com/problems/account-merge/) | Medium |
| 26  | [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Medium |
| 27  | [Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium |
| 28  | [House Robber II](https://leetcode.com/problems/house-robber-ii/) | Medium |
| 29  | [Word Break](https://leetcode.com/problems/word-break/) | Medium |
| 30  | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium |

---

### 🔴 Hard
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 2   | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 3   | [Jump Game III](https://leetcode.com/problems/jump-game-iii/) | Hard |
| 4   | [Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Hard |
| 5   | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 6   | [N-Queens II](https://leetcode.com/problems/n-queens-ii/) | Hard |
| 7   | [Maximum Product of Three Numbers](https://leetcode.com/problems/maximum-product-of-three-numbers/) | Hard |
| 8   | [Integer Break](https://leetcode.com/problems/integer-break/) | Hard |
| 9   | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 10  | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 11  | [Jump Game IV](https://leetcode.com/problems/jump-game-iv/) | Hard |
| 12  | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Hard |
| 13  | [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/) | Hard |
| 14  | [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/) | Hard |
| 15  | [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard |
| 16  | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 17  | [Falling Squares](https://leetcode.com/problems/falling-squares/) | Hard |
| 18  | [Maximal Network Rank](https://leetcode.com/problems/maximal-network-rank/) | Hard |
| 19  | [Smallest Range II](https://leetcode.com/problems/smallest-range-ii/) | Hard |
| 20  | [Dota2 Senate](https://leetcode.com/problems/dota2-senate/) | Hard |
| 21  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 22  | [Simplify Path](https://leetcode.com/problems/simplify-path/) | Hard |
| 23  | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Hard |
| 24  | [K-th Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Hard |
| 25  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 26  | [Jump Game VI](https://leetcode.com/problems/jump-game-vi/) | Hard |
| 27  | [Integer to English Words](https://leetcode.com/problems/integer-to-english-words/) | Hard |
| 28  | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 29  | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Hard |
| 30  | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |

### 🟢 Easy
### 🟡 Medium
### 🔴 Hard

## **Dynamic Programming (DP)**

### **Easy**
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy |
| 2   | [House Robber](https://leetcode.com/problems/house-robber/) | Easy |
| 3   | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy |
| 4   | [Fibonacci Number](https://leetcode.com/problems/fibonacci-number/) | Easy |
| 5   | [House Robber II](https://leetcode.com/problems/house-robber-ii/) | Easy |
| 6   | [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Easy |
| 7   | [Climbing Stairs - Variations](https://leetcode.com/problems/climbing-stairs-variations/) | Easy |
| 8   | [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Easy |
| 9   | [Unique Paths](https://leetcode.com/problems/unique-paths/) | Easy |
| 10  | [Ugly Number II](https://leetcode.com/problems/ugly-number-ii/) | Easy |
| 11  | [Coin Change](https://leetcode.com/problems/coin-change/) | Easy |
| 12  | [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | Easy |
| 13  | [Jump Game](https://leetcode.com/problems/jump-game/) | Easy |
| 14  | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Easy |
| 15  | [Divide Two Integers](https://leetcode.com/problems/divide-two-integers/) | Easy |
| 16  | [Number of Ways to Stay in the Same Place After Some Steps](https://leetcode.com/problems/number-of-ways-to-stay-in-the-same-place-after-some-steps/) | Easy |
| 17  | [K-th Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Easy |
| 18  | [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) | Easy |
| 19  | [Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy |
| 20  | [Integer Break](https://leetcode.com/problems/integer-break/) | Easy |
| 21  | [Maximum Length of Pair Chain](https://leetcode.com/problems/maximum-length-of-pair-chain/) | Easy |
| 22  | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 23  | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Easy |
| 24  | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Easy |
| 25  | [Coin Change 2](https://leetcode.com/problems/coin-change-2/) | Easy |
| 26  | [Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Easy |
| 27  | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Easy |
| 28  | [Climbing Stairs with Memoization](https://leetcode.com/problems/climbing-stairs-with-memoization/) | Easy |
| 29  | [Path Sum III](https://leetcode.com/problems/path-sum-iii/) | Easy |
| 30  | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy |
| 31  | [Single Number](https://leetcode.com/problems/single-number/) | Easy |
| 32  | [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy |
| 33  | [Palindrome Number](https://leetcode.com/problems/palindrome-number/) | Easy |
| 34  | [Excel Sheet Column Number](https://leetcode.com/problems/excel-sheet-column-number/) | Easy |
| 35  | [Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square/) | Easy |
| 36  | [Divide Two Integers](https://leetcode.com/problems/divide-two-integers/) | Easy |
| 37  | [Power of Two](https://leetcode.com/problems/power-of-two/) | Easy |
| 38  | [Happy Number](https://leetcode.com/problems/happy-number/) | Easy |
| 39  | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Easy |
| 40  | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Easy |

---

### **Medium**
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Word Break](https://leetcode.com/problems/word-break/) | Medium |
| 2   | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium |
| 3   | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium |
| 4   | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Medium |
| 5   | [Interleaving String](https://leetcode.com/problems/interleaving-string/) | Medium |
| 6   | [Coin Change](https://leetcode.com/problems/coin-change/) | Medium |
| 7   | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium |
| 8   | [Edit Distance](https://leetcode.com/problems/edit-distance/) | Medium |
| 9   | [House Robber III](https://leetcode.com/problems/house-robber-iii/) | Medium |
| 10  | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium |
| 11  | [Best Time to Buy and Sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | Medium |
| 12  | [Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium |
| 13  | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Medium |
| 14  | [Maximum Length of a Concatenated String with Unique Characters](https://leetcode.com/problems/maximum-length-of-a-concatenated-string-with-unique-characters/) | Medium |
| 15  | [Decode Ways](https://leetcode.com/problems/decode-ways/) | Medium |
| 16  | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Medium |
| 17  | [Find the Kth Largest Element in an Array](https://leetcode.com/problems/find-the-kth-largest-element-in-an-array/) | Medium |
| 18  | [Target Sum](https://leetcode.com/problems/target-sum/) | Medium |
| 19  | [Integer Break](https://leetcode.com/problems/integer-break/) | Medium |
| 20  | [Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/) | Medium |
| 21  | [Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) | Medium |
| 22  | [Perfect Squares](https://leetcode.com/problems/perfect-squares/) | Medium |
| 23  | [Counting Bits](https://leetcode.com/problems/counting-bits/) | Medium |
| 24  | [Subsets](https://leetcode.com/problems/subsets/) | Medium |
| 25  | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 26  | [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | Medium |
| 27  | [Unique Paths III](https://leetcode.com/problems/unique-paths-iii/) | Medium |
| 28  | [Target Sum](https://leetcode.com/problems/target-sum/) | Medium |
| 29  | [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Medium |
| 30  | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Medium |
| 31  | [Largest Square of 1s](https://leetcode.com/problems/largest-square-of-1s/) | Medium |
| 32  | [Maximum Product of Word Lengths](https://leetcode.com/problems/maximum-product-of-word-lengths/) | Medium |
| 33  | [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) | Medium |
| 34  | [Count of Substrings with All Vowels Present](https://leetcode.com/problems/count-of-substrings-with-all-vowels-present/) | Medium |
| 35  | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Medium |
| 36  | [Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Medium |
| 37  | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium |
| 38  | [Count All Valid Pickup and Delivery Options](https://leetcode.com/problems/count-all-valid-pickup-and-delivery-options/) | Medium |
| 39  | [The Maze II](https://leetcode.com/problems/the-maze-ii/) | Medium |
| 40  | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Medium |

---

### **Hard**
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 2   | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 3   | [Edit Distance](https://leetcode.com/problems/edit-distance/) | Hard |
| 4   | [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Hard |
| 5   | [Scramble String](https://leetcode.com/problems/scramble-string/) | Hard |
| 6   | [Burst Balloons](https://leetcode.com/problems/burst-balloons/) | Hard |
| 7   | [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard |
| 8   | [Maximum Sum of 3 Non-Overlapping Subarrays](https://leetcode.com/problems/maximum-sum-of-3-non-overlapping-subarrays/) | Hard |
| 9   | [Count All Valid Pickup and Delivery Options](https://leetcode.com/problems/count-all-valid-pickup-and-delivery-options/) | Hard |
| 10  | [Palindrome Partitioning III](https://leetcode.com/problems/palindrome-partitioning-iii/) | Hard |
| 11  | [Shortest Supersequence](https://leetcode.com/problems/shortest-supersequence/) | Hard |
| 12  | [Minimum Number of Refueling Stops](https://leetcode.com/problems/minimum-number-of-refueling-stops/) | Hard |
| 13  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 14  | [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |
| 15  | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 16  | [Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/) | Hard |
| 17  | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard |
| 18  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 19  | [Knapsack Problem](https://leetcode.com/problems/knapsack-problem/) | Hard |
| 20  | [Optimal Account Balancing](https://leetcode.com/problems/optimal-account-balancing/) | Hard |
| 21  | [Maximum Number of Points with Cost](https://leetcode.com/problems/maximum-number-of-points-with-cost/) | Hard |
| 22  | [Longest Palindromic Subsequence II](https://leetcode.com/problems/longest-palindromic-subsequence-ii/) | Hard |
| 23  | [Remove Boxes](https://leetcode.com/problems/remove-boxes/) | Hard |
| 24  | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 25  | [Count Palindromes](https://leetcode.com/problems/count-palindromes/) | Hard |
| 26  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 27  | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 28  | [Minimum Cost to Hire K Workers](https://leetcode.com/problems/minimum-cost-to-hire-k-workers/) | Hard |
| 29  | [Egg Drop Problem](https://leetcode.com/problems/egg-drop-problem/) | Hard |
| 30  | [Optimal Palindrome Partitioning](https://leetcode.com/problems/optimal-palindrome-partitioning/) | Hard |
| 31  | [Minimum Path Sum in Triangle](https://leetcode.com/problems/minimum-path-sum-in-triangle/) | Hard |
| 32  | [Egg Drop Problem](https://leetcode.com/problems/egg-drop-problem/) | Hard |
| 33  | [Knapsack Problem](https://leetcode.com/problems/knapsack-problem/) | Hard |
| 34  | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 35  | [Palindrome Partitioning III](https://leetcode.com/problems/palindrome-partitioning-iii/) | Hard |
| 36  | [Burst Balloons](https://leetcode.com/problems/burst-balloons/) | Hard |
| 37  | [Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) | Hard |
| 38  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 39  | [Longest Palindromic Substring II](https://leetcode.com/problems/longest-palindromic-substring-ii/) | Hard |
| 40  | [Optimal Palindrome Partitioning](https://leetcode.com/problems/optimal-palindrome-partitioning/) | Hard |


### **Extra Challenges**
| No  | Problem | Difficulty |
|-----|---------|------------|
| 1   | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 2   | [Maximum Sum of 3 Non-Overlapping Subarrays](https://leetcode.com/problems/maximum-sum-of-3-non-overlapping-subarrays/) | Hard |
| 3   | [Super Ugly Number](https://leetcode.com/problems/super-ugly-number/) | Hard |
| 4   | [Maximum Number of Points with Cost](https://leetcode.com/problems/maximum-number-of-points-with-cost/) | Hard |
| 5   | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Hard |
| 6   | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 7   | [Remove Boxes](https://leetcode.com/problems/remove-boxes/) | Hard |
| 8   | [Minimum Cost to Hire K Workers](https://leetcode.com/problems/minimum-cost-to-hire-k-workers/) | Hard |
| 9   | [Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/) | Hard |
| 10  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |


# 🚪 Sliding Window 

Sliding Window is a commonly used technique for solving array and string problems involving subarrays/substrings, maximum/minimums, or fixed/variable window sizes.
# Sliding Window Problems

## 🟢 Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy |
| 2  | [Reverse String](https://leetcode.com/problems/reverse-string/) | Easy |
| 3  | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy |
| 4  | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy |
| 5  | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy |
| 6  | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy |
| 7  | [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy |
| 8  | [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) | Easy |
| 9  | [Remove Element](https://leetcode.com/problems/remove-element/) | Easy |
| 10 | [First Bad Version](https://leetcode.com/problems/first-bad-version/) | Easy |
| 11 | [Binary Search](https://leetcode.com/problems/binary-search/) | Easy |
| 12 | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Easy |
| 13 | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy |
| 14 | [Ransom Note](https://leetcode.com/problems/ransom-note/) | Easy |
| 15 | [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy |
| 16 | [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy |
| 17 | [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy |
| 18 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Easy |
| 19 | [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) | Easy |
| 20 | [3Sum](https://leetcode.com/problems/3sum/) | Easy |
| 21 | [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Easy |
| 22 | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Easy |
| 23 | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Easy |
| 24 | [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy |
| 25 | [Maximum Length of Repeated Subarray](https://leetcode.com/problems/maximum-length-of-repeated-subarray/) | Easy |
| 26 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 27 | [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Easy |
| 28 | [Search Insert Position](https://leetcode.com/problems/search-insert-position/) | Easy |
| 29 | [Majority Element](https://leetcode.com/problems/majority-element/) | Easy |
| 30 | [Rotate Image](https://leetcode.com/problems/rotate-image/) | Easy |

## 🟡 Medium

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Medium |
| 2  | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium |
| 3  | [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) | Medium |
| 4  | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 5  | [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) | Medium |
| 6  | [Permutations II](https://leetcode.com/problems/permutations-ii/) | Medium |
| 7  | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium |
| 8  | [Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Medium |
| 9  | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 10 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Medium |
| 11 | [Word Ladder](https://leetcode.com/problems/word-ladder/) | Medium |
| 12 | [Smallest Subarray with Sum Greater than or Equal to K](https://leetcode.com/problems/smallest-subarray-with-sum-greater-than-or-equal-to-k/) | Medium |
| 13 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium |
| 14 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Medium |
| 15 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Medium |
| 16 | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 17 | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Medium |
| 18 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Medium |
| 19 | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium |
| 20 | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Medium |
| 21 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Medium |
| 22 | [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/) | Medium |
| 23 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Medium |
| 24 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium |
| 25 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Medium |
| 26 | [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Medium |
| 27 | [Insert Interval](https://leetcode.com/problems/insert-interval/) | Medium |
| 28 | [Unique Paths](https://leetcode.com/problems/unique-paths/) | Medium |
| 29 | [Subsets](https://leetcode.com/problems/subsets/) | Medium |
| 30 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |

## 🔴 Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) | Hard |
| 2  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 3  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 4  | [Longest Substring with At Most Two Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/) | Hard |
| 5  | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Hard |
| 6  | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 7  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 8  | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Hard |
| 9  | [Max Sliding Window](https://leetcode.com/problems/max-sliding-window/) | Hard |
| 10 | [Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard |
| 11 | [Word Ladder III](https://leetcode.com/problems/word-ladder-iii/) | Hard |
| 12 | [Palindrome Partitioning III](https://leetcode.com/problems/palindrome-partitioning-iii/) | Hard |
| 13 | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard |
| 14 | [Scramble String](https://leetcode.com/problems/scramble-string/) | Hard |
| 15 | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 16 | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Hard |
| 17 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard |
| 18 | [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |
| 19 | [Count of Distinct Substrings](https://leetcode.com/problems/count-of-distinct-substrings/) | Hard |
| 20 | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Hard |
| 21 | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Hard |
| 22 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Hard |
| 23 | [Max Points on a Line](https://leetcode.com/problems/max-points-on-a-line/) | Hard |
| 24 | [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) | Hard |
| 25 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 26 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 27 | [Largest K-Length Subsequence](https://leetcode.com/problems/largest-k-length-subsequence/) | Hard |
| 28 | [Smallest Subtree with All the Deepest Nodes](https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/) | Hard |
| 29 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard |
| 30 | [Find Kth Smallest Element in Sorted Matrix](https://leetcode.com/problems/find-kth-smallest-element-in-sorted-matrix/) | Hard |


# 📌 Two Pointer 

# Two Pointer Problems

## 🟢 Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy |
| 2  | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy |
| 3  | [Reverse String](https://leetcode.com/problems/reverse-string/) | Easy |
| 4  | [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy |
| 5  | [Move Zeroes](https://leetcode.com/problems/move-zeroes/) | Easy |
| 6  | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy |
| 7  | [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy |
| 8  | [Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/) | Easy |
| 9  | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy |
| 10 | [Remove Element](https://leetcode.com/problems/remove-element/) | Easy |
| 11 | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Easy |
| 12 | [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) | Easy |
| 13 | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy |
| 14 | [First Bad Version](https://leetcode.com/problems/first-bad-version/) | Easy |
| 15 | [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy |
| 16 | [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy |
| 17 | [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) | Easy |
| 18 | [Two Sum II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Easy |
| 19 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 20 | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy |
| 21 | [Binary Search](https://leetcode.com/problems/binary-search/) | Easy |
| 22 | [Count Primes](https://leetcode.com/problems/count-primes/) | Easy |
| 23 | [Ransom Note](https://leetcode.com/problems/ransom-note/) | Easy |
| 24 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Easy |
| 25 | [Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/) | Easy |
| 26 | [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Easy |
| 27 | [3Sum](https://leetcode.com/problems/3sum/) | Easy |
| 28 | [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/) | Easy |
| 29 | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Easy |
| 30 | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Easy |

## 🟡 Medium

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [3Sum](https://leetcode.com/problems/3sum/) | Medium |
| 2  | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium |
| 3  | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Medium |
| 4  | [Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Medium |
| 5  | [Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium |
| 6  | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium |
| 7  | [Maximum Length of Repeated Subarray](https://leetcode.com/problems/maximum-length-of-repeated-subarray/) | Medium |
| 8  | [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) | Medium |
| 9  | [First Missing Positive](https://leetcode.com/problems/first-missing-positive/) | Medium |
| 10 | [Maximum Profit in Job Scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/) | Medium |
| 11 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium |
| 12 | [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) | Medium |
| 13 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Medium |
| 14 | [Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium |
| 15 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium |
| 16 | [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) | Medium |
| 17 | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Medium |
| 18 | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Medium |
| 19 | [Two Sum IV - Input is a BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) | Medium |
| 20 | [Find Duplicate Subtrees](https://leetcode.com/problems/find-duplicate-subtrees/) | Medium |
| 21 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Medium |
| 22 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Medium |
| 23 | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Medium |
| 24 | [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium |
| 25 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium |
| 26 | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium |
| 27 | [Maximum Subarray Sum with One Deletion](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/) | Medium |
| 28 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Medium |
| 29 | [Subsets II](https://leetcode.com/problems/subsets-ii/) | Medium |
| 30 | [Rotate Image](https://leetcode.com/problems/rotate-image/) | Medium |

## 🔴 Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/) | Hard |
| 2  | [Wildcards Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |
| 3  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 4  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 5  | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 6  | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 7  | [Maximal Square](https://leetcode.com/problems/maximal-square/) | Hard |
| 8  | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 9  | [Word Ladder III](https://leetcode.com/problems/word-ladder-iii/) | Hard |
| 10 | [Palindrome Partitioning III](https://leetcode.com/problems/palindrome-partitioning-iii/) | Hard |
| 11 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard |
| 12 | [Longest Increasing Subsequence II](https://leetcode.com/problems/longest-increasing-subsequence-ii/) | Hard |
| 13 | [Count and Say](https://leetcode.com/problems/count-and-say/) | Hard |
| 14 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Hard |
| 15 | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Hard |
| 16 | [Insert Interval](https://leetcode.com/problems/insert-interval/) | Hard |
| 17 | [Partition Array into Three Parts With Equal Sum](https://leetcode.com/problems/partition-array-into-three-parts-with-equal-sum/) | Hard |
| 18 | [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/) | Hard |
| 19 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Hard |
| 20 | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Hard |
| 21 | [Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) | Hard |
| 22 | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard |
| 23 | [Jump Game III](https://leetcode.com/problems/jump-game-iii/) | Hard |
| 24 | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Hard |
| 25 | [Meeting Rooms III](https://leetcode.com/problems/meeting-rooms-iii/) | Hard |
| 26 | [Subarray Sum Divisible by K](https://leetcode.com/problems/subarray-sum-divisible-by-k/) | Hard |
| 27 | [Scramble String](https://leetcode.com/problems/scramble-string/) | Hard |
| 28 | [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Hard |
| 29 | [Number of Distinct Islands](https://leetcode.com/problems/number-of-distinct-islands/) | Hard |
| 30 | [Count of Distinct Substrings](https://leetcode.com/problems/count-of-distinct-substrings/) | Hard |

✅ **Pro Tip:** Many of these problems can be solved with both **Two Pointer** and **Sliding Window** strategies, so master both patterns in tandem!

---

# Prefix Sum Problems

## 🟢 Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Prefix Sum](https://leetcode.com/problems/prefix-sum/) | Easy |
| 2  | [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | Easy |
| 3  | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy |
| 4  | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Easy |
| 5  | [Maximum Subarray Sum Equals K](https://leetcode.com/problems/maximum-subarray-sum-equals-k/) | Easy |
| 6  | [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Easy |
| 7  | [Check If a Number is Majority Element in a Sorted Array](https://leetcode.com/problems/check-if-a-number-is-majority-element-in-a-sorted-array/) | Easy |
| 8  | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Easy |
| 9  | [Range Sum Query – Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Easy |
| 10 | [Sum of All Odd Length Subarrays](https://leetcode.com/problems/sum-of-all-odd-length-subarrays/) | Easy |
| 11 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Easy |
| 12 | [Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) | Easy |
| 13 | [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) | Easy |
| 14 | [Sum of Subarrays](https://leetcode.com/problems/sum-of-subarrays/) | Easy |
| 15 | [Subarray with Sum 0](https://leetcode.com/problems/subarray-with-sum-0/) | Easy |
| 16 | [Find the Smallest Subarray With Sum Greater Than or Equal to K](https://leetcode.com/problems/find-the-smallest-subarray-with-sum-greater-than-or-equal-to-k/) | Easy |
| 17 | [Prefix Sum Array](https://leetcode.com/problems/prefix-sum-array/) | Easy |
| 18 | [Find the Total Sum of a Range](https://leetcode.com/problems/find-the-total-sum-of-a-range/) | Easy |
| 19 | [Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Easy |
| 20 | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Easy |
| 21 | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy |
| 22 | [Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) | Easy |
| 23 | [Find the Largest Value in Each Tree Row](https://leetcode.com/problems/find-the-largest-value-in-each-tree-row/) | Easy |
| 24 | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy |
| 25 | [Subarray with Sum 0](https://leetcode.com/problems/subarray-with-sum-0/) | Easy |
| 26 | [Range Sum Query - 2D Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/) | Easy |
| 27 | [Find All Duplicates in an Array](https://leetcode.com/problems/find-all-duplicates-in-an-array/) | Easy |
| 28 | [Find the Missing Number](https://leetcode.com/problems/find-the-missing-number/) | Easy |
| 29 | [Equal Row and Column Pairs](https://leetcode.com/problems/equal-row-and-column-pairs/) | Easy |
| 30 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy |

## 🟡 Medium

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/) | Medium |
| 2  | [Prefix Sum 2](https://leetcode.com/problems/prefix-sum-2/) | Medium |
| 3  | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 4  | [Number of Subarrays with Bounded Maximum](https://leetcode.com/problems/number-of-subarrays-with-bounded-maximum/) | Medium |
| 5  | [Contiguous Subarray](https://leetcode.com/problems/contiguous-subarray/) | Medium |
| 6  | [Range Sum Query 2D - Mutable](https://leetcode.com/problems/range-sum-query-2d-mutable/) | Medium |
| 7  | [Maximum Subarray Sum](https://leetcode.com/problems/maximum-subarray-sum/) | Medium |
| 8  | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 9  | [Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Medium |
| 10 | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Medium |
| 11 | [Maximum Subarray Sum with One Deletion](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/) | Medium |
| 12 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 13 | [Count Good Triplets](https://leetcode.com/problems/count-good-triplets/) | Medium |
| 14 | [Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) | Medium |
| 15 | [Number of Subarrays with Sum 0](https://leetcode.com/problems/number-of-subarrays-with-sum-0/) | Medium |
| 16 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 17 | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 18 | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Medium |
| 19 | [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Medium |
| 20 | [Find the Smallest Subarray With Sum Greater Than or Equal to K](https://leetcode.com/problems/find-the-smallest-subarray-with-sum-greater-than-or-equal-to-k/) | Medium |
| 21 | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Medium |
| 22 | [Count Subarrays with Sum 0](https://leetcode.com/problems/count-subarrays-with-sum-0/) | Medium |
| 23 | [Find the Largest Subarray with Sum Less than K](https://leetcode.com/problems/find-the-largest-subarray-with-sum-less-than-k/) | Medium |
| 24 | [Find the Maximum Subarray Sum](https://leetcode.com/problems/find-the-maximum-subarray-sum/) | Medium |
| 25 | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Medium |
| 26 | [Total Subarrays Divisible by K](https://leetcode.com/problems/total-subarrays-divisible-by-k/) | Medium |
| 27 | [Find Kth Smallest Element](https://leetcode.com/problems/find-kth-smallest-element/) | Medium |
| 28 | [Minimum Subarray Sum](https://leetcode.com/problems/minimum-subarray-sum/) | Medium |
| 29 | [Maximum Size Subarray Sum Equals k](https://leetcode.com/problems/maximum-size-subarray-sum-equals-k/) | Medium |
| 30 | [Minimum Subarray](https://leetcode.com/problems/minimum-subarray/) | Medium |

## 🔴 Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard |
| 2  | [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Hard |
| 3  | [Count of Subarrays](https://leetcode.com/problems/count-of-subarrays/) | Hard |
| 4  | [Range Sum Query - 2D Mutable](https://leetcode.com/problems/range-sum-query-2d-mutable/) | Hard |
| 5  | [Find the Smallest Subarray With Sum Greater Than or Equal to K](https://leetcode.com/problems/find-the-smallest-subarray-with-sum-greater-than-or-equal-to-k/) | Hard |
| 6  | [Maximum Subarray Sum with One Deletion](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/) | Hard |
| 7  | [Smallest Subarray with Sum Greater than K](https://leetcode.com/problems/smallest-subarray-with-sum-greater-than-k/) | Hard |
| 8  | [Prefix Sum Query](https://leetcode.com/problems/prefix-sum-query/) | Hard |
| 9  | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Hard |
| 10 | [Maximum Subarray Sum](https://leetcode.com/problems/maximum-subarray-sum/) | Hard |
| 11 | [Total Subarrays Divisible by K](https://leetcode.com/problems/total-subarrays-divisible-by-k/) | Hard |
| 12 | [Kth Smallest Element](https://leetcode.com/problems/kth-smallest-element/) | Hard |
| 13 | [Find the Maximum Subarray Sum](https://leetcode.com/problems/find-the-maximum-subarray-sum/) | Hard |
| 14 | [Find the Largest Subarray with Sum Less than K](https://leetcode.com/problems/find-the-largest-subarray-with-sum-less-than-k/) | Hard |
| 15 | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Hard |
| 16 | [Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Hard |
| 17 | [Count the Number of Subarrays with Sum 0](https://leetcode.com/problems/count-the-number-of-subarrays-with-sum-0/) | Hard |
| 18 | [Minimum Subarray](https://leetcode.com/problems/minimum-subarray/) | Hard |
| 19 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 20 | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard |
| 21 | [Total Subarray Sum Divisible by K](https://leetcode.com/problems/total-subarray-sum-divisible-by-k/) | Hard |
| 22 | [Find the Maximum Size Subarray](https://leetcode.com/problems/find-the-maximum-size-subarray/) | Hard |
| 23 | [Subarray Sum with Largest Sum](https://leetcode.com/problems/subarray-sum-with-largest-sum/) | Hard |
| 24 | [Subarray with Sum 0](https://leetcode.com/problems/subarray-with-sum-0/) | Hard |
| 25 | [Count Subarrays](https://leetcode.com/problems/count-subarrays/) | Hard |
| 26 | [Total Subarrays Divisible by K](https://leetcode.com/problems/total-subarrays-divisible-by-k/) | Hard |
| 27 | [Smallest Subarray With Sum Greater Than K](https://leetcode.com/problems/smallest-subarray-with-sum-greater-than-k/) | Hard |
| 28 | [Find Kth Largest Element](https://leetcode.com/problems/find-kth-largest-element/) | Hard |
| 29 | [Maximum Subarray Sum with One Deletion](https://leetcode.com/problems/maximum-subarray-sum-with-one-deletion/) | Hard |
| 30 | [Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/) | Hard |



# Bit Manipulation Problems

## 🟢 Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Single Number](https://leetcode.com/problems/single-number/) | Easy |
| 2  | [Power of Two](https://leetcode.com/problems/power-of-two/) | Easy |
| 3  | [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy |
| 4  | [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy |
| 5  | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Easy |
| 6  | [Hamming Distance](https://leetcode.com/problems/hamming-distance/) | Easy |
| 7  | [Find the Complement](https://leetcode.com/problems/find-the-complement/) | Easy |
| 8  | [Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/) | Easy |
| 9  | [Add Binary](https://leetcode.com/problems/add-binary/) | Easy |
| 10 | [Number Complement](https://leetcode.com/problems/number-complement/) | Easy |
| 11 | [Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy |
| 12 | [Missing Number](https://leetcode.com/problems/missing-number/) | Easy |
| 13 | [Flip Bit to Win](https://leetcode.com/problems/flip-bit-to-win/) | Easy |
| 14 | [Binary Gap](https://leetcode.com/problems/binary-gap/) | Easy |
| 15 | [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Easy |
| 16 | [Find the Difference](https://leetcode.com/problems/find-the-difference/) | Easy |
| 17 | [XOR Operation in an Array](https://leetcode.com/problems/xor-operation-in-an-array/) | Easy |
| 18 | [Total Hamming Distance](https://leetcode.com/problems/total-hamming-distance/) | Easy |
| 19 | [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy |
| 20 | [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy |
| 21 | [Find the Complement](https://leetcode.com/problems/find-the-complement/) | Easy |
| 22 | [Check Power of 3](https://leetcode.com/problems/check-power-of-three/) | Easy |
| 23 | [Add Digits](https://leetcode.com/problems/add-digits/) | Easy |
| 24 | [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Easy |
| 25 | [Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/) | Easy |
| 26 | [Reverse Integer](https://leetcode.com/problems/reverse-integer/) | Easy |
| 27 | [Integer to Roman](https://leetcode.com/problems/integer-to-roman/) | Easy |
| 28 | [Roman to Integer](https://leetcode.com/problems/roman-to-integer/) | Easy |
| 29 | [Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes/) | Easy |
| 30 | [Perfect Number](https://leetcode.com/problems/perfect-number/) | Easy |

## 🟡 Medium

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Single Number II](https://leetcode.com/problems/single-number-ii/) | Medium |
| 2  | [Counting Bits](https://leetcode.com/problems/counting-bits/) | Medium |
| 3  | [Find the Two Single Numbers](https://leetcode.com/problems/find-the-two-single-numbers/) | Medium |
| 4  | [Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/) | Medium |
| 5  | [Subsets](https://leetcode.com/problems/subsets/) | Medium |
| 6  | [Gray Code](https://leetcode.com/problems/gray-code/) | Medium |
| 7  | [Binary Watch](https://leetcode.com/problems/binary-watch/) | Medium |
| 8  | [Missing Number](https://leetcode.com/problems/missing-number/) | Medium |
| 9  | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium |
| 10 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium |
| 11 | [Integer Replacement](https://leetcode.com/problems/integer-replacement/) | Medium |
| 12 | [Find the Largest Integer Divisible by K](https://leetcode.com/problems/find-the-largest-integer-divisible-by-k/) | Medium |
| 13 | [Complement of Base 10 Integer](https://leetcode.com/problems/complement-of-base-10-integer/) | Medium |
| 14 | [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Medium |
| 15 | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium |
| 16 | [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium |
| 17 | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium |
| 18 | [Integer to English Words](https://leetcode.com/problems/integer-to-english-words/) | Medium |
| 19 | [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Medium |
| 20 | [Single Number III](https://leetcode.com/problems/single-number-iii/) | Medium |
| 21 | [Kth Smallest Number in Multiplication Table](https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/) | Medium |
| 22 | [Power of Four](https://leetcode.com/problems/power-of-four/) | Medium |
| 23 | [Reverse String II](https://leetcode.com/problems/reverse-string-ii/) | Medium |
| 24 | [Divide Two Integers](https://leetcode.com/problems/divide-two-integers/) | Medium |
| 25 | [Number of Enclaves](https://leetcode.com/problems/number-of-enclaves/) | Medium |
| 26 | [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium |
| 27 | [Total Hamming Distance](https://leetcode.com/problems/total-hamming-distance/) | Medium |
| 28 | [XOR Operation in an Array](https://leetcode.com/problems/xor-operation-in-an-array/) | Medium |
| 29 | [XOR Queries of a Subarray](https://leetcode.com/problems/xor-queries-of-a-subarray/) | Medium |
| 30 | [Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/) | Medium |

## 🔴 Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Hard |
| 2  | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard |
| 3  | [Max XOR of Two Numbers in an Array](https://leetcode.com/problems/max-xor-of-two-numbers-in-an-array/) | Hard |
| 4  | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | Hard |
| 5  | [Minimum XOR Sum of Two Arrays](https://leetcode.com/problems/minimum-xor-sum-of-two-arrays/) | Hard |
| 6  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 7  | [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) | Hard |
| 8  | [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Hard |
| 9  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 10 | [Smallest Subtree with All the Deepest Nodes](https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/) | Hard |
| 11 | [Scramble String](https://leetcode.com/problems/scramble-string/) | Hard |
| 12 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 13 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard |
| 14 | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Hard |
| 15 | [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |
| 16 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard |
| 17 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 18 | [Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/) | Hard |
| 19 | [Edit Distance](https://leetcode.com/problems/edit-distance/) | Hard |
| 20 | [Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) | Hard |
| 21 | [Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Hard |
| 22 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 23 | [K-th Smallest in Lexicographical Order](https://leetcode.com/problems/k-th-smallest-in-lexicographical-order/) | Hard |
| 24 | [Dungeon Game](https://leetcode.com/problems/dungeon-game/) | Hard |
| 25 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard |
| 26 | [Find Kth Smallest Element in Sorted Matrix](https://leetcode.com/problems/find-kth-smallest-element-in-sorted-matrix/) | Hard |
| 27 | [Largest K-Length Subsequence](https://leetcode.com/problems/largest-k-length-subsequence/) | Hard |
| 28 | [Smallest Subtree with All the Deepest Nodes](https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/) | Hard |
| 29 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard |
| 30 | [Find Kth Smallest Element in Sorted Matrix](https://leetcode.com/problems/find-kth-smallest-element-in-sorted-matrix/) | Hard |


# Trie Problems for Interview Preparation

## Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) | Easy |
| 2  | [Add and Search Word](https://leetcode.com/problems/add-and-search-word-data-structure-design/) | Easy |
| 3  | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Easy |
| 4  | [Prefix and Suffix Search](https://leetcode.com/problems/prefix-and-suffix-search/) | Easy |
| 5  | [Longest Word in Dictionary](https://leetcode.com/problems/longest-word-in-dictionary/) | Easy |
| 6  | [Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/) | Easy |
| 7  | [Word Pattern](https://leetcode.com/problems/word-pattern/) | Easy |
| 8  | [Find Words That Can Be Formed by Characters](https://leetcode.com/problems/find-words-that-can-be-formed-by-characters/) | Easy |
| 9  | [Implement Magic Dictionary](https://leetcode.com/problems/implement-magic-dictionary/) | Easy |
| 10 | [Detect Capital](https://leetcode.com/problems/detect-capital/) | Easy |
| 11 | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Easy |
| 12 | [Replace Words](https://leetcode.com/problems/replace-words/) | Easy |
| 13 | [Simplified Fractions](https://leetcode.com/problems/simplified-fractions/) | Easy |
| 14 | [Count and Say](https://leetcode.com/problems/count-and-say/) | Easy |
| 15 | [Longest Prefix Match](https://leetcode.com/problems/longest-prefix-match/) | Easy |
| 16 | [Alien Dictionary](https://leetcode.com/problems/alien-dictionary/) | Easy |
| 17 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Easy |
| 18 | [Minimum Length of String After Deleting Similar Ends](https://leetcode.com/problems/minimum-length-of-string-after-deleting-similar-ends/) | Easy |
| 19 | [Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Easy |
| 20 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Easy |
| 21 | [Number of Matching Subsequences](https://leetcode.com/problems/number-of-matching-subsequences/) | Easy |
| 22 | [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Easy |
| 23 | [Add Bold Tag in String](https://leetcode.com/problems/add-bold-tag-in-string/) | Easy |
| 24 | [Find Kth Largest in an Array](https://leetcode.com/problems/find-kth-largest-in-an-array/) | Easy |
| 25 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Easy |
| 26 | [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Easy |
| 27 | [Detect Capital](https://leetcode.com/problems/detect-capital/) | Easy |
| 28 | [Sum of Substrings](https://leetcode.com/problems/sum-of-substrings/) | Easy |
| 29 | [Find All Possible Recipes from Given Supplies](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/) | Easy |
| 30 | [Number of Unique Email Addresses](https://leetcode.com/problems/number-of-unique-email-addresses/) | Easy |

## Medium

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Medium |
| 2  | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Medium |
| 3  | [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) | Medium |
| 4  | [Add and Search Word](https://leetcode.com/problems/add-and-search-word-data-structure-design/) | Medium |
| 5  | [Find Words That Can Be Formed by Characters](https://leetcode.com/problems/find-words-that-can-be-formed-by-characters/) | Medium |
| 6  | [Prefix and Suffix Search](https://leetcode.com/problems/prefix-and-suffix-search/) | Medium |
| 7  | [Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/) | Medium |
| 8  | [Replace Words](https://leetcode.com/problems/replace-words/) | Medium |
| 9  | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Medium |
| 10 | [Word Pattern](https://leetcode.com/problems/word-pattern/) | Medium |
| 11 | [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Medium |
| 12 | [Simplified Fractions](https://leetcode.com/problems/simplified-fractions/) | Medium |
| 13 | [Word Search](https://leetcode.com/problems/word-search/) | Medium |
| 14 | [Add Bold Tag in String](https://leetcode.com/problems/add-bold-tag-in-string/) | Medium |
| 15 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 16 | [Word Break](https://leetcode.com/problems/word-break/) | Medium |
| 17 | [Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/) | Medium |
| 18 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium |
| 19 | [Design Magic Dictionary](https://leetcode.com/problems/design-magic-dictionary/) | Medium |
| 20 | [Find Kth Largest in an Array](https://leetcode.com/problems/find-kth-largest-in-an-array/) | Medium |
| 21 | [Count and Say](https://leetcode.com/problems/count-and-say/) | Medium |
| 22 | [Detect Capital](https://leetcode.com/problems/detect-capital/) | Medium |
| 23 | [Number of Matching Subsequences](https://leetcode.com/problems/number-of-matching-subsequences/) | Medium |
| 24 | [Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Medium |
| 25 | [Simplified Fractions](https://leetcode.com/problems/simplified-fractions/) | Medium |
| 26 | [Find All Possible Recipes from Given Supplies](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/) | Medium |
| 27 | [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Medium |
| 28 | [Sum of Substrings](https://leetcode.com/problems/sum-of-substrings/) | Medium |
| 29 | [Maximum Product of Word Lengths](https://leetcode.com/problems/maximum-product-of-word-lengths/) | Medium |
| 30 | [Design a Trie](https://leetcode.com/problems/design-a-trie/) | Medium |

## Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Word Break II](https://leetcode.com/problems/word-break-ii/) | Hard |
| 2  | [Palindrome Pairs](https://leetcode.com/problems/palindrome-pairs/) | Hard |
| 3  | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Hard |
| 4  | [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Hard |
| 5  | [Add and Search Word](https://leetcode.com/problems/add-and-search-word-data-structure-design/) | Hard |
| 6  | [Add Bold Tag in String](https://leetcode.com/problems/add-bold-tag-in-string/) | Hard |
| 7  | [Find Words That Can Be Formed by Characters](https://leetcode.com/problems/find-words-that-can-be-formed-by-characters/) | Hard |
| 8  | [Longest Word in Dictionary](https://leetcode.com/problems/longest-word-in-dictionary/) | Hard |
| 9  | [Word Pattern II](https://leetcode.com/problems/word-pattern-ii/) | Hard |
| 10 | [Count and Say](https://leetcode.com/problems/count-and-say/) | Hard |
| 11 | [Prefix and Suffix Search](https://leetcode.com/problems/prefix-and-suffix-search/) | Hard |
| 12 | [Implement Trie](https://leetcode.com/problems/implement-trie-prefix-tree/) | Hard |
| 13 | [Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/) | Hard |
| 14 | [Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/) | Hard |
| 15 | [Number of Matching Subsequences](https://leetcode.com/problems/number-of-matching-subsequences/) | Hard |
| 16 | [Design Magic Dictionary](https://leetcode.com/problems/design-magic-dictionary/) | Hard |
| 17 | [Minimum Length of String After Deleting Similar Ends](https://leetcode.com/problems/minimum-length-of-string-after-deleting-similar-ends/) | Hard |
| 18 | [Is Subsequence](https://leetcode.com/problems/is-subsequence/) | Hard |
| 19 | [Word Search III](https://leetcode.com/problems/word-search-iii/) | Hard |
| 20 | [Palindrome Pairs II](https://leetcode.com/problems/palindrome-pairs-ii/) | Hard |
| 21 | [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) | Hard |
| 22 | [Design Prefix Tree](https://leetcode.com/problems/design-prefix-tree/) | Hard |
| 23 | [Prefix Matching with Trie](https://leetcode.com/problems/prefix-matching-with-trie/) | Hard |
| 24 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Hard |
| 25 | [Find Kth Largest in an Array](https://leetcode.com/problems/find-kth-largest-in-an-array/) | Hard |
| 26 | [Trie and Dictionary Matching](https://leetcode.com/problems/trie-and-dictionary-matching/) | Hard |
| 27 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard |
| 28 | [Find All Possible Recipes from Given Supplies](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/) | Hard |
| 29 | [Word Break](https://leetcode.com/problems/word-break/) | Hard |
| 30 | [Wildcard Matching](https://leetcode.com/problems/wildcard-matching/) | Hard |


# Segment Tree Problems for Interview Preparation

## Easy

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Easy |
| 2  | [Range Sum Query 2D - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/) | Easy |
| 3  | [Range Minimum Query - Immutable](https://leetcode.com/problems/range-minimum-query-immutable/) | Easy |
| 4  | [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Easy |
| 5  | [Prefix Sum Array](https://leetcode.com/problems/prefix-sum-array/) | Easy |
| 6  | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Easy |
| 7  | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Easy |
| 8  | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Easy |
| 9  | [Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) | Easy |
| 10 | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Easy |
| 11 | [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Easy |
| 12 | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Easy |
| 13 | [Max Sum of Rectangle No Larger Than K](https://leetcode.com/problems/max-sum-of-rectangle-no-larger-than-k/) | Easy |
| 14 | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Easy |
| 15 | [Min Stack](https://leetcode.com/problems/min-stack/) | Easy |
| 16 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy |
| 17 | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Easy |
| 18 | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Easy |
| 19 | [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) | Easy |
| 20 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Easy |
| 21 | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | Easy |
| 22 | [House Robber](https://leetcode.com/problems/house-robber/) | Easy |
| 23 | [House Robber II](https://leetcode.com/problems/house-robber-ii/) | Easy |
| 24 | [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy |
| 25 | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | Easy |
| 26 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | Easy |
| 27 | [Integer Break](https://leetcode.com/problems/integer-break/) | Easy |
| 28 | [Non-decreasing Subsequences](https://leetcode.com/problems/non-decreasing-subsequences/) | Easy |
| 29 | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy |
| 30 | [Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) | Easy |

## Medium

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Range Sum Query 2D - Mutable](https://leetcode.com/problems/range-sum-query-2d-mutable/) | Medium |
| 2  | [Range Minimum Query](https://leetcode.com/problems/range-minimum-query/) | Medium |
| 3  | [Segment Tree Range Sum](https://leetcode.com/problems/segment-tree-range-sum/) | Medium |
| 4  | [Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/) | Medium |
| 5  | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 6  | [Maximum Product of Three Numbers](https://leetcode.com/problems/maximum-product-of-three-numbers/) | Medium |
| 7  | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Medium |
| 8  | [Maximum Sum of Non-overlapping Subarrays](https://leetcode.com/problems/maximum-sum-of-non-overlapping-subarrays/) | Medium |
| 9  | [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium |
| 10 | [The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/) | Medium |
| 11 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Medium |
| 12 | [Partition Labels](https://leetcode.com/problems/partition-labels/) | Medium |
| 13 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Medium |
| 14 | [Number of Subarrays with Bounded Maximum](https://leetcode.com/problems/number-of-subarrays-with-bounded-maximum/) | Medium |
| 15 | [Maximum Length of Pair Chain](https://leetcode.com/problems/maximum-length-of-pair-chain/) | Medium |
| 16 | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Medium |
| 17 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium |
| 18 | [Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) | Medium |
| 19 | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Medium |
| 20 | [Maximum Subarray Sum Equals k](https://leetcode.com/problems/maximum-subarray-sum-equals-k/) | Medium |
| 21 | [Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/) | Medium |
| 22 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Medium |
| 23 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
| 24 | [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | Medium |
| 25 | [Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) | Medium |
| 26 | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium |
| 27 | [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) | Medium |
| 28 | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Medium |
| 29 | [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) | Medium |
| 30 | [Expression Add Operators](https://leetcode.com/problems/expression-add-operators/) | Medium |

### Hard

| NO | Problem | Difficulty |
|----|---------|------------|
| 1  | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 2  | [Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/) | Hard |
| 3  | [Range Minimum Query - Immutable](https://leetcode.com/problems/range-minimum-query-immutable/) | Hard |
| 4  | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Hard |
| 5  | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 6  | [Shortest Subarray with Sum at Least K](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) | Hard |
| 7  | [Reverse Pairs](https://leetcode.com/problems/reverse-pairs/) | Hard |
| 8  | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Hard |
| 9  | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Hard |
| 10 | [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) | Hard |
| 11 | [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) | Hard |
| 12 | [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard |
| 13 | [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) | Hard |
| 14 | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Hard |
| 15 | [Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) | Hard |
| 16 | [Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) | Hard |
| 17 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 18 | [Find the Kth Largest Sum of a Subarray](https://leetcode.com/problems/find-the-kth-largest-sum-of-a-subarray/) | Hard |
| 19 | [N-Queens](https://leetcode.com/problems/n-queens/) | Hard |
| 20 | [Word Ladder II](https://leetcode.com/problems/word-ladder-ii/) | Hard |
| 21 | [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Hard |
| 22 | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Hard |
| 23 | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
| 24 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard |
| 25 | [Range Minimum Query](https://leetcode.com/problems/range-minimum-query/) | Hard |
| 26 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | Hard |
| 27 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 28 | [Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/) | Hard |
| 29 | [Zigzag Conversion](https://leetcode.com/problems/zigzag-conversion/) | Hard |
| 30 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Hard |

