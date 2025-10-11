# Arrays

This Markdown file contains a **master reference table** for all Array problems in A2Z sheet, with difficulty, required concepts, patterns, and key points. Use this as a guide before creating individual problem files.

| S.No | Problem Name                                               | Difficulty | Concepts Required                  | Pattern / Approach                   | Notes / Key Points                          |
| ---- | ---------------------------------------------------------- | ---------- | ---------------------------------- | ------------------------------------ | ------------------------------------------- |
| 1    | Largest Element in an Array                                | Easy       | Array traversal, comparison        | Linear Scan                          | Find max by traversing array once           |
| 2    | Second Largest Element in an Array without sorting         | Medium     | Array traversal, tracking          | Two-pass or single-pass              | Keep track of largest & second largest      |
| 3    | Check if the array is sorted                               | Easy       | Array traversal, comparison        | Linear Scan                          | Compare each element with next              |
| 4    | Remove duplicates from Sorted array                        | Medium     | Array manipulation, two pointers   | In-place removal                     | Maintain unique index pointer               |
| 5    | Left Rotate an array by one place                          | Easy       | Array manipulation                 | Shift elements                       | Use temp variable for first element         |
| 6    | Left rotate an array by D places                           | Medium     | Array manipulation                 | Reversal algorithm / temporary array | Rotate using reverse or temp array          |
| 7    | Move Zeros to end                                          | Easy       | Array manipulation                 | Two pointers                         | Maintain non-zero index                     |
| 8    | Linear Search                                              | Easy       | Array traversal                    | Linear scan                          | Check each element sequentially             |
| 9    | Find the Union                                             | Medium     | Hashing, sorting, sets             | Merge / Hashing                      | Use set or hash to remove duplicates        |
| 10   | Find missing number in an array                            | Medium     | Math formula, XOR, array traversal | Sum formula / XOR                    | Use sum 1..n or XOR trick                   |
| 11   | Maximum Consecutive Ones                                   | Easy       | Array traversal                    | Sliding window                       | Count consecutive ones and track max        |
| 12   | Find the number that appears once, others twice            | Medium     | XOR, array traversal               | XOR trick                            | XOR all numbers to get unique               |
| 13   | Longest subarray with given sum K (positives)              | Medium     | Hashing, prefix sum                | Hash Map                             | Maintain prefix sum and hashmap             |
| 14   | 2Sum Problem                                               | Easy       | Hashing, array traversal           | Hashing / Two pointers               | Check sum pairs with hashset                |
| 15   | Sort an array of 0's 1's and 2's                           | Medium     | Array manipulation, pointers       | Dutch National Flag                  | Use three pointers for in-place sorting     |
| 16   | Majority Element (>n/2 times)                              | Medium     | Array traversal, counting          | Boyer-Moore Voting                   | Track candidate and verify count            |
| 17   | Kadane's Algorithm, maximum subarray sum                   | Medium     | DP / array traversal               | DP / Sliding window                  | Track current sum and max sum               |
| 18   | Print subarray with maximum subarray sum                   | Medium     | Kadane + indices                   | Extended Kadane                      | Keep track of start and end indices         |
| 19   | Stock Buy and Sell                                         | Medium     | Array traversal                    | Greedy                               | Track min price and max profit              |
| 20   | Rearrange array in alternating positive and negative items | Medium     | Two pointers, array manipulation   | Partition & merge                    | Maintain order and sign alternation         |
| 21   | Next Permutation                                           | Medium     | Array manipulation, combinatorics  | Lexicographic next                   | Find pivot, swap, reverse suffix            |
| 22   | Leaders in an Array                                        | Easy       | Array traversal                    | Reverse scan                         | Track max from right                        |
| 23   | Longest Consecutive Sequence in an Array                   | Medium     | Hashing, set                       | HashSet traversal                    | Check sequence starts with num-1 absent     |
| 24   | Set Matrix Zeros                                           | Medium     | Matrix manipulation                | Row/Column marking                   | Use first row/col or extra array            |
| 25   | Rotate Matrix by 90 degrees                                | Medium     | Matrix manipulation                | Transpose + Reverse                  | Rotate in-place for NxN matrix              |
| 26   | Print the matrix in spiral manner                          | Medium     | Matrix traversal                   | Simulation                           | Maintain four boundaries                    |
| 27   | Count subarrays with given sum                             | Medium     | Prefix sum, HashMap                | Hashing                              | Track sum frequencies                       |
| 28   | Pascal's Triangle                                          | Easy       | Array / DP                         | Build iteratively                    | Each element = sum of two above             |
| 29   | Majority Element (n/3 times)                               | Hard       | Array traversal                    | Extended Boyer-Moore                 | Track two candidates and counts             |
| 30   | 3-Sum Problem                                              | Medium     | Sorting, two pointers              | Two pointer after sorting            | Avoid duplicates, O(n^2)                    |
| 31   | 4-Sum Problem                                              | Medium     | Sorting, two pointers              | Two pointer + nested loops           | Reduce to 2-sum                             |
| 32   | Largest Subarray with 0 Sum                                | Medium     | Prefix sum, HashMap                | HashMap of sum to index              | Track first occurrence of prefix sum        |
| 33   | Count number of subarrays with given xor K                 | Medium     | XOR, HashMap                       | Prefix XOR + HashMap                 | Similar to sum problem but with XOR         |
| 34   | Merge Overlapping Subintervals                             | Medium     | Sorting, intervals                 | Sort + merge                         | Merge intervals overlapping in sorted order |
| 35   | Merge two sorted arrays without extra space                | Hard       | Array manipulation                 | Gap method / in-place merge          | Avoid extra array, optimize swaps           |
| 36   | Find the repeating and missing number                      | Medium     | Math / XOR                         | Sum & XOR                            | Calculate sum and sum squares or XOR method |
| 37   | Count Inversions                                           | Hard       | Merge sort, BIT                    | Merge sort count                     | Count inversions while merging              |
| 38   | Reverse Pairs                                              | Hard       | Merge sort                         | Modified Merge sort                  | Count pairs satisfying reverse condition    |
| 39   | Maximum Product Subarray                                   | Medium     | Array traversal, DP                | Kadane variation                     | Track max and min product so far            |

---

**Usage:**

- This file serves as a **cheatsheet** for the Arrays section.
- Use it to quickly identify **concepts, patterns, and difficulty** before implementing problem-specific Markdown and C++ solutions.
