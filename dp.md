# 🧮 Dynamic Programming (DP) Mastery

Your complete, self-contained roadmap to mastering **Dynamic Programming** — from fundamentals and recurrence building to advanced grid, subsequence, string, and partition DPs.  
This section is structured for clarity, with every DP category explained through real problems and optimization patterns.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [1D DP Problems](#-1d-dp-problems)
3. [2D & 3D DP on Grids](#-2d--3d-dp-on-grids)
4. [DP on Subsequences](#-dp-on-subsequences)
5. [DP on Strings](#-dp-on-strings)
6. [DP on Stocks](#-dp-on-stocks)
7. [DP on LIS Patterns](#-dp-on-lis-patterns)
8. [Partition DP](#-partition-dp)
9. [DP on Rectangles](#-dp-on-rectangles)
10. [Concepts & Patterns](#-concepts--patterns)
11. [Study Plan (6 Weeks)](#-study-plan-6-weeks)
12. [Progress Tracker](#-progress-tracker)
13. [Final Goal](#-final-goal)
14. [Author Note](#-author-note)

---

## 🧠 Introduction

Dynamic Programming (DP) is the **art of solving overlapping subproblems efficiently** using recursion, memoization, and tabulation.  
It’s the bridge between brute-force recursion and optimal substructure solutions.

This section covers:

- 1D, 2D, and 3D DPs
- Subsequence-based DPs
- Grid and String DPs
- Partition DPs and LIS-based DPs
- Space optimization techniques (1D → 2D → O(1))

By mastering these, you’ll move from solving **basic recurrence problems** to **top-tier interview-level optimizations**.

---

## 🪜 1D DP Problems

| #   | Problem                                  | Concept                                         | Status |
| --- | ---------------------------------------- | ----------------------------------------------- | ------ |
| 1   | **Introduction to DP**                   | Memoization, Tabulation, Space Optimization     | ☐      |
| 2   | **Climbing Stairs**                      | Classic 1D recurrence: `f(n) = f(n−1) + f(n−2)` | ☐      |
| 3   | **Frog Jump**                            | Minimize cost, build 1D DP                      | ☐      |
| 4   | **Frog Jump with K Distance**            | K-step recurrence generalization                | ☐      |
| 5   | **Maximum Sum of Non-Adjacent Elements** | DP on subsequences                              | ☐      |
| 6   | **House Robber**                         | Classic 1D DP on non-adjacent sum               | ☐      |
| 7   | **House Robber 2**                       | Circular array variant of above                 | ☐      |
| 8   | **Ninja’s Training**                     | 2D DP introduction                              | ☐      |

🧩 _Goal:_ Build comfort translating recurrences into memoized or tabulated forms.

---

## 🧭 2D & 3D DP on Grids

| #   | Problem                              | Concept                       | Status |
| --- | ------------------------------------ | ----------------------------- | ------ |
| 1   | **Grid Unique Paths**                | Count paths with moves (→, ↓) | ☐      |
| 2   | **Unique Paths II**                  | Paths with obstacles          | ☐      |
| 3   | **Minimum Path Sum**                 | Min-cost grid traversal       | ☐      |
| 4   | **Triangle**                         | Fixed start, variable end     | ☐      |
| 5   | **Minimum/Maximum Falling Path Sum** | Variable start & end          | ☐      |
| 6   | **Cherry Pickup II**                 | 3D DP (two robots on grid)    | ☐      |

🧠 _Pattern:_ Define `dp[i][j]` as the best path to `(i,j)` and build using transitions from top-left to bottom-right.

---

## 🎯 DP on Subsequences

| #   | Problem                                    | Concept                          | Status |
| --- | ------------------------------------------ | -------------------------------- | ------ |
| 1   | **Subset Sum Equals Target**               | Basic DP on subsequences         | ☐      |
| 2   | **Partition Equal Subset Sum**             | Split array into equal halves    | ☐      |
| 3   | **Partition with Minimum Difference**      | Minimize abs(sum1−sum2)          | ☐      |
| 4   | **Count Subsets with Sum K**               | Counting variant                 | ☐      |
| 5   | **Count Partitions with Given Difference** | Equation-based subset count      | ☐      |
| 6   | **0/1 Knapsack**                           | Base for all subsequence DPs     | ☐      |
| 7   | **Minimum Coins**                          | Infinite supply                  | ☐      |
| 8   | **Target Sum**                             | Positive/negative sign variation | ☐      |
| 9   | **Coin Change II**                         | Count combinations               | ☐      |
| 10  | **Unbounded Knapsack**                     | Infinite usage allowed           | ☐      |
| 11  | **Rod Cutting**                            | Convert to unbounded knapsack    | ☐      |

🧩 _Goal:_ Identify and convert recursive choices into subset transitions.

---

## 🧵 DP on Strings

| #   | Problem                                     | Concept                        | Status |
| --- | ------------------------------------------- | ------------------------------ | ------ |
| 1   | **Longest Common Subsequence (LCS)**        | Base string DP                 | ☐      |
| 2   | **Print LCS**                               | Backtrack from dp[][]          | ☐      |
| 3   | **Longest Common Substring**                | Continuous matching variant    | ☐      |
| 4   | **Longest Palindromic Subsequence**         | LCS on reversed string         | ☐      |
| 5   | **Min Insertions to Make Palindrome**       | Length − LPS                   | ☐      |
| 6   | **Min Insertions/Deletions to Convert A→B** | LCS-based diff                 | ☐      |
| 7   | **Shortest Common Supersequence**           | Combine strings using LCS      | ☐      |
| 8   | **Distinct Subsequences**                   | Count subsequences using 1D DP | ☐      |
| 9   | **Edit Distance**                           | DP on replace/insert/delete    | ☐      |
| 10  | **Wildcard Matching**                       | String pattern DP              | ☐      |

🧠 _Pattern:_ `dp[i][j]` represents a relation between prefixes `s1[0..i-1]` and `s2[0..j-1]`.

---

## 💹 DP on Stocks

| #   | Problem                                     | Concept                  | Status |
| --- | ------------------------------------------- | ------------------------ | ------ |
| 1   | **Best Time to Buy and Sell Stock I**       | Single transaction       | ☐      |
| 2   | **Buy and Sell Stock II**                   | Multiple transactions    | ☐      |
| 3   | **Buy and Sell Stock III**                  | At most two transactions | ☐      |
| 4   | **Buy and Sell Stock IV**                   | At most K transactions   | ☐      |
| 5   | **Buy and Sell Stock with Cooldown**        | Transaction cooldown     | ☐      |
| 6   | **Buy and Sell Stock with Transaction Fee** | Deduct fee in profit     | ☐      |

🧠 _Pattern:_ Maintain two states — `buy` and `sell` — at each step.

---

## 📈 DP on LIS Patterns

| #   | Problem                                  | Concept                       | Status |
| --- | ---------------------------------------- | ----------------------------- | ------ |
| 1   | **Longest Increasing Subsequence (LIS)** | Classic increasing order DP   | ☐      |
| 2   | **Print LIS**                            | Reconstruct LIS using prev[]  | ☐      |
| 3   | **LIS using Binary Search**              | O(n log n) optimization       | ☐      |
| 4   | **Largest Divisible Subset**             | LIS variant with divisibility | ☐      |
| 5   | **Longest String Chain**                 | LIS on words                  | ☐      |
| 6   | **Longest Bitonic Subsequence**          | LIS + LDS combo               | ☐      |
| 7   | **Number of LIS**                        | Count LIS length combinations | ☐      |

🧩 _Pattern:_ Variants of LIS differ only by their comparison conditions.

---

## 🧩 Partition DP

| #   | Problem                                 | Concept                             | Status |
| --- | --------------------------------------- | ----------------------------------- | ------ |
| 1   | **Matrix Chain Multiplication (MCM)**   | Partition DP foundation             | ☐      |
| 2   | **MCM Bottom-Up**                       | Tabulated version                   | ☐      |
| 3   | **Minimum Cost to Cut a Stick**         | Interval DP                         | ☐      |
| 4   | **Burst Balloons**                      | Choose partition points dynamically | ☐      |
| 5   | **Evaluate Boolean Expression to True** | Boolean partition DP                | ☐      |
| 6   | **Palindrome Partitioning II**          | Min cuts                            | ☐      |
| 7   | **Partition Array for Max Sum**         | Front partition pattern             | ☐      |

🧠 _Pattern:_ Try every partition index and combine subproblems’ answers.

---

## 🧱 DP on Rectangles

| #   | Problem                                   | Concept                         | Status |
| --- | ----------------------------------------- | ------------------------------- | ------ |
| 1   | **Maximum Rectangle Area with All 1’s**   | Histogram-based DP              | ☐      |
| 2   | **Count Square Submatrices with All 1’s** | DP[i][j] = min of neighbors + 1 | ☐      |

---

## ⚙️ Concepts & Patterns

| Concept                      | Summary                                            |
| ---------------------------- | -------------------------------------------------- |
| **Overlapping Subproblems**  | Solve smaller subcases once and reuse              |
| **Memoization → Tabulation** | Transition from top-down to bottom-up              |
| **Space Optimization**       | Use rolling arrays or single array techniques      |
| **Choice Diagram**           | Every DP problem = set of decisions per state      |
| **Transition Formula**       | Define `dp[state]` in terms of smaller subproblems |
| **Subsequence vs Subarray**  | Subsequences are non-contiguous                    |
| **State Compression**        | Reduce DP dimensions using binary encoding         |

---

## 📆 Study Plan (6 Weeks)

| Week       | Focus           | Key Topics                               |
| ---------- | --------------- | ---------------------------------------- |
| **Week 1** | Basics          | Climbing Stairs, Frog Jump, House Robber |
| **Week 2** | Grids           | Unique Paths, Triangle, Falling Path Sum |
| **Week 3** | Subsequences    | Subset Sum, Knapsack, Coin Change        |
| **Week 4** | Strings         | LCS, Edit Distance, Wildcard Matching    |
| **Week 5** | Stocks          | Buy/Sell Variants                        |
| **Week 6** | LIS & Partition | MCM, Boolean Eval, LIS, Bitonic Sequence |

🧩 _Tip:_ Always begin with recursion → memoization → tabulation → space optimization.

---

## ✅ Progress Tracker

### 1D DP

- [ ] Introduction to DP
- [ ] Climbing Stairs
- [ ] Frog Jump
- [ ] Frog Jump with K Distance
- [ ] Maximum Sum of Non-Adjacent Elements
- [ ] House Robber / House Robber 2
- [ ] Ninja’s Training

### Grids

- [ ] Unique Paths / Unique Paths II
- [ ] Minimum Path Sum
- [ ] Triangle
- [ ] Falling Path Sum
- [ ] Cherry Pickup II

### Subsequences

- [ ] Subset Sum
- [ ] Partition Equal Subset Sum
- [ ] Partition Min Difference
- [ ] Count Subsets with Sum K
- [ ] Count Partitions with Given Diff
- [ ] 0/1 Knapsack
- [ ] Minimum Coins
- [ ] Target Sum
- [ ] Coin Change II
- [ ] Unbounded Knapsack
- [ ] Rod Cutting

### Strings

- [ ] LCS
- [ ] Print LCS
- [ ] Longest Common Substring
- [ ] LPS / Min Insertions to Palindrome
- [ ] Edit Distance
- [ ] Wildcard Matching
- [ ] Distinct Subsequences
- [ ] Shortest Common Supersequence

### Stocks

- [ ] Buy/Sell I–V
- [ ] Cooldown
- [ ] Transaction Fee

### LIS / Partition

- [ ] LIS / Print LIS / Binary Search
- [ ] Largest Divisible Subset
- [ ] Longest String Chain
- [ ] Bitonic Sequence
- [ ] Number of LIS
- [ ] Matrix Chain Multiplication
- [ ] Minimum Cost to Cut Stick
- [ ] Burst Balloons
- [ ] Evaluate Boolean Expression
- [ ] Palindrome Partitioning II
- [ ] Partition Array for Max Sum

### Rectangles

- [ ] Maximum Rectangle with 1s
- [ ] Count Square Submatrices with 1s

---

## 🎯 Final Goal

By completing this roadmap, you will:

- Be fluent with **recurrence formulation**
- Identify **DP state transitions** instantly
- Solve **any DP problem** with recursion or tabulation
- Handle advanced categories (Grids, LIS, Strings, Partition DPs)
- Build an **interview-ready, modular DP library** 🚀

---

## 💬 Author Note

> This repo is designed to make DP intuitive — not memorized.  
> Focus on understanding _why_ each transition works, not just _how_.

Happy Coding 💻  
**#DSA #DynamicProgramming #Memoization #Tabulation #InterviewPrep**
