# 🌲 Binary Trees & BST Mastery

A complete, self-contained roadmap to mastering **binary trees** and **binary search trees (BSTs)** — from fundamental traversals to advanced construction, view problems, tree-to-list transformations, and efficient BST operations.  
This file is focused purely on tree problems you should implement, understand, and add to your repo.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Basic Representations & Traversals](#-basic-representations--traversals)
3. [Iterative Traversals & Unified Traversals](#-iterative-traversals--unified-traversals)
4. [Tree Metrics & Classic Problems](#-tree-metrics--classic-problems)
5. [Views, Paths & Distance Problems](#-views-paths--distance-problems)
6. [Construct / Serialize / Special Traversals](#-construct--serialize--special-traversals)
7. [Binary Search Tree (BST) Problems](#-binary-search-tree-bst-problems)
8. [Advanced / Miscellaneous Tree Problems](#-advanced--miscellaneous-tree-problems)
9. [Concepts to Remember](#-concepts-to-remember)
10. [Study Plan (4 Weeks)](#-study-plan-4-weeks)
11. [Progress Tracker](#-progress-tracker)
12. [How to Use This File](#-how-to-use-this-file)
13. [Author Note](#-author-note)

---

## 🧠 Introduction

Trees model hierarchical data and are central to many algorithms. Start with representations and traversals, then move to problem patterns: recursion, divide-and-conquer, BFS levels, two-pointer analogues on paths, and transform problems (serialize/flatten). BSTs add ordering guarantees enabling search/selection optimizations.

---

## 🔧 Basic Representations & Traversals

| #   | Problem                                  | Notes                                                            |
| --- | ---------------------------------------- | ---------------------------------------------------------------- |
| 1   | Introduction to Trees \| Types of Trees  | Binary, BST, N-ary, complete, balanced                           |
| 2   | Binary Tree Representation in C++        | `struct TreeNode { int val; TreeNode* left; TreeNode* right; };` |
| 3   | Binary Tree Representation in Java       | `class TreeNode { int val; TreeNode left, right; }`              |
| 4   | Binary Tree Traversals (BFS / DFS)       | Conceptual: preorder, inorder, postorder, level order            |
| 5   | Preorder Traversal — C++ / Java          | Recursive implementation                                         |
| 6   | Inorder Traversal — C++ / Java           | Recursive implementation                                         |
| 7   | Postorder Traversal — C++ / Java         | Recursive implementation                                         |
| 8   | Level Order Traversal (BFS) — C++ / Java | Queue-based BFS                                                  |

---

## ⚙️ Iterative Traversals & Unified Traversals

| #   | Problem                                         | Notes                                        |
| --- | ----------------------------------------------- | -------------------------------------------- |
| 1   | Iterative Preorder (Stack) — C++ / Java         | Use stack, push right then left              |
| 2   | Iterative Inorder (Stack) — C++ / Java          | Push left spine, process nodes               |
| 3   | Iterative Postorder using 2 Stacks — C++ / Java | Reverse of modified preorder                 |
| 4   | Iterative Postorder using 1 Stack — C++ / Java  | Track last visited node                      |
| 5   | Preorder/Inorder/Postorder in One Traversal     | Use stack of pairs/state to output all three |

---

## 📏 Tree Metrics & Classic Problems

| #   | Problem                                     | Notes                                       |
| --- | ------------------------------------------- | ------------------------------------------- |
| 1   | Maximum Depth / Height                      | DFS recursion returning max height          |
| 2   | Check for Balanced Binary Tree              | Height-checking with early stop             |
| 3   | Diameter of Binary Tree                     | Height-based DP (max of left+right)         |
| 4   | Maximum Path Sum in Binary Tree             | Track max via postorder and negative values |
| 5   | Check if Two Trees are Identical            | Recursively compare subtrees                |
| 6   | Check for Symmetric Trees                   | Mirror-check recursive/iterative            |
| 7   | Count total Nodes in a COMPLETE Binary Tree | O(log² n) method using subtree heights      |

---

## 👀 Views, Paths & Distance Problems

| #   | Problem                                     | Notes                                   |
| --- | ------------------------------------------- | --------------------------------------- |
| 1   | Zig-Zag / Spiral Traversal                  | Alternate level direction               |
| 2   | Boundary Traversal                          | Left boundary, leaves, right boundary   |
| 3   | Vertical Order Traversal                    | Map by horizontal distance (hd)         |
| 4   | Top View / Bottom View                      | Use hd and first/last vertically        |
| 5   | Right View / Left View                      | Level-order pick extreme node           |
| 6   | Print Root-to-Node Path                     | Backtracking or parent map              |
| 7   | Lowest Common Ancestor (LCA) in Binary Tree | Recursion returns lca candidate         |
| 8   | Maximum Width of Binary Tree                | Track index-based width per level       |
| 9   | Children Sum Property (O(N))                | Check node value equals sum of children |
| 10  | Print nodes at distance K from a node       | Convert to parent pointers + BFS        |
| 11  | Minimum time to BURN the tree from a node   | BFS from source using parent links      |

---

## 🧩 Construct / Serialize / Special Traversals

| #   | Problem                                      | Notes                                        |
| --- | -------------------------------------------- | -------------------------------------------- |
| 1   | Requirements for Unique Binary Tree (theory) | When traversals uniquely identify tree       |
| 2   | Construct from Preorder & Inorder            | Recursion with index ranges                  |
| 3   | Construct from Postorder & Inorder           | Recursion with index ranges                  |
| 4   | Serialize and Deserialize Binary Tree        | Use preorder + null markers or level-order   |
| 5   | Morris Traversal (Preorder / Inorder)        | O(1) space threaded tree traversal           |
| 6   | Flatten Binary Tree to Linked List           | 3 approaches: recursion, stack, Morris-style |
| 7   | Print all nodes at distance K                | (duplicate of above — ensure parent mapping) |
| 8   | Binary Tree Upside Down                      | Pointer manipulation to rotate structure     |

---

## 🔎 Binary Search Tree (BST) Problems

| #   | Problem                                     | Notes                                         |
| --- | ------------------------------------------- | --------------------------------------------- |
| 1   | Introduction to BST — properties            | left < node < right                           |
| 2   | Search in BST                               | Recursion/iterative using ordering            |
| 3   | Ceil & Floor in BST                         | Walk tree maintaining candidate               |
| 4   | Insert into BST                             | Standard BST insert                           |
| 5   | Delete Node in BST                          | Replace with inorder predecessor/successor    |
| 6   | K-th Smallest / Largest in BST              | Inorder traversal / augmented tree            |
| 7   | Validate a BST                              | Range-check recursion or inorder monotonicity |
| 8   | LCA in BST                                  | Use ordering to traverse from root            |
| 9   | Construct BST from Preorder — 3 Methods     | Stack / recursion with bounds / inserting     |
| 10  | Inorder Successor / Predecessor (3 methods) | Parent pointers / stack / augmented tree      |
| 11  | BST Iterator (O(H) space)                   | Controlled inorder with stack                 |
| 12  | Two Sum in BST (pair sum K)                 | Inorder + two pointers or hashset             |
| 13  | Recover BST (swap fix)                      | Find two swapped nodes during inorder         |
| 14  | Largest BST in Binary Tree                  | Postorder returns size & bounds               |

---

## 🧠 Advanced / Miscellaneous Tree Problems

| #   | Problem                                        | Notes                                      |
| --- | ---------------------------------------------- | ------------------------------------------ |
| 1   | Binary Tree Upside Down (repeated)             | Ensure unique cover or merge earlier entry |
| 2   | Rotate / Transform problems (referenced above) | Misc pointer manipulations                 |

---

## ✍️ Concepts to Remember

- **Recursive templates**: many tree problems use a postorder pattern (`left`, `right`, `process`) returning heterogeneous info (height, sum, valid flag).
- **Parent pointer trick**: convert tree problems to graph-BFS when you need "distance from node" or burn-time.
- **Indexing for width/vertical**: use `(index)` per node or horizontal distance `hd`. Beware overflow; normalize indices by subtracting min index per level if needed.
- **Morris Traversal**: learn threaded links (temporary) to achieve O(1) extra space.
- **BST invariants**: use range constraints for validation and for efficient LCA/ceil/floor.
- **Construct-from-traversals**: preorder/postorder + inorder uniquely identify binary trees; preorder+postorder alone do not (unless additional constraints).
- **Inorder-based solutions**: many selection and order problems reduce to inorder traversal (sorted order of BST).

---

## 📆 Study Plan (4 Weeks)

| Week       | Focus                                                                                |
| ---------- | ------------------------------------------------------------------------------------ |
| **Week 1** | Representations + recursive traversals + iterative traversals                        |
| **Week 2** | Tree metrics: depth, diameter, max path sum, balanced check, symmetric check         |
| **Week 3** | Views & path problems: LCA, views, width, nodes at distance K, burn-time             |
| **Week 4** | Construct/serialize, Morris/flattens, BST operations, validation, advanced BST tasks |

Practice: 3–5 problems/day — implement recursive + iterative + one optimized variant where applicable.

---

## ✅ Progress Tracker

### Representations & Traversals

- [ ] Binary Tree Representation in C++
- [ ] Binary Tree Representation in Java
- [ ] Preorder Traversal (C++/Java)
- [ ] Inorder Traversal (C++/Java)
- [ ] Postorder Traversal (C++/Java)
- [ ] Level Order Traversal (BFS)

### Iterative & Unified Traversals

- [ ] Iterative Preorder (Stack)
- [ ] Iterative Inorder (Stack)
- [ ] Iterative Postorder (2 Stacks)
- [ ] Iterative Postorder (1 Stack)
- [ ] Pre/In/Post in One Traversal

### Metrics & Classic Problems

- [ ] Maximum Depth / Height
- [ ] Check Balanced Tree
- [ ] Diameter of Binary Tree
- [ ] Maximum Path Sum
- [ ] Identical Trees
- [ ] Symmetric Trees

### Views, Paths & Distance

- [ ] Zig-Zag Traversal
- [ ] Boundary Traversal
- [ ] Vertical Order Traversal
- [ ] Top / Bottom / Left / Right Views
- [ ] Root-to-Node Path
- [ ] Lowest Common Ancestor (LCA)
- [ ] Maximum Width
- [ ] Children Sum Property
- [ ] Nodes at Distance K
- [ ] Minimum time to BURN the tree

### Construct / Serialize / Special

- [ ] Unique Tree Requirements (theory)
- [ ] Construct from Preorder+Inorder
- [ ] Construct from Postorder+Inorder
- [ ] Serialize / Deserialize
- [ ] Morris Traversal (Inorder/Preorder)
- [ ] Flatten Tree to Linked List

### BST

- [ ] BST Intro & Search
- [ ] Ceil & Floor in BST
- [ ] Insert / Delete in BST
- [ ] K-th Smallest / Largest
- [ ] Validate BST
- [ ] LCA in BST
- [ ] Construct BST from Preorder (methods)
- [ ] Inorder Successor / Predecessor
- [ ] BST Iterator (O(H) space)
- [ ] Two Sum in BST
- [ ] Recover BST
- [ ] Largest BST in Binary Tree

---

## 🛠 How to Use This File

1. For each problem: write a clear problem statement at the top of a `.cpp` or `.java` file.
2. Implement the **recursive** solution first, then iterative and optimized versions.
3. Add a short **explanation** comment block: approach, complexity, edge-cases.
4. Unit-test with small trees and edge cases (empty tree, single-node, skewed tree).
5. Check off progress in the tracker above.

---

## 💬 Author Note

Trees are where recursion becomes intuition. Start by mastering traversal patterns and then build up to view/path problems and construction tasks. BSTs are a natural follow-up — they teach how ordering empowers logarithmic operations.

Happy Tree-Coding 🌳  
**#DSA #Trees #BST #MorrisTraversal #LCA #InterviewPrep**
