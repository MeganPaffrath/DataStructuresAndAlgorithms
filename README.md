# DataStructuresAndAlgorithms


## Outline

- [Graphs](Graphs/GRAPHS.md)

---

- **[Data Structures And Algorithms](#Data-Structures-And-Algorithms)**
- **[Data Structures](#Data-Structures)**
  - **[Lists, Stacks and Queues](#Lists-Stacks--Queues)**
  - **[Hash Tables](#Hash-Tables)**
  - **[Trees](#Trees)**
  - **[Balanced Trees](#Balanced-Trees)**
  - **[Heaps and Treaps](#Heaps-and-Treaps)**
  - **[Graphs](#Graphs)**


  <!--
  Things to Include:
  1. Intro to DS
  2. Searching and Algorithm analysis
  3. sorting
  4. Lists, stacks, Queues
  5. Hash Tables
  6. trees
  7. Balanced Trees
  8. Heaps and Treaps
  9. graphs
  10. algorithms
  11. B-Trees
  12. Represents
  13. Additional Materials

  -->

  <!-- - **[Linked lists](#Linked-Lists)** nothing yet -->
  <!-- - **[Trees, Tries, & Graphs](#Trees-Tries--Graphs)** nothing yet -->
  <!-- - **[Stacks & Queues](#Stacks--Queues)** nothing yet -->
  <!-- - **[Heaps](#Heaps)** nothing yet -->
  <!-- - **[Vectors/Array Lists](#VectorsArray-Lists)** nothing yet -->
  <!-- - **[Hash Tables](#Hash-Tables)** nothing yet -->
<!-- - **[Algorithms](#Algorithms)** nothing yet -->
  <!-- - **[Breadth-First Search](#Breadth-First-Search)** nothing yet -->
  <!-- - **[Depth-First Search](#Depth-First-Search)** nothing yet -->
  <!-- - **[Binary Search](#Binary-Search)** nothing yet -->
  <!-- - **[Merge Sort](#Merge-Sort)** nothing yet -->
  <!-- - **[Quick Sort](#Quick-Sort)** nothing yet -->
<!-- - **[Concepts](#Concepts)** nothing yet -->
  <!-- - **[Bit Manipulation](#Bit-Manipulation)** nothing yet -->
  <!-- - **[Memory (Stack vs. Heap)](#Memory-Stack-vs-Heap )** nothing yet -->
  <!-- - **[Recursion](#Recursion)** nothing yet -->
  <!-- - **[Dynamic Programming](#Dynamic-Programming)** nothing yet -->
  <!-- - **[Big O Time & Space](#Big-O-Time--Space)** nothing yet -->

<!-- ## Items To Include
- Data Structures
  - Linked lists, Trees, Tries, & Graphs, Stacks & Queues, Heaps, Vectors / Array Lists, Hash Tables
- Algorithms
  - Breadth-First Search, Depth-First Search, Binary Search, Merge Sort, Quick Sort
- Concepts
  - Bit Manipulation, Memory (Stack vs. Heap), Recursion, Dynamic Programming, Big O Time & Space
- All Items (Bold = Done)
  - 2-3-4 tree, array, binary tree, graphs, heap, hash table, linked list, ordered array, priority queues, red-black tree, stacks, queues, weighted graphs -->
---
## Data Structures And Algorithms
- A **Data Structure** is an arrangement of data. It is a special way of organizing, managing, storing, processing, and retrieving data.
- An **Algorithm** is used to manipulate data in these structures
  - A sequence of steps used to solve a problem / do a calculation
  - Examples: searching through data and sorting data

---
## Data Structures:
- Data Structures include:
  - **Record**: DS that stores subitems with names associated to each subitem
  - **Array**: Stores ordered list of items, each item directly accessible by an index
  - **Linked List**: Stores ordered list of items in nodes. Each node stores data with a pointer to the next node.
    - **Doubly Linked List**: Nodes have pointers to next and previous nodes.
  - **Trees**:
    - **Binary Tree**: Each node stores data and has 2 children. (Left child and right child)
  - **Hash Table**: Stores unordered items by mapping (or hashing) each item into a location in an array
  - **Heaps**:
      - **Max-heap**: Tree in which a node's key is >= the keys of the node's children
    -  **Min-heap**: Tree in which the node's key is <= the keys of the node's children
  - **Graph**: Represents connections among items, consists of vertices and edges
    - **Vertex**: An item in a graph
    - **Edge**: A connection between 2 vertices
  - **Tries**:
  - **Stack**:
  - **Queue**:
  - **Vectors**:
  - **Hash Tables**:
- ADTs (Abstract Data Types):
  - Stack, Queue, Linked List, Binary Tree, Red-Black Tree, 2-3-4 Tree, Hash Table, Heap, Graph

| Data Structure | Advantage | Disadvantage |
| --- | --- | --- |
| Array | Quick insertion, very fast access if index is known | Slow search, slow deletion, fixed size |
| Ordered Array | Quicker search than unsorted array | Slow insertion and deletion, fixed size |
| Stack | Provides last-int, first-out access | Slow access to other items |
| Queue | Provides first-in, first-out access | Slow access to other items |
| Linked List | Quick insertion, quick deletion | Slow Search |
| Binary Tree | Quick search, insertion, deletion (if tree remains balanced) | Deletion algorithm is complex |
| Red-black Tree | Quick search, insertion, deletion. Tree always balanced | Complex |
| 2-3-4 Tree | Quick search, insertion, deletion. Tree always balanced. Similar trees good for disk storage | Complex |
| Hash Table | Very fast access if key known. Fast insertion | Slow deletion, access if key not known, inefficient memory usage |
| Heap | Fast insertion, deletion, access to largest item | Slower access to other items |
| Graph | Models real-world situations | Some algorithms are slow and complex |



### Lists, Stacks, & Queues

- Unsorted Linked Lists
- Sorted Linked Lists
<!-- ### Trees, Tries, & Graphs -->
<!-- ### Stacks & Queues -->
<!-- ### Heaps   -->
<!-- ### Vectors/Array Lists -->


<!-- v MIDTERM 2 -->
### Hash Tables
- **Hash Table**: Sorts unordered items by mapping or hashing each item to a location in an array (or vector)
- **Big-O**:
  - insertion/removal or item: O(1)
  - More efficient than searching a list [O(N) or O(logN) for binary]
- **Key** - value used to map to an index
- **Bucket** - Each hash table array element
- A hash function computes a bucket index from the item's key
### Trees
### Balanced Trees
### Heaps and Treaps
### Graphs
<!-- ^ MIDTERM 2 -->


---
<!-- ### Algorithms
- Algorithms include:
  - Breadth-First Search, Depth-First Search, Binary Search, Merge Sort, Quick Sort -->

<!-- ### Breadth-First Search -->
<!-- ### Depth-First Search -->
<!-- ### Binary Search -->
<!-- ### Merge Sort -->
<!-- ### Quick Sort -->

---
<!-- ## Concepts
- Concepts include:
  - Bit Manipulation, Memory (Stack vs. Heap), Recursion, Dynamic Programming, Big O Time & Space -->

<!-- ### Bit Manipulation -->
<!-- ### Memory (Stack vs. Heap) -->
<!-- ### Recursion -->
<!-- ### Dynamic Programming -->
<!-- ### Big O Time & Space -->
---
