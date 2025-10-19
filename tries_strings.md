# 🌳 Trees, Tries & String Mastery

Your complete roadmap to mastering **Trees**, **Tries**, and **String Algorithms** —  
from basic concepts like tree structure and recursion to advanced string processing with **KMP**, **Z-function**, and **Trie-based prefix/XOR** problems.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Tree Fundamentals](#-tree-fundamentals)
3. [Trie (Prefix Tree) Problems](#-trie-prefix-tree-problems)
4. [String Fundamentals & Hashing](#-string-fundamentals--hashing)
5. [String Matching Algorithms](#-string-matching-algorithms)
6. [String Manipulation & Parsing](#-string-manipulation--parsing)
7. [Concepts to Remember](#-concepts-to-remember)
8. [Study Plan (5 Weeks)](#-study-plan-5-weeks)
9. [Progress Tracker](#-progress-tracker)
10. [Final Goal](#-final-goal)
11. [Author Note](#-author-note)

---

## 🧠 Introduction

This section unifies three critical ideas:

- **Trees and Tries** — hierarchical data structures for searching and prefix operations.
- **String Algorithms** — efficient text searching, hashing, and pattern recognition.
- **Parsing and Expression Problems** — applying stack, recursion, and math logic on strings.

Together, these concepts help you solve problems in **search engines, compilers, text editors, and autocompletion systems.**

---

## 🌴 Tree Fundamentals

| #   | Problem                   | Concept                                       | Status |
| --- | ------------------------- | --------------------------------------------- | ------ |
| 1   | **Introduction to Trees** | Understanding types: Binary, BST, N-ary, Trie | ☐      |

🧩 _Goal:_ Understand tree structure, recursion, and node-based traversal before moving to Tries.

---

## 🌲 Trie (Prefix Tree) Problems

| #   | Problem                                 | Concept                                   | Status |
| --- | --------------------------------------- | ----------------------------------------- | ------ |
| 1   | **Implement Trie (Prefix Tree)**        | Insert, Search, StartsWith                | ☐      |
| 2   | **Implement Trie – II**                 | Insert multiple strings, frequency, erase | ☐      |
| 3   | **Longest String with All Prefixes**    | Build Trie and check prefix validity      | ☐      |
| 4   | **Number of Distinct Substrings**       | Trie-based substring counting             | ☐      |
| 5   | **Bit Prerequisites for Trie Problems** | Bit manipulation needed for XOR tries     | ☐      |
| 6   | **Maximum XOR with Element from Array** | Trie with bitwise paths                   | ☐      |
| 7   | **Maximum XOR of Two Numbers in Array** | Binary Trie for pairwise max XOR          | ☐      |
| 8   | **Word Search II**                      | Backtracking + Trie hybrid                | ☐      |

🧠 _Pattern:_ Tries convert prefix and XOR problems into efficient **O(L)** lookups and enable **fast dictionary searching.**

---

## ✳️ String Fundamentals & Hashing

| #   | Problem                                 | Concept                                | Status |
| --- | --------------------------------------- | -------------------------------------- | ------ |
| 1   | **Minimum Number of Bracket Reversals** | Stack-based balance correction         | ☐      |
| 2   | **Count and Say**                       | Recursive string generation            | ☐      |
| 3   | **Hashing in Strings (Theory)**         | Rolling hash, polynomial hash concepts | ☐      |
| 4   | **Rabin-Karp Algorithm**                | Substring search using rolling hash    | ☐      |

🧩 _Goal:_ Build intuition for substring comparison, rolling hash design, and modular arithmetic in string hashing.

---

## 🔍 String Matching Algorithms

| #   | Problem                            | Concept                                     | Status |
| --- | ---------------------------------- | ------------------------------------------- | ------ |
| 1   | **Z-Function**                     | Prefix-suffix matching precomputation       | ☐      |
| 2   | **KMP Algorithm / LPS Array**      | Prefix pattern matching (LPS preprocessing) | ☐      |
| 3   | **Shortest Palindrome**            | KMP-based reverse prefix solution           | ☐      |
| 4   | **Longest Happy Prefix**           | KMP prefix border                           | ☐      |
| 5   | **Count Palindromic Subsequences** | DP + string recurrence                      | ☐      |

🧠 _Pattern:_ Use precomputed **prefix-suffix arrays (Z/KMP)** to search or analyze repeating string patterns in linear time.

---

## ✂️ String Manipulation & Parsing

| #   | Problem                                        | Concept                                | Status |
| --- | ---------------------------------------------- | -------------------------------------- | ------ |
| 1   | **Check if Two Strings are Anagrams**          | Frequency counting (hashmap / array)   | ☐      |
| 2   | **Reverse Words / Palindrome Check**           | Tokenize & compare reversed string     | ☐      |
| 3   | **Largest Odd Number in a String**             | Scan from end for last odd digit       | ☐      |
| 4   | **Longest Common Prefix**                      | Compare character by character         | ☐      |
| 5   | **Isomorphic Strings**                         | Maintain mapping pattern between chars | ☐      |
| 6   | **Check if One String is Rotation of Another** | `s1 + s1` contains `s2`                | ☐      |
| 7   | **Remove Outermost Parentheses**               | Stack count logic                      | ☐      |
| 8   | **Sort Characters by Frequency**               | Frequency sort via heap/hashmap        | ☐      |
| 9   | **Maximum Nesting Depth of Parentheses**       | Count open/close depth                 | ☐      |
| 10  | **Roman Number ↔ Integer Conversion**          | Parsing from both directions           | ☐      |
| 11  | **Implement Atoi (String to Integer)**         | Manual parsing and overflow check      | ☐      |
| 12  | **Count Number of Substrings**                 | Sliding window or prefix sum           | ☐      |
| 13  | **Longest Palindromic Substring**              | Expand-around-center (No DP)           | ☐      |
| 14  | **Sum of Beauty of All Substrings**            | Hash + frequency difference            | ☐      |
| 15  | **Reverse Every Word in a String**             | Manual two-pointer reversal            | ☐      |

🧠 _Pattern:_ Focus on **two-pointer**, **stack**, and **frequency-mapping** logic for clean string manipulation.

---

## ⚙️ Concepts to Remember

| Concept                   | Description                                      |
| ------------------------- | ------------------------------------------------ |
| **Trie Structure**        | Tree for efficient prefix storage                |
| **Prefix Matching**       | Used in autocompletion and dictionary problems   |
| **Rolling Hash**          | Converts strings into comparable integers        |
| **Z & KMP Algorithms**    | Pattern matching in O(n)                         |
| **Palindrome Tricks**     | Reverse + prefix/suffix comparison               |
| **Stack for Parentheses** | Count or validate balanced expressions           |
| **Character Mapping**     | Used in anagrams, isomorphism, encoding problems |
| **Parsing Techniques**    | Manual token reading and integer conversion      |

---

## 📆 Study Plan (5 Weeks)

| Week       | Focus                          | Key Topics                                             |
| ---------- | ------------------------------ | ------------------------------------------------------ |
| **Week 1** | Trees & Tries                  | Introduction to Trie, Prefix, and XOR problems         |
| **Week 2** | String Basics                  | Bracket, Count & Say, Hashing, Rabin-Karp              |
| **Week 3** | String Matching                | Z-function, KMP, Prefix/Border patterns                |
| **Week 4** | String Manipulation            | Anagram, Palindrome, Prefix problems                   |
| **Week 5** | Parsing & Palindrome Expansion | Atoi, Longest Palindromic Substring, Roman conversions |

🧩 _Tip:_ Practice dry runs — visualize Trie insertion and prefix walking; trace KMP’s LPS array manually for deep understanding.

---

## ✅ Progress Tracker

### Tree / Trie

- [ ] Introduction to Trees
- [ ] Implement Trie I / II
- [ ] Longest String with All Prefixes
- [ ] Number of Distinct Substrings
- [ ] Bit Pre-Requisites for Trie
- [ ] Maximum XOR (Array + Element)
- [ ] Word Search II

### String Fundamentals & Hashing

- [ ] Bracket Reversals
- [ ] Count and Say
- [ ] Hashing Theory
- [ ] Rabin-Karp

### String Matching

- [ ] Z-Function
- [ ] KMP / LPS Array
- [ ] Shortest Palindrome
- [ ] Longest Happy Prefix
- [ ] Count Palindromic Subsequences

### String Manipulation & Parsing

- [ ] Anagram Check
- [ ] Reverse Words / Palindrome Check
- [ ] Largest Odd Number
- [ ] Longest Common Prefix
- [ ] Isomorphic String
- [ ] Rotation Check
- [ ] Remove Outermost Parentheses
- [ ] Sort Characters by Frequency
- [ ] Maximum Nesting Depth
- [ ] Roman ↔ Integer Conversion
- [ ] Implement Atoi
- [ ] Count Substrings
- [ ] Longest Palindromic Substring
- [ ] Sum of Beauty of Substrings
- [ ] Reverse Every Word

---

## 🎯 Final Goal

By completing this roadmap, you will:

- Master **Trie operations, prefix queries, and XOR optimizations**
- Understand **rolling hash, KMP, and Z-function algorithms**
- Gain proficiency in **parsing, palindrome, and string transformations**
- Be interview-ready for **Google, Meta, Amazon, and Codeforces-style string problems**

---

## 💬 Author Note

> Trees, Tries, and String Algorithms teach how data flows through **characters, bits, and structures** — forming the foundation of advanced algorithms like **suffix arrays, automata, and pattern matching**.  
> Think in terms of _patterns, repetition, and hierarchy_ — not just characters.

Happy Coding 💻  
**#DSA #Trie #Strings #Hashing #KMP #RabinKarp #Parsing #InterviewPrep**
