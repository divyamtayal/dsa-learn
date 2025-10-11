# Arrays — Concepts and Patterns Cheat Sheet

This Markdown file summarizes **all core concepts, patterns, and tips** required to solve Array problems in A2Z sheet. It is designed for **quick revision and interview preparation**.

---

## 1. Core Array Concepts

- **Array Traversal**: Linear scan using loops.
- **Prefix Sum**: Cumulative sum to solve sum-related problems efficiently.
- **Suffix Sum**: Reverse cumulative sum for right-side calculations.
- **Hashing**: Use hash map/set to track occurrences or uniqueness.
- **Two Pointers**: Start from both ends or maintain window for pairs/subarrays.
- **Sliding Window**: Maintain a window with conditions (max/min sum, consecutive ones, etc.).
- **In-place Modification**: Modify arrays without extra space (e.g., remove duplicates, move zeros).
- **Sorting**: Quick, Merge, Counting sort to simplify searching, merge intervals, k-sum problems.
- **Kadane’s Algorithm**: Maximum subarray sum or product; track current and max sums.
- **Boyer-Moore Voting Algorithm**: Find majority element (> n/2 or n/3).
- **Math/XOR tricks**: Find missing/repeating numbers or unique elements.
- **Matrix Manipulation**: Rotate, spiral print, set row/col zeros.
- **Merge / Overlap Techniques**: Interval merging after sorting.
- **Greedy / Max-Min Tracking**: Track minimum/maximum dynamically for profit, leaders, etc.

---

## 2. Array Problem Patterns

| Pattern               | Example Problems                                           | Key Idea                                           | Notes                                          |
| --------------------- | ---------------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------- |
| Linear Scan           | Largest Element, Check Sorted, Max Consecutive Ones        | Traverse array sequentially                        | O(n) time, simplest approach                   |
| Two Pointers          | 2Sum, 3Sum, 4Sum, Move Zeros, Dutch National Flag          | Maintain two pointers to scan/partition            | Often requires sorted array for sum problems   |
| Sliding Window        | Max Consecutive Ones, Longest Subarray Sum K               | Maintain window satisfying condition               | Expand/shrink window, track result dynamically |
| Prefix/Suffix Sum     | Count subarrays with sum K, Largest Subarray with 0 sum    | Precompute cumulative sums                         | Use hashmap to track first occurrences         |
| Hashing               | Find Union, Missing Number, Subarray XOR K                 | Store elements/frequencies in set/map              | Quick lookups, O(n) time typically             |
| In-place Modification | Remove Duplicates, Move Zeros, Rearrange Positive/Negative | Use pointers to overwrite elements                 | Optimize space usage                           |
| Greedy / Max-Min      | Stock Buy & Sell, Leaders in Array                         | Track current min/max                              | One-pass solution often works                  |
| Sorting + Merge       | Merge Overlapping Intervals, 3Sum, 4Sum                    | Sort first, then apply two pointers or merge logic | O(n log n) for sort, careful with duplicates   |
| Kadane’s Algorithm    | Max Subarray Sum, Max Product Subarray                     | Track current sum/product and max                  | Consider negative numbers for product version  |
| Boyer-Moore Voting    | Majority Element > n/2 or n/3                              | Track candidate(s) and counts                      | Verify candidate occurrence at the end         |
| Math / XOR            | Single number, Missing & Repeating                         | Use sum formula or XOR property                    | XOR: a^a=0, a^0=a, associative                 |
| Matrix Manipulation   | Rotate Matrix 90, Spiral Print, Set Matrix Zeros           | Transpose + reverse or boundary traversal          | Use extra array or in-place approach           |
| Merge Sort Based      | Count Inversions, Reverse Pairs                            | Divide & Conquer + merge step                      | Count while merging for efficiency             |

---

## 3. Quick Tips

- **Duplicates**: Handle carefully with sorting, sets, or two pointers.
- **Subarray / Subsequence**: Contiguous vs non-contiguous distinction.
- **Edge Cases**: Empty arrays, single-element arrays, all equal elements, negative numbers.
- **Space Optimization**: Many array problems can be solved in-place.
- **Time Complexity Awareness**: Optimize O(n^2) to O(n) using hashing, prefix sums, sliding window, or two pointers.
- **Matrix Boundaries**: Always check row/col boundaries when rotating or printing spirals.
- **Negative Numbers in Kadane / Max Product**: Track both max and min products for subarrays.

---

This **concepts & patterns cheat sheet** should be saved as `01_arrays/concepts_patterns.md` in your repo for **ultimate reference and revision**.
