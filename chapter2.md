# Chapter 2 - common data types

## Fundamental data types

**Containers**

Types:
- Stack
- Queue 
- Table

Methods:

- Put
- Get

**Dictionaries**

Methods:

- Search
- Insert
- Delete

**Trees**

Common operations:

- Insertion
- Deletion
- Traversal
- Search

**Priority queues**

Methods:

- Insert
- Find minimum
- Delete minimum

**Special data structures:**
- String
- Geometry 
- Graph
- Set

## Tree

![img](https://upload.wikimedia.org/wikipedia/commons/4/45/Tree-data-structure.svg)

Search for a key in a balanced binary search tree takes ```O(lg(h))``` time, where ```h``` – height of the tree.

## Note from author:

In ideal world abstract data structures are easily replaceable.

Author recommends to use data structures like black-boxes with same API-s when developing an algorithm. It'll be for purpose of experiments, because replacing data structure with the proper one can significantly increase performance.

For example, if we needed to improve performance of selection sort, we could change data structure from an array to a binary search tree.

Selection sort – ```O(n^2)```

Heap sort – ```O(n lg(n))```

Heap sort is selection sort which uses another data structure – heap or binary search tree.

