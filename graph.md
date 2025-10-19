# 🕸️ Graph Mastery

Your ultimate guide to mastering **Graph Data Structures and Algorithms** — from representation and traversal to shortest paths, topological sorting, and disjoint set union (DSU).  
This roadmap takes you from **graph basics → connected components → shortest paths → MST → advanced algorithms** like Tarjan’s and Kosaraju’s.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Graph Representation & Basics](#-graph-representation--basics)
3. [Traversal & Connected Components](#-traversal--connected-components)
4. [Cycle Detection & Bipartite Graphs](#-cycle-detection--bipartite-graphs)
5. [Topological Sorting & DAG Problems](#-topological-sorting--dag-problems)
6. [Shortest Path Algorithms](#-shortest-path-algorithms)
7. [Minimum Spanning Tree (MST) Algorithms](#-minimum-spanning-tree-mst-algorithms)
8. [Disjoint Set (Union-Find) Applications](#-disjoint-set-union-find-applications)
9. [Advanced Graph Algorithms](#-advanced-graph-algorithms)
10. [Concepts to Remember](#-concepts-to-remember)
11. [Study Plan (5 Weeks)](#-study-plan-5-weeks)
12. [Progress Tracker](#-progress-tracker)
13. [Final Goal](#-final-goal)
14. [Author Note](#-author-note)

---

## 🧠 Introduction

A **Graph** is a collection of **nodes (vertices)** connected by **edges**.  
Graphs are everywhere — from social networks, maps, and compilers to recommendation systems.

Graph problems test:

- Your **understanding of relationships and connectivity**
- Your **ability to apply BFS, DFS, and DP on graph structures**
- Your **problem-solving with shortest paths, MSTs, and SCCs**

---

## 🏗️ Graph Representation & Basics

| #   | Problem                          | Concept                                           | Status |
| --- | -------------------------------- | ------------------------------------------------- | ------ |
| 1   | **Introduction to Graphs**       | Types: Directed, Undirected, Weighted, Unweighted | ☐      |
| 2   | **Graph Representation in C++**  | Adjacency Matrix & Adjacency List                 | ☐      |
| 3   | **Graph Representation in Java** | Adjacency Matrix & Adjacency List                 | ☐      |
| 4   | **Connected Components**         | Disconnected graph handling                       | ☐      |

🧩 _Goal:_ Understand how to represent graphs in memory and visualize edges and connections.

---

## 🔄 Traversal & Connected Components

| #   | Problem                        | Concept                                  | Status |
| --- | ------------------------------ | ---------------------------------------- | ------ |
| 1   | **Breadth-First Search (BFS)** | Level-order traversal                    | ☐      |
| 2   | **Depth-First Search (DFS)**   | Recursive graph traversal                | ☐      |
| 3   | **Number of Provinces**        | Connected components in adjacency matrix | ☐      |
| 4   | **Number of Islands**          | Connected components in grid             | ☐      |
| 5   | **Flood Fill Algorithm**       | BFS/DFS grid coloring                    | ☐      |
| 6   | **Rotten Oranges**             | Multi-source BFS                         | ☐      |
| 7   | **0/1 Matrix Problem**         | BFS shortest distance from zero          | ☐      |
| 8   | **Surrounded Regions**         | Replace enclosed regions                 | ☐      |
| 9   | **Number of Enclaves**         | Edge-based BFS                           | ☐      |
| 10  | **Number of Distinct Islands** | Shape-based DFS comparison               | ☐      |

🧠 _Pattern:_ Grids = Graphs with implicit edges. BFS is best for shortest distance; DFS for exploration.

---

## 🔁 Cycle Detection & Bipartite Graphs

| #   | Problem                                  | Concept                      | Status |
| --- | ---------------------------------------- | ---------------------------- | ------ |
| 1   | **Detect Cycle (Undirected Graph, BFS)** | Use queue + parent tracking  | ☐      |
| 2   | **Detect Cycle (Undirected Graph, DFS)** | Recursive backtracking       | ☐      |
| 3   | **Bipartite Graph (BFS)**                | Alternate color assignment   | ☐      |
| 4   | **Bipartite Graph (DFS)**                | Recursive color assignment   | ☐      |
| 5   | **Detect Cycle (Directed Graph, DFS)**   | Back-edge detection          | ☐      |
| 6   | **Find Eventual Safe States (DFS)**      | Terminal node identification | ☐      |

🧩 _Goal:_ Learn color-based cycle detection and BFS/DFS parity checks for bipartite graphs.

---

## 🧭 Topological Sorting & DAG Problems

| #   | Problem                             | Concept                           | Status |
| --- | ----------------------------------- | --------------------------------- | ------ |
| 1   | **Topological Sort (DFS)**          | Recursive ordering                | ☐      |
| 2   | **Kahn’s Algorithm (BFS)**          | In-degree based ordering          | ☐      |
| 3   | **Detect Cycle in Directed Graph**  | Using topological sort (Kahn’s)   | ☐      |
| 4   | **Course Schedule I & II**          | Prerequisite task dependency      | ☐      |
| 5   | **Find Eventual Safe States (BFS)** | Topological variant               | ☐      |
| 6   | **Alien Dictionary**                | Topological sorting of characters | ☐      |
| 7   | **Shortest Path in DAG**            | Linear DP on topological order    | ☐      |

🧠 _Pattern:_ Topological sort applies to **Directed Acyclic Graphs (DAGs)**.  
Use DFS or Kahn’s algorithm depending on recursion or queue preference.

---

## 🛣️ Shortest Path Algorithms

| #   | Problem                                                 | Concept                                    | Status |
| --- | ------------------------------------------------------- | ------------------------------------------ | ------ |
| 1   | **Shortest Path in Undirected Graph with Unit Weights** | BFS traversal                              | ☐      |
| 2   | **Word Ladder I**                                       | Shortest transformation sequence           | ☐      |
| 3   | **Word Ladder II (Basic)**                              | Generate all shortest transformation paths | ☐      |
| 4   | **Word Ladder II (Optimized)**                          | Bidirectional BFS + backtracking           | ☐      |
| 5   | **Dijkstra’s Algorithm (Using Priority Queue)**         | Single-source shortest path                | ☐      |
| 6   | **Dijkstra’s Algorithm (Using Set)**                    | Alternate approach                         | ☐      |
| 7   | **Dijkstra’s Explanation (Why PQ not Q)**               | Complexity analysis                        | ☐      |
| 8   | **Print Shortest Path (Dijkstra’s)**                    | Store parent array                         | ☐      |
| 9   | **Shortest Distance in Binary Maze**                    | BFS variant                                | ☐      |
| 10  | **Path with Minimum Effort**                            | Min-heap based path relaxation             | ☐      |
| 11  | **Cheapest Flights Within K Stops**                     | BFS + cost tracking                        | ☐      |
| 12  | **Minimum Multiplications to Reach End**                | BFS in number graph                        | ☐      |
| 13  | **Network Delay Time**                                  | Dijkstra’s variant                         | ☐      |
| 14  | **Number of Ways to Arrive at Destination**             | Dijkstra + path counting                   | ☐      |
| 15  | **Bellman-Ford Algorithm**                              | Negative edge handling                     | ☐      |
| 16  | **Floyd-Warshall Algorithm**                            | All-pairs shortest paths                   | ☐      |
| 17  | **Find City with Smallest Reachable Neighbors**         | Floyd-Warshall application                 | ☐      |

🧠 _Pattern:_

- BFS → Unweighted graphs
- Dijkstra → Weighted positive edges
- Bellman-Ford → Handles negative edges
- Floyd-Warshall → All-pairs distances

---

## 🌉 Minimum Spanning Tree (MST) Algorithms

| #   | Problem                             | Concept                   | Status |
| --- | ----------------------------------- | ------------------------- | ------ |
| 1   | **MST Theory**                      | Concept of spanning trees | ☐      |
| 2   | **Prim’s Algorithm (Using PQ)**     | Greedy MST                | ☐      |
| 3   | **Kruskal’s Algorithm (Using DSU)** | Edge-based MST            | ☐      |

🧩 _Goal:_ Understand **Greedy selection** and how **Union-Find** ensures acyclic MSTs.

---

## ⚙️ Disjoint Set (Union-Find) Applications

| #   | Problem                                      | Concept                               | Status |
| --- | -------------------------------------------- | ------------------------------------- | ------ |
| 1   | **Disjoint Set (DSU)**                       | Union by Rank, Size, Path Compression | ☐      |
| 2   | **Number of Provinces (Using DSU)**          | Connected components                  | ☐      |
| 3   | **Operations to Make Network Connected**     | Count components                      | ☐      |
| 4   | **Accounts Merge**                           | DSU-based merging                     | ☐      |
| 5   | **Number of Islands II (Online Queries)**    | DSU-based dynamic connections         | ☐      |
| 6   | **Making a Large Island**                    | DSU + adjacency logic                 | ☐      |
| 7   | **Most Stones Removed with Same Row/Column** | DSU grouping                          | ☐      |

🧠 _Pattern:_ DSU = Fast connectivity detection. Used in MSTs, dynamic networks, and grid merging.

---

## 🧩 Advanced Graph Algorithms

| #   | Problem                                      | Concept                                | Status |
| --- | -------------------------------------------- | -------------------------------------- | ------ |
| 1   | **Strongly Connected Components (Kosaraju)** | Reverse graph + DFS order              | ☐      |
| 2   | **Bridges in Graph (Tarjan)**                | Discovery + low time                   | ☐      |
| 3   | **Articulation Points (Tarjan)**             | Node removal that increases components | ☐      |

🧠 _Pattern:_ Based on **DFS timestamps**, `tin[]`, and `low[]` arrays — key for critical connections.

---

## 🧭 Concepts to Remember

| Concept                      | Description                                    |
| ---------------------------- | ---------------------------------------------- |
| **Graph Types**              | Directed, Undirected, Weighted, Unweighted     |
| **Adjacency Representation** | List (O(V+E)) preferred over matrix            |
| **BFS/DFS Traversal**        | Explore level/order or depth-first             |
| **Topological Sort**         | Valid order in DAGs                            |
| **Cycle Detection**          | Color marking, parent tracking                 |
| **Shortest Path Algorithms** | BFS, Dijkstra, Bellman-Ford, Floyd-Warshall    |
| **MST**                      | Kruskal’s (edges), Prim’s (vertices)           |
| **DSU**                      | Union-Find for dynamic connectivity            |
| **Tarjan/Kosaraju**          | DFS-based low-link algorithms for SCCs/bridges |

---

## 📆 Study Plan (5 Weeks)

| Week       | Focus                      | Key Topics                             |
| ---------- | -------------------------- | -------------------------------------- |
| **Week 1** | Representation & Traversal | Graph structure, BFS, DFS              |
| **Week 2** | Components & Cycles        | Provinces, Islands, Bipartite, Cycles  |
| **Week 3** | Topological Sort & DAGs    | Kahn’s, Course Schedule, Alien Dict    |
| **Week 4** | Shortest Paths             | Dijkstra, Bellman-Ford, Floyd-Warshall |
| **Week 5** | MST & DSU & Advanced       | Kruskal, Prim, DSU, Tarjan, Kosaraju   |

🧩 _Tip:_ Always visualize — sketch graphs, color visited nodes, and track parent edges.

---

## ✅ Progress Tracker

### Graph Representation & Traversal

- [ ] Intro to Graph
- [ ] C++ Representation
- [ ] Java Representation
- [ ] BFS / DFS
- [ ] Connected Components
- [ ] Provinces / Islands / Flood Fill
- [ ] Rotten Oranges
- [ ] 0/1 Matrix
- [ ] Enclaves / Distinct Islands

### Cycle & Bipartite

- [ ] Cycle Detection (BFS/DFS)
- [ ] Bipartite Graph (BFS/DFS)
- [ ] Directed Cycle Detection
- [ ] Eventual Safe States

### Topological Sorting

- [ ] DFS Topo Sort
- [ ] Kahn’s Algo
- [ ] Detect Cycle via Topo Sort
- [ ] Course Schedule
- [ ] Alien Dictionary
- [ ] Shortest Path in DAG

### Shortest Paths

- [ ] Unweighted (BFS)
- [ ] Word Ladder I/II
- [ ] Dijkstra (PQ / Set)
- [ ] Bellman-Ford
- [ ] Floyd-Warshall
- [ ] Cheapest Flights / Network Delay / Path with Min Effort

### MST & DSU

- [ ] Prim’s Algorithm
- [ ] Kruskal’s Algorithm
- [ ] Disjoint Set (Union-Find)
- [ ] Accounts Merge / Provinces (DSU)
- [ ] Islands II / Making Large Island
- [ ] Most Stones Removed

### Advanced

- [ ] Kosaraju (SCCs)
- [ ] Tarjan (Bridges)
- [ ] Articulation Points

---

## 🎯 Final Goal

By the end of this roadmap, you will:

- Be fluent in **graph traversal, shortest path, MST, and DSU**
- Identify graph types instantly (DAG, connected, cyclic)
- Handle both **matrix-based** and **edge-list-based** problems
- Be fully interview-ready for **Google, Amazon, and Meta-level** questions 🚀

---

## 💬 Author Note

> Graphs are _not just edges and nodes_ — they’re **relationships** and **paths**.  
> Learn to think in connections, not arrays. Every graph problem is a story of flow and reachability.

Happy Coding 💻  
**#DSA #Graphs #BFS #DFS #Dijkstra #MST #DSU #TopologicalSort #InterviewPrep**
