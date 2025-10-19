# 🔢 Arrays Mastery

Your complete, self-contained roadmap to mastering **Array Data Structure problems** — from beginner implementations to advanced algorithms like Kadane’s, Next Permutation, and Subarray XOR.  
This guide is designed to cover all **array patterns** required for interviews and contests.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Basic Array Operations](#-basic-array-operations)
3. [Searching & Duplicates](#-searching--duplicates)
4. [Rotations & Rearrangements](#-rotations--rearrangements)
5. [Mathematical & Subarray Problems](#-mathematical--subarray-problems)
6. [Advanced Subarray & Hash Problems](#-advanced-subarray--hash-problems)
7. [Matrix Problems](#-matrix-problems)
8. [Patterns & Algorithms](#-patterns--algorithms)
9. [Study Plan (5 Weeks)](#-study-plan-5-weeks)
10. [Progress Tracker](#-progress-tracker)
11. [Final Goal](#-final-goal)
12. [Author Note](#-author-note)

---

## 🧠 Introduction

Arrays form the backbone of most data structure and algorithm problems.  
They are used to build a deep understanding of **memory, iteration, sorting, searching, and pattern recognition**.

This section covers:

- Core array manipulation
- Subarray and prefix-based problems
- Mathematical optimizations
- Matrix transformations
- Advanced algorithms (Kadane’s, Dutch National Flag, XOR, Merge intervals, etc.)

By the end, you’ll recognize **patterns instantly** and reduce complex brute-force logic to clean linear-time solutions.

---

## 🧩 Basic Array Operations

| #   | Problem                                      | Concept                                   | Status |
| --- | -------------------------------------------- | ----------------------------------------- | ------ |
| 1   | **Largest Element in an Array**              | Simple traversal and comparison           | ☐      |
| 2   | **Second Largest Element (Without Sorting)** | Track first and second max                | ☐      |
| 3   | **Check if Array is Sorted**                 | Single pass check (increasing/decreasing) | ☐      |
| 4   | **Remove Duplicates from Sorted Array**      | Two pointer overwrite logic               | ☐      |
| 5   | **Left Rotate Array by One Place**           | Temp + shift                              | ☐      |
| 6   | **Left Rotate Array by D Places**            | Reverse segments or use temp array        | ☐      |
| 7   | **Move Zeros to End**                        | Stable move with two pointers             | ☐      |
| 8   | **Linear Search**                            | Simple scan                               | ☐      |
| 9   | **Find the Union of Two Arrays**             | Hashset or two-pointer merge              | ☐      |
| 10  | **Find Missing Number**                      | Use sum or XOR                            | ☐      |
| 11  | **Maximum Consecutive Ones**                 | Count consecutive 1s in binary array      | ☐      |
| 12  | **Number Appears Once (Others Twice)**       | XOR all elements                          | ☐      |

---

## 🔍 Searching & Duplicates

| #   | Problem                                                   | Concept                                 | Status |
| --- | --------------------------------------------------------- | --------------------------------------- | ------ |
| 1   | **Longest Subarray with Given Sum K (Positive Integers)** | Two pointers or prefix sum              | ☐      |
| 2   | **2-Sum Problem**                                         | Hashmap for complement or two-pointer   | ☐      |
| 3   | **Sort 0’s, 1’s, and 2’s**                                | Dutch National Flag algorithm           | ☐      |
| 4   | **Majority Element (> n/2)**                              | Boyer–Moore Voting Algorithm            | ☐      |
| 5   | **Kadane’s Algorithm (Max Subarray Sum)**                 | Prefix sum / running max logic          | ☐      |
| 6   | **Print Subarray with Maximum Sum**                       | Extension of Kadane’s storing indices   | ☐      |
| 7   | **Stock Buy and Sell**                                    | Max profit via single pass tracking min | ☐      |

---

## 🔁 Rotations & Rearrangements

| #   | Problem                                       | Concept                            | Status |
| --- | --------------------------------------------- | ---------------------------------- | ------ |
| 1   | **Rearrange Positive & Negative Alternately** | Partition by sign and interleave   | ☐      |
| 2   | **Next Permutation**                          | Find next lexicographical order    | ☐      |
| 3   | **Leaders in Array**                          | Elements greater than all to right | ☐      |
| 4   | **Longest Consecutive Sequence**              | Hashset and boundary detection     | ☐      |

---

## 🧮 Mathematical & Subarray Problems

| #   | Problem                            | Concept                                  | Status |
| --- | ---------------------------------- | ---------------------------------------- | ------ |
| 1   | **Set Matrix Zeros**               | Mark first row/col + O(1) space approach | ☐      |
| 2   | **Rotate Matrix by 90°**           | Transpose + reverse rows                 | ☐      |
| 3   | **Print Matrix in Spiral Order**   | Boundary traversal                       | ☐      |
| 4   | **Count Subarrays with Given Sum** | Prefix sum hashmap                       | ☐      |
| 5   | **Pascal’s Triangle**              | Combinatorial pattern / nCr generation   | ☐      |

---

## ⚙️ Advanced Subarray & Hash Problems

| #   | Problem                                         | Concept                        | Status |
| --- | ----------------------------------------------- | ------------------------------ | ------ |
| 1   | **Majority Element (> n/3)**                    | Extended Boyer–Moore           | ☐      |
| 2   | **3-Sum Problem**                               | Sorting + two-pointer          | ☐      |
| 3   | **4-Sum Problem**                               | Nested loops + two-pointer     | ☐      |
| 4   | **Largest Subarray with 0 Sum**                 | Prefix sum + hashmap           | ☐      |
| 5   | **Count Subarrays with Given XOR K**            | XOR prefix + hashmap           | ☐      |
| 6   | **Merge Overlapping Intervals**                 | Sort + merge adjacent overlaps | ☐      |
| 7   | **Merge Two Sorted Arrays Without Extra Space** | Gap method / shell sort style  | ☐      |
| 8   | **Find Repeating and Missing Number**           | XOR / sum difference trick     | ☐      |
| 9   | **Count Inversions**                            | Modified merge sort            | ☐      |
| 10  | **Reverse Pairs**                               | Merge sort + counting          | ☐      |
| 11  | **Maximum Product Subarray**                    | Track max/min products         | ☐      |

---

## 🧠 Patterns & Algorithms

| Pattern                           | Description                                                   |
| --------------------------------- | ------------------------------------------------------------- |
| **Prefix Sum / XOR**              | Compute cumulative value and use hashmap for subarray queries |
| **Two Pointer / Sliding Window**  | Optimize O(n²) loops for sum or distinct count problems       |
| **Kadane’s Algorithm**            | Efficient max subarray finder using prefix diff idea          |
| **Dutch National Flag Algorithm** | In-place sort for 0s, 1s, and 2s (partitioning logic)         |
| **Boyer–Moore Voting**            | Find majority elements in O(n) and O(1) space                 |
| **Merge Sort Modifications**      | Used for inversion count and reverse pairs                    |
| **Matrix Transformations**        | Transpose, rotate, spiral traversal, zero-marking             |
| **Set Hash + Boundaries**         | For longest consecutive sequence or unique range building     |

---

## 📆 Study Plan (5 Weeks)

| Week       | Focus                | Key Topics                                        |
| ---------- | -------------------- | ------------------------------------------------- |
| **Week 1** | Basics               | Traversals, rotation, duplicates, missing numbers |
| **Week 2** | Subarray Logic       | Kadane’s, stock buy/sell, sum/xor patterns        |
| **Week 3** | Advanced Hash + Math | Count inversions, 0 sum, XOR, n/3 majority        |
| **Week 4** | Matrix Operations    | Rotate, spiral, set zeros                         |
| **Week 5** | Mixed Practice       | Merge intervals, 3-sum, next permutation          |

🧩 _Tip:_ Implement 3–5 problems daily, focusing on code clarity and pattern understanding instead of memorization.

---

## ✅ Progress Tracker

### Basic Operations

- [ ] Largest Element in Array
- [ ] Second Largest Element (Without Sorting)
- [ ] Check if Array is Sorted
- [ ] Remove Duplicates from Sorted Array
- [ ] Left Rotate Array by One
- [ ] Left Rotate Array by D Places
- [ ] Move Zeros to End
- [ ] Linear Search
- [ ] Find Union of Arrays
- [ ] Find Missing Number
- [ ] Maximum Consecutive Ones
- [ ] Number Appears Once (Others Twice)

### Searching & Subarray

- [ ] Longest Subarray with Given Sum K
- [ ] 2-Sum Problem
- [ ] Sort 0s, 1s, and 2s
- [ ] Majority Element (> n/2)
- [ ] Kadane’s Algorithm
- [ ] Print Subarray with Maximum Sum
- [ ] Stock Buy and Sell

### Rearrangement & Sequence

- [ ] Rearrange Positive/Negative Alternately
- [ ] Next Permutation
- [ ] Leaders in Array
- [ ] Longest Consecutive Sequence

### Matrix

- [ ] Set Matrix Zeros
- [ ] Rotate Matrix by 90°
- [ ] Print Matrix in Spiral Order
- [ ] Pascal’s Triangle

### Advanced Hash & Math

- [ ] Majority Element (> n/3)
- [ ] 3-Sum Problem
- [ ] 4-Sum Problem
- [ ] Largest Subarray with 0 Sum
- [ ] Count Subarrays with Given XOR K
- [ ] Merge Overlapping Intervals
- [ ] Merge Two Sorted Arrays (No Extra Space)
- [ ] Find Repeating and Missing Number
- [ ] Count Inversions
- [ ] Reverse Pairs
- [ ] Maximum Product Subarray

---

## 🎯 Final Goal

By mastering this list, you’ll:

- Handle any **array or subarray** interview problem confidently
- Recognize patterns instantly (prefix, XOR, Kadane’s, two pointer)
- Transition seamlessly into **DP, matrix, and graph** concepts
- Have a clean, complete **GitHub portfolio section** for arrays 🚀

---

## 💬 Author Note

> This repository is designed to be **self-contained** — you won’t need any other source.  
> Implement, test, and analyze each problem to understand **why** it works.

Happy Coding 💻  
**#DSA #Arrays #Subarrays #Kadane #PrefixSum #InterviewPrep**
