# 🔤 Tries & Strings Mastery

Your complete roadmap to mastering **Tries** and **String Algorithms** —  
covering everything from **prefix-based structures (Tries, XOR problems)** to **advanced string matching and manipulation** techniques like **KMP**, **Z-function**, and **Rabin-Karp**.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Trie (Prefix Tree) Problems](#-trie-prefix-tree-problems)
3. [String Fundamentals & Hashing](#-string-fundamentals--hashing)
4. [String Matching Algorithms](#-string-matching-algorithms)
5. [String Manipulation & Parsing](#-string-manipulation--parsing)
6. [Concepts to Remember](#-concepts-to-remember)
7. [Study Plan (5 Weeks)](#-study-plan-5-weeks)
8. [Progress Tracker](#-progress-tracker)
9. [Final Goal](#-final-goal)
10. [Author Note](#-author-note)

---

## 🧠 Introduction

This section focuses on two of the most powerful topics in modern problem-solving:

- **Tries (Prefix Trees)** — used for searching, prefix-matching, and XOR problems.
- **String Algorithms** — pattern matching, hashing, palindrome analysis, and parsing.

Mastering these builds the foundation for problems in **autocomplete systems**, **text editors**, **search engines**, and **pattern recognition**.

---

## 🌲 Trie (Prefix Tree) Problems

| #   | Problem                                       | Concept                                          | Status |
| --- | --------------------------------------------- | ------------------------------------------------ | ------ |
| 1   | **Implement Trie - II (Prefix Tree)**         | Insert, search, erase, prefix counting           | ☐      |
| 2   | **Longest String with All Prefixes**          | Maintain prefix chain validity                   | ☐      |
| 3   | **Number of Distinct Substrings in a String** | Use Trie to store unique substrings              | ☐      |
| 4   | **Bit Prerequisites for Trie Problems**       | Learn bit manipulation for XOR-Trie              | ☐      |
| 5   | **Maximum XOR With an Element From Array**    | Query bitwise Trie efficiently                   | ☐      |
| 6   | **Maximum XOR of Two Numbers in an Array**    | Binary Trie pairwise XOR optimization            | ☐      |
| 7   | **Word Search II**                            | Backtracking + Trie hybrid for multi-word search | ☐      |

🧠 _Pattern:_ Tries help transform string/prefix or XOR problems into **logarithmic-time lookups**, enabling fast pattern and number queries.

---

## ✳️ String Fundamentals & Hashing

| #   | Problem                                 | Concept                                        | Status |
| --- | --------------------------------------- | ---------------------------------------------- | ------ |
| 1   | **Minimum Number of Bracket Reversals** | Stack-based balancing logic                    | ☐      |
| 2   | **Count and Say**                       | Recursively build the next term of sequence    | ☐      |
| 3   | **Hashing in Strings (Theory)**         | Rolling hash and collision handling            | ☐      |
| 4   | **Rabin-Karp Algorithm**                | Substring search using polynomial rolling hash | ☐      |

🧩 _Goal:_ Learn hashing and counting-based logic before advancing to string matching.

---

## 🔍 String Matching Algorithms

| #   | Problem                            | Concept                                       | Status |
| --- | ---------------------------------- | --------------------------------------------- | ------ |
| 1   | **Z-Function**                     | Compute longest prefix-suffix matches in O(n) | ☐      |
| 2   | **KMP Algorithm / LPS (pi) Array** | Prefix function for efficient matching        | ☐      |
| 3   | **Shortest Palindrome**            | Build palindrome using reversed prefix + KMP  | ☐      |
| 4   | **Longest Happy Prefix**           | Longest prefix also acting as suffix          | ☐      |
| 5   | **Count Palindromic Subsequences** | DP + string recurrence relationships          | ☐      |

🧠 _Pattern:_ Both **Z-function** and **KMP** revolve around precomputing overlap information — essential for matching, prefix checking, and palindrome analysis.

---

## ✂️ String Manipulation & Parsing

| #   | Problem                                        | Concept                                    | Status |
| --- | ---------------------------------------------- | ------------------------------------------ | ------ |
| 1   | **Check if Two Strings are Anagram**           | Frequency count or sorting                 | ☐      |
| 2   | **Reverse Words / Palindrome Check**           | Reverse order or compare mirror positions  | ☐      |
| 3   | **Largest Odd Number in a String**             | Traverse from end for last odd digit       | ☐      |
| 4   | **Longest Common Prefix**                      | Compare characters of all strings          | ☐      |
| 5   | **Isomorphic String**                          | Maintain 1-to-1 mapping between characters | ☐      |
| 6   | **Check if One String is Rotation of Another** | Check if `s2` is substring of `s1 + s1`    | ☐      |
| 7   | **Remove Outermost Parentheses**               | Stack or counter to track nesting          | ☐      |
| 8   | **Sort Characters by Frequency**               | Use hashmap + max-heap                     | ☐      |
| 9   | **Maximum Nesting Depth of Parentheses**       | Track max open count                       | ☐      |
| 10  | **Roman Number ↔ Integer Conversion**          | Bidirectional parsing with lookup map      | ☐      |
| 11  | **Implement Atoi (String to Integer)**         | Manual parsing with overflow detection     | ☐      |
| 12  | **Count Number of Substrings**                 | Sliding window or prefix-sum based         | ☐      |
| 13  | **Longest Palindromic Substring**              | Expand around center (no DP)               | ☐      |
| 14  | **Sum of Beauty of All Substrings**            | Hashmap + frequency difference             | ☐      |
| 15  | **Reverse Every Word in a String**             | Reverse words in-place using two pointers  | ☐      |

🧠 _Pattern:_ Use **stack**, **hashmaps**, and **two-pointers** to manipulate substrings efficiently — without converting to extra data structures.

---

## ⚙️ Concepts to Remember

| Concept                   | Description                                        |
| ------------------------- | -------------------------------------------------- |
| **Trie (Prefix Tree)**    | Efficient prefix storage for strings and bits      |
| **Rolling Hash**          | Convert substrings to comparable integer values    |
| **Z / KMP Algorithms**    | Precompute longest border for string patterning    |
| **Palindrome Techniques** | Reverse, expand, or check symmetry dynamically     |
| **Frequency Mapping**     | Used for anagram and character grouping problems   |
| **Stack Parsing**         | Evaluate or clean expressions with parentheses     |
| **Two-pointer Logic**     | Simplifies reversal, substring, and counting logic |

---

## 📆 Study Plan (5 Weeks)

| Week       | Focus                       | Key Topics                                     |
| ---------- | --------------------------- | ---------------------------------------------- |
| **Week 1** | Trie Basics                 | Insert/Search/Erase, Longest Prefix, XOR Trie  |
| **Week 2** | String Fundamentals         | Bracket reversal, Count and Say, Hashing       |
| **Week 3** | String Matching             | Z-Function, KMP, Palindrome Prefix             |
| **Week 4** | String Manipulation         | Anagram, Reverse, Prefix, Parentheses          |
| **Week 5** | Parsing + Advanced Patterns | Atoi, Longest Palindrome, Beauty of Substrings |

🧩 _Tip:_ For KMP/Z problems, dry run string examples manually to visualize prefix overlaps.

---

## ✅ Progress Tracker

### Tries

- [ ] Implement Trie - II (Prefix Tree)
- [ ] Longest String with All Prefixes
- [ ] Number of Distinct Substrings
- [ ] Bit PreRequisites for Trie
- [ ] Maximum XOR With an Element From Array
- [ ] Word Search II
- [ ] Maximum XOR of Two Numbers in Array

### String Fundamentals & Hashing

- [ ] Minimum Number of Bracket Reversals
- [ ] Count and Say
- [ ] Hashing in Strings (Theory)
- [ ] Rabin-Karp Algorithm

### String Matching

- [ ] Z-Function
- [ ] KMP Algorithm / LPS(pi) Array
- [ ] Shortest Palindrome
- [ ] Longest Happy Prefix
- [ ] Count Palindromic Subsequences

### String Manipulation & Parsing

- [ ] Check if Two Strings are Anagram
- [ ] Reverse Words / Palindrome Check
- [ ] Largest Odd Number in a String
- [ ] Longest Common Prefix
- [ ] Isomorphic String
- [ ] Check if One String is Rotation of Another
- [ ] Remove Outermost Parentheses
- [ ] Sort Characters by Frequency
- [ ] Maximum Nesting Depth of Parentheses
- [ ] Roman Number ↔ Integer Conversion
- [ ] Implement Atoi
- [ ] Count Number of Substrings
- [ ] Longest Palindromic Substring
- [ ] Sum of Beauty of All Substrings
- [ ] Reverse Every Word in a String

---

## 🎯 Final Goal

By completing this roadmap, you will:

- Master **Tries** and **Prefix/XOR** problems
- Implement all major **string matching** algorithms (KMP, Z, Rabin-Karp)
- Be fluent in **string manipulation, parsing, and palindrome** logic
- Develop **pattern recognition skills** for competitive and interview problems

---

## 💬 Author Note

> Strings and Tries teach one of the most powerful lessons in DSA —  
> **how data can represent both words and numbers structurally.**  
> Once you see patterns in prefixes, repetitions, and mirrors —  
> every string problem becomes intuitive.

Happy Coding 💻  
**#DSA #Trie #Strings #KMP #ZFunction #RabinKarp #Parsing #InterviewPrep**
