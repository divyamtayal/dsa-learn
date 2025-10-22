# 🔁 Two Pointers & Sliding Window Mastery

Your complete, self-contained guide to mastering **Two Pointer** and **Sliding Window** problems —  
the backbone of efficient string and array algorithms.  
This roadmap will take you from the basics to advanced patterns used in **interviews** and **competitive programming**.

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

The **Two Pointer** and **Sliding Window** techniques are powerful tools to convert brute-force `O(n²)` solutions  
into clean `O(n)` or `O(n log n)` algorithms.

They are widely used in:

- Longest / shortest substring problems
- Counting subarrays / substrings
- Sum, distinct count, or character frequency problems
- Optimizing dynamic range queries

---

## 🎯 Two Pointer Problems

| #   | Problem                                            | Concept                                                               | LeetCode                                                                                    | Status |
| --- | -------------------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------ |
| 1   | **Longest Substring Without Repeating Characters** | Maintain left pointer to ensure all characters are unique             | [LeetCode 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | ☐      |
| 2   | **Binary Subarray With Sum**                       | Count subarrays with a given sum using prefix/two pointers            | [LeetCode 930](https://leetcode.com/problems/binary-subarrays-with-sum/)                    | ☐      |
| 3   | **Maximum Points You Can Obtain From Cards**       | Convert to min-sum window problem on middle subarray                  | [LeetCode 1423](https://leetcode.com/problems/maximum-points-you-can-obtain-from-cards/)    | ☐      |
| 4   | **Subarray With K Different Integers**             | Use “at most k” trick: `exact = atMost(k) - atMost(k-1)`              | [LeetCode 992](https://leetcode.com/problems/subarrays-with-k-different-integers/)          | ☐      |
| 5   | **Minimum Window Subsequence**                     | Two-pointer forward-backward scan to find smallest subsequence window | [LeetCode 727](https://leetcode.com/problems/minimum-window-subsequence/)                   | ☐      |

🧩 _Goal:_ Gain comfort controlling two moving indices that represent valid ranges or paired relationships.

---

## 🪟 Sliding Window Problems

| #   | Problem                                                  | Concept                                                        | LeetCode                                                                                             | Status |
| --- | -------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------ |
| 1   | **Max Consecutive Ones III**                             | Longest subarray with at most `k` zeros → variable-size window | [LeetCode 1004](https://leetcode.com/problems/max-consecutive-ones-iii/)                             | ☐      |
| 2   | **Fruit Into Baskets**                                   | Longest subarray with at most 2 distinct elements              | [LeetCode 904](https://leetcode.com/problems/fruit-into-baskets/)                                    | ☐      |
| 3   | **Longest Repeating Character Replacement**              | Maintain max frequency char to allow ≤ `k` replacements        | [LeetCode 424](https://leetcode.com/problems/longest-repeating-character-replacement/)               | ☐      |
| 4   | **Count Number of Nice Subarrays**                       | Count subarrays with exactly k odd numbers                     | [LeetCode 1248](https://leetcode.com/problems/count-number-of-nice-subarrays/)                       | ☐      |
| 5   | **Number of Substrings Containing All Three Characters** | Count substrings containing ‘a’, ‘b’, and ‘c’                  | [LeetCode 1358](https://leetcode.com/problems/number-of-substrings-containing-all-three-characters/) | ☐      |
| 6   | **Longest Substring with At Most K Distinct Characters** | Expand/shrink window maintaining ≤ k distinct chars            | [LeetCode 340](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)  | ☐      |
| 7   | **Minimum Window Substring**                             | Classic min substring covering all target chars                | [LeetCode 76](https://leetcode.com/problems/minimum-window-substring/)                               | ☐      |

🧠 _Pattern:_ Adjust `left` / `right` while maintaining frequency maps or counters to keep the window valid.

---

## 🧩 Concepts to Remember

| Concept                       | Description                                                                              |
| ----------------------------- | ---------------------------------------------------------------------------------------- |
| **Two Pointers**              | Two indices (`left`, `right`) moving in a coordinated way to track valid ranges or pairs |
| **Sliding Window**            | Dynamic window [left..right] that expands/contracts based on conditions                  |
| **Fixed vs Variable Window**  | Fixed keeps constant length; Variable adjusts both sides dynamically                     |
| **At Most K / Exactly K**     | Use difference of counts: `exactlyK = atMost(K) − atMost(K−1)`                           |
| **Prefix Sum + Two Pointers** | Convert sum constraints into pointer motion                                              |
| **Character Frequency Map**   | Essential for substring counting problems                                                |

---

## 🔁 Common Patterns

| Pattern                        | Used In                                        | Key Idea                                           |
| ------------------------------ | ---------------------------------------------- | -------------------------------------------------- |
| **Expand & Shrink Window**     | Min Window Substring, Longest Unique Substring | Expand `right`, then contract `left` until invalid |
| **At Most K Trick**            | Subarray With K Distinct, Nice Subarrays       | Count ≤ K, subtract ≤ K−1                          |
| **Opposite Pointers**          | Two Sum Sorted, Reversal                       | Start & end pointer convergence                    |
| **Max Frequency Optimization** | Longest Repeating Char                         | Maintain `maxFreq` to skip re-scanning window      |
| **Complement Transform**       | Max Points From Cards                          | Reframe to “remove min sum window”                 |
| **Counting Valid Windows**     | Nice Subarrays / Substrings                    | Increment count per valid right index              |

---

## 📆 Study Plan (4 Weeks)

| Week       | Focus              | Key Topics                                                            |
| ---------- | ------------------ | --------------------------------------------------------------------- |
| **Week 1** | Fundamentals       | Longest Unique Substring, Binary Subarray Sum                         |
| **Week 2** | Basic Windows      | Max Consecutive Ones III, Fruit Into Baskets                          |
| **Week 3** | Frequency/Distinct | Repeating Char Replacement, Nice Subarrays, ABC Substrings            |
| **Week 4** | Advanced           | Minimum Window Substring, K Distinct Subarray, Min Window Subsequence |

🧩 _Tip:_ Maintain templates for fixed and variable windows. Reuse patterns — nearly all problems share structure.

---

## ✅ Progress Tracker

### Two Pointer Problems

- [ ] [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [ ] [Binary Subarray With Sum](https://leetcode.com/problems/binary-subarrays-with-sum/)
- [ ] [Maximum Points You Can Obtain From Cards](https://leetcode.com/problems/maximum-points-you-can-obtain-from-cards/)
- [ ] [Subarray With K Different Integers](https://leetcode.com/problems/subarrays-with-k-different-integers/)
- [ ] [Minimum Window Subsequence](https://leetcode.com/problems/minimum-window-subsequence/)

### Sliding Window Problems

- [ ] [Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/)
- [ ] [Fruit Into Baskets](https://leetcode.com/problems/fruit-into-baskets/)
- [ ] [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)
- [ ] [Count Number of Nice Subarrays](https://leetcode.com/problems/count-number-of-nice-subarrays/)
- [ ] [Number of Substrings Containing All Three Characters](https://leetcode.com/problems/number-of-substrings-containing-all-three-characters/)
- [ ] [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)
- [ ] [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)

---

## 🧭 How to Use This Repository

1. Folder layout:
