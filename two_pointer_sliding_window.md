# 🔁 Two Pointers & Sliding Window Mastery

Your complete, self-contained guide to mastering **Two Pointer** and **Sliding Window** problems — the backbone of efficient string and array algorithms.  
This roadmap will take you from the basics to advanced patterns used in interviews and contests.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Two Pointer Problems](#-two-pointer-problems)
3. [Sliding Window Problems](#-sliding-window-problems)
4. [Concepts to Remember](#-concepts-to-remember)
5. [Common Patterns](#-common-patterns)
6. [Study Plan (4 Weeks)](#-study-plan-4-weeks)
7. [Progress Tracker](#-progress-tracker)
8. [How to Use This Repository](#-how-to-use-this-repository)
9. [Final Goal](#-final-goal)
10. [Author Note](#-author-note)

---

## 🧠 Introduction

The **Two Pointer** and **Sliding Window** techniques are some of the most powerful tools in algorithm design.  
They reduce brute-force `O(n²)` approaches to elegant `O(n)` or `O(n log n)` solutions by managing dynamic ranges or pointer interactions.

These techniques are used to solve:

- Longest/shortest substring problems
- Counting subarrays/substrings with given properties
- Array pair problems (sum, distinct count)
- Character frequency and window optimizations

Mastering them gives you a massive edge in both **interviews** and **competitive programming**.

---

## 🎯 Two Pointer Problems

| #   | Problem                                            | Concept                                                               | Status |
| --- | -------------------------------------------------- | --------------------------------------------------------------------- | ------ |
| 1   | **Longest Substring Without Repeating Characters** | Maintain left pointer to ensure all characters are unique             | ☐      |
| 2   | **Binary Subarray With Sum**                       | Count subarrays with a given sum using prefix/two pointers            | ☐      |
| 3   | **Maximum Points You Can Obtain From Cards**       | Convert to min-sum window problem on middle subarray                  | ☐      |
| 4   | **Subarray With K Different Integers**             | Use “at most k” two-pointer logic, exact = atMost(k) - atMost(k-1)    | ☐      |
| 5   | **Minimum Window Subsequence**                     | Two-pointer forward-backward pass to find smallest subsequence window | ☐      |

🧩 _Goal:_ Build fluency in controlling two moving indices that represent valid ranges or paired relationships.

---

## 🪟 Sliding Window Problems

| #   | Problem                                                  | Concept                                                      | Status |
| --- | -------------------------------------------------------- | ------------------------------------------------------------ | ------ |
| 1   | **Max Consecutive Ones III**                             | Longest subarray with at most k zeros → variable-size window | ☐      |
| 2   | **Fruit Into Baskets**                                   | Longest subarray with at most 2 distinct elements            | ☐      |
| 3   | **Longest Repeating Character Replacement**              | Maintain max frequency char to allow ≤k replacements         | ☐      |
| 4   | **Count Number of Nice Subarrays**                       | Count subarrays with exactly k odd numbers                   | ☐      |
| 5   | **Number of Substrings Containing All Three Characters** | Count all substrings containing ‘a’, ‘b’, and ‘c’            | ☐      |
| 6   | **Longest Substring with At Most K Distinct Characters** | Expand/shrink window maintaining ≤k distinct chars           | ☐      |
| 7   | **Minimum Window Substring**                             | Classic min substring covering target characters             | ☐      |

🧠 _Pattern:_ Adjust `left` and `right` pointers while maintaining frequency maps or counts to keep the window valid.

---

## 🧩 Concepts to Remember

| Concept                       | Description                                                                                                                    |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Two Pointers**              | Two indices (usually `left` & `right`) moving in a controlled way — same or opposite direction — to find valid pairs or ranges |
| **Sliding Window**            | Dynamic window [left..right] that expands/contracts based on problem constraints                                               |
| **Variable vs Fixed Window**  | Variable adjusts both sides dynamically; Fixed keeps size constant                                                             |
| **At Most K / Exactly K**     | Use difference of counts: `exactlyK = atMost(K) - atMost(K-1)`                                                                 |
| **Prefix Sum + Two Pointers** | Converts sum constraints into pointer movement                                                                                 |
| **Character Frequency Map**   | Key to substring problems — track counts of each element in window                                                             |

---

## 🔁 Common Patterns

| Pattern                        | Used In                                        | Idea                                                         |
| ------------------------------ | ---------------------------------------------- | ------------------------------------------------------------ |
| **Expand & Shrink Window**     | Min Window Substring, Longest Unique Substring | Expand `right`, then contract `left` until condition invalid |
| **At Most K Trick**            | Subarray With K Distinct, Nice Subarrays       | Count windows with ≤k, subtract ≤(k−1)                       |
| **Opposite Pointers**          | Pair Sum, Reverse Operations                   | One pointer from start, one from end                         |
| **Max Frequency Optimization** | Longest Repeating Char Replacement             | Keep track of `maxFreq` to avoid unnecessary recalculation   |
| **Transform Complement**       | Max Points from Cards                          | Convert to “remove smallest subarray” problem                |
| **Counting Valid Windows**     | Count Nice Subarrays                           | Increment count while window valid; use cumulative counts    |

---

## 🧭 Study Plan (4 Weeks)

| Week       | Focus                   | Key Topics                                                                                    |
| ---------- | ----------------------- | --------------------------------------------------------------------------------------------- |
| **Week 1** | Fundamentals            | Longest unique substring, binary subarray sum                                                 |
| **Week 2** | Basic Window Expansions | Max consecutive ones III, fruit into baskets                                                  |
| **Week 3** | Frequency + Distinct    | Longest repeating char replacement, nice subarrays, number of substrings with all three chars |
| **Week 4** | Advanced Windows        | Minimum window substring, subarray with k distinct, minimum window subsequence                |

🧩 _Tip:_ Write your own templates for fixed-size and variable-size window problems to reuse in multiple questions.

---

## ✅ Progress Tracker

### Two Pointer Problems

- [ ] Longest Substring Without Repeating Characters
- [ ] Binary Subarray With Sum
- [ ] Maximum Points You Can Obtain From Cards
- [ ] Subarray With K Different Integers
- [ ] Minimum Window Subsequence

### Sliding Window Problems

- [ ] Max Consecutive Ones III
- [ ] Fruit Into Baskets
- [ ] Longest Repeating Character Replacement
- [ ] Count Number of Nice Subarrays
- [ ] Number of Substrings Containing All Three Characters
- [ ] Longest Substring with At Most K Distinct Characters
- [ ] Minimum Window Substring

---

## 🧭 How to Use This Repository

1. Create separate folders for each category (`/TwoPointers`, `/SlidingWindow`).
2. Add each solution as a `.cpp` or `.py` file named clearly (e.g., `longest_unique_substring.cpp`).
3. Write a short explanation in comments before the code (approach, complexity, key idea).
4. Update the checklist above as you complete problems.
5. Use this repo as your **personal reference** for interview prep and review.

---

## 🎯 Final Goal

By completing this roadmap, you will:

- Recognize and apply **two-pointer** and **sliding window** patterns instantly
- Convert brute-force substring/subarray problems to `O(n)` solutions
- Master **“expand–shrink” logic**, **distinct count**, and **frequency map** tricks
- Be ready for **top-tier interviews** and **competitive programming contests**

---

## 💬 Author Note

> This repository is structured to be **self-contained** — no external references needed.  
> Follow the plan, understand the patterns, and mark your progress.

Happy Coding 💻  
**#DSA #TwoPointers #SlidingWindow #InterviewPrep**
