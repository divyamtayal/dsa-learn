# ⚡ Bit Manipulation Mastery

Your complete roadmap to mastering **Bit Manipulation** — from fundamentals to advanced tricks involving XOR, power-of-two logic, and prime sieves.  
This guide takes you from pure theory to implementation patterns used in **optimization, number theory, and system-level logic**.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Basic Bit Operations](#-basic-bit-operations)
3. [Bit Tricks & Logic Problems](#-bit-tricks--logic-problems)
4. [XOR-Based Problems](#-xor-based-problems)
5. [Prime & Number Theory Extensions](#-prime--number-theory-extensions)
6. [Power and Exponentiation](#-power-and-exponentiation)
7. [Concepts to Remember](#-concepts-to-remember)
8. [Study Plan (3 Weeks)](#-study-plan-3-weeks)
9. [Progress Tracker](#-progress-tracker)
10. [Final Goal](#-final-goal)
11. [Author Note](#-author-note)

---

## 🧠 Introduction

Bit Manipulation is one of the most powerful low-level techniques used in:

- Optimizing space and arithmetic operations
- Subset and mask generation
- Power of two / parity checks
- Fast mathematical computations
- Cryptography and number theory

Understanding bit operations helps you think **at the binary level** — essential for high-performance code and competitive programming.

---

## 💡 Basic Bit Operations

| #   | Problem                                       | Concept                                          | Status                   |
| --- | --------------------------------------------- | ------------------------------------------------ | ------------------------ | --- |
| 1   | **Introduction to Bit Manipulation (Theory)** | Learn bitwise AND, OR, XOR, NOT, shift operators | ☐                        |
| 2   | **Check if i-th Bit is Set**                  | `(n >> i) & 1`                                   | ☐                        |
| 3   | **Check if a Number is Odd or Even**          | `n & 1`                                          | ☐                        |
| 4   | **Check if a Number is Power of 2**           | `n & (n - 1)` trick                              | ☐                        |
| 5   | **Count Number of Set Bits**                  | Brian Kernighan’s Algorithm                      | ☐                        |
| 6   | **Set/Unset the Rightmost Unset Bit**         | Use `n                                           | (n + 1)` and related ops | ☐   |
| 7   | **Swap Two Numbers (Without Temp)**           | XOR swap trick                                   | ☐                        |

🧩 _Goal:_ Build intuition on how numbers behave at the bit level and get comfortable with shifts and masks.

---

## 🧮 Bit Tricks & Logic Problems

| #   | Problem                                       | Concept                                   | Status |
| --- | --------------------------------------------- | ----------------------------------------- | ------ |
| 1   | **Divide Two Integers Without `/`, `*`, `%`** | Use bit shifts to simulate division       | ☐      |
| 2   | **Count Bits to Flip to Convert A → B**       | XOR both numbers and count bits           | ☐      |
| 3   | **Find Number Appearing Odd Times**           | XOR of all numbers                        | ☐      |
| 4   | **Power Set (All Subsets)**                   | Generate subsets from bitmask of length n | ☐      |
| 5   | **Find XOR from L to R**                      | Compute XOR pattern using `xorUpto(n)`    | ☐      |
| 6   | **Find Two Numbers Appearing Odd Times**      | XOR grouping technique                    | ☐      |

🧠 _Pattern:_ XOR is your best friend — it cancels duplicates and isolates differences elegantly.

---

## 🔱 Prime & Number Theory Extensions

| #   | Problem                             | Concept                                     | Status |
| --- | ----------------------------------- | ------------------------------------------- | ------ |
| 1   | **Print Prime Factors of a Number** | Trial division up to √n                     | ☐      |
| 2   | **All Divisors of a Number**        | Iterate till √n and collect pairs           | ☐      |
| 3   | **Sieve of Eratosthenes**           | Mark multiples efficiently using bits/array | ☐      |
| 4   | **Prime Factorization using Sieve** | Precompute smallest prime factor (SPF)      | ☐      |

🧠 _Pattern:_ Combine number theory with bit concepts — the sieve uses boolean flags that parallel bit masking principles.

---

## ⚡ Power and Exponentiation

| #   | Problem         | Concept                                            | Status |
| --- | --------------- | -------------------------------------------------- | ------ |
| 1   | **Power(n, x)** | Binary exponentiation (fast power) using bit logic | ☐      |

🧩 _Goal:_ Understand how bits in the exponent drive the multiply-skip behavior in fast exponentiation.

---

## 🧠 Concepts to Remember

| Concept                         | Description                                           |
| ------------------------------- | ----------------------------------------------------- | --------------------------------------------------- |
| **Bit Masking**                 | Represent subset, toggle, or selection via bits       |
| **Shift Operations**            | `<<` doubles, `>>` halves (for positive numbers)      |
| **Set/Unset/Toggle**            | Set: `n                                               | (1<<i)`, Unset: `n & ~(1<<i)`, Toggle: `n ^ (1<<i)` |
| **Brian Kernighan’s Algorithm** | Efficiently counts set bits (`n = n & (n-1)`)         |
| **Power of Two**                | A number has only one set bit → `(n & (n-1)) == 0`    |
| **XOR Properties**              | `a^a=0`, `a^0=a`, associative & commutative           |
| **Subset Enumeration**          | Iterate `mask` from 0 → (1<<n)-1 for all combinations |
| **Fast Exponentiation**         | If exponent’s bit is 1 → multiply; always square base |

---

## 📆 Study Plan (3 Weeks)

| Week       | Focus               | Key Topics                                          |
| ---------- | ------------------- | --------------------------------------------------- |
| **Week 1** | Bit Fundamentals    | Bit operations, odd/even, power of 2, counting bits |
| **Week 2** | XOR & Mask Problems | Odd times numbers, power set, L to R XOR            |
| **Week 3** | Number Theory       | Prime factorization, sieve, binary exponentiation   |

🧩 _Tip:_ Re-implement each problem using **bitwise logic only** — avoid arithmetic where possible to train bit intuition.

---

## ✅ Progress Tracker

### Basic Bit Operations

- [ ] Introduction to Bit Manipulation (Theory)
- [ ] Check i-th Bit is Set
- [ ] Check if Number is Odd/Even
- [ ] Check if Power of 2
- [ ] Count Set Bits
- [ ] Set/Unset Rightmost Unset Bit
- [ ] Swap Two Numbers

### Bit Logic & XOR

- [ ] Divide Two Integers Without `/`, `*`, `%`
- [ ] Count Bits to Flip A → B
- [ ] Find Number Appearing Odd Times
- [ ] Power Set (All Subsets)
- [ ] Find XOR from L to R
- [ ] Find Two Numbers Appearing Odd Times

### Number Theory & Power

- [ ] Print Prime Factors
- [ ] All Divisors of a Number
- [ ] Sieve of Eratosthenes
- [ ] Prime Factorization using Sieve
- [ ] Power(n, x)

---

## 🎯 Final Goal

By mastering this section, you will:

- Be fluent in **bit-level arithmetic** and **masking tricks**
- Understand **binary exponentiation, sieves, and XOR-based problems**
- Reduce complex mathematical solutions to O(1)/O(log n) logic
- Gain a deep understanding of **binary representation & optimization**

---

## 💬 Author Note

> This repository is designed to be **self-contained** — no need to look elsewhere.  
> Implement, analyze, and re-derive each trick until you can explain it intuitively.

Happy Coding ⚡  
**#DSA #BitManipulation #XOR #Sieve #BinaryExponentiation #InterviewPrep**
