# 🧩 Stack and Queue Mastery

Your complete, self-contained guide to mastering **Stacks and Queues** — from basic implementations to advanced interview problems.  
This roadmap is designed to take you from **first principles → advanced pattern recognition** without needing any other reference.

---

## 📚 Table of Contents

1. [Introduction](#-introduction)
2. [Core Implementations](#-core-implementations)
3. [Expression Evaluation](#-expression-evaluation)
4. [Monotonic Stack Patterns](#-monotonic-stack-patterns)
5. [Range and Histogram Problems](#-range-and-histogram-problems)
6. [Sliding Window and Deque Problems](#-sliding-window-and-deque-problems)
7. [Stack Simulation Problems](#-stack-simulation-problems)
8. [Logic and Design Applications](#-logic-and-design-applications)
9. [Concepts to Remember](#-concepts-to-remember)
10. [Study Plan (7 Weeks)](#-study-plan-7-weeks)
11. [Progress Tracker](#-progress-tracker)
12. [How to Use This Repository](#-how-to-use-this-repository)
13. [Final Goal](#-final-goal)
14. [Author Note](#-author-note)

---

## 🧠 Introduction

Stacks and Queues are foundational data structures for solving:

- **Parsing** (expressions, brackets)
- **Range queries** (next greater/smaller)
- **Sliding window** and **real-time processing**
- **System design** (caches, scheduling)

Mastering them builds the intuition required for many **dynamic programming, graph, and design** problems.

---

## 🏗️ Core Implementations

| #   | Problem                               | Concept                                    | Status |
| --- | ------------------------------------- | ------------------------------------------ | ------ |
| 1   | Implement **Stack using Array**       | Understand static memory and top pointer   | ☐      |
| 2   | Implement **Queue using Array**       | Circular queue logic and overflow handling | ☐      |
| 3   | Implement **Stack using Queue(s)**    | Using two queues (push or pop costly)      | ☐      |
| 4   | Implement **Queue using Stack(s)**    | Reverse order via stack transfer           | ☐      |
| 5   | Implement **Stack using Linked List** | Dynamic memory (push = head insert)        | ☐      |
| 6   | Implement **Queue using Linked List** | Maintain `front` and `rear`                | ☐      |

🧩 _Goal:_ Build complete comfort implementing stacks and queues manually before using STL (`std::stack`, `std::queue`, `std::deque`).

---

## ⚙️ Expression Evaluation

| #   | Problem                         | Concept                                   | Status |
| --- | ------------------------------- | ----------------------------------------- | ------ |
| 1   | **Balanced Parentheses**        | Use stack to check valid open/close order | ☐      |
| 2   | **Infix → Postfix Conversion**  | Operator precedence + associativity       | ☐      |
| 3   | **Prefix → Infix Conversion**   | Reverse traversal logic                   | ☐      |
| 4   | **Prefix → Postfix Conversion** | Stack-based expression building           | ☐      |
| 5   | **Postfix → Prefix Conversion** | Reverse and evaluate with stack           | ☐      |
| 6   | **Postfix → Infix Conversion**  | Operator before operands                  | ☐      |
| 7   | **Infix → Prefix Conversion**   | Reverse, swap brackets, then postfix      | ☐      |

🧠 _Pattern:_ Stack holds **operators** and **operands** separately. Understand how evaluation order mirrors **recursion depth**.

---

## 📈 Monotonic Stack Patterns

| #   | Problem                         | Core Idea                               | Status |
| --- | ------------------------------- | --------------------------------------- | ------ |
| 1   | **Next Greater Element (NGE)**  | Pop smaller elements → decreasing stack | ☐      |
| 2   | **Next Greater Element II**     | Handle circular arrays (mod index)      | ☐      |
| 3   | **Next Smaller Element (NSE)**  | Increasing stack for smaller boundaries | ☐      |
| 4   | **Number of NGEs to the Right** | Maintain count of next greater elements | ☐      |

🧠 _Pattern:_ Maintain a **monotonic stack** (either increasing or decreasing).  
Every “pop” reveals a **relationship** — typically a **next boundary**.

---

## 🏔️ Range and Histogram Problems

| #   | Problem                            | Concept                                                   | Status |
| --- | ---------------------------------- | --------------------------------------------------------- | ------ |
| 1   | **Trapping Rainwater**             | Water trapped = min(leftMax, rightMax) − height           | ☐      |
| 2   | **Sum of Subarray Minimums**       | Each element’s contribution = product of left/right spans | ☐      |
| 3   | **Sum of Subarray Ranges**         | (Sum of max) − (sum of min) using monotonic stacks        | ☐      |
| 4   | **Largest Rectangle in Histogram** | Next smaller element to left/right defines width          | ☐      |
| 5   | **Maximal Rectangle**              | Apply histogram logic on each matrix row                  | ☐      |

🧠 _Pattern:_ For every element, find the **nearest smaller/greater** on both sides → compute **range contribution**.

---

## 🌀 Sliding Window and Deque Problems

| #   | Problem                    | Core Concept                                       | Status |
| --- | -------------------------- | -------------------------------------------------- | ------ |
| 1   | **Sliding Window Maximum** | Maintain decreasing deque of indices               | ☐      |
| 2   | **Stock Span Problem**     | Similar to NGE; span = distance between boundaries | ☐      |

🧠 _Pattern:_ Use a **deque (double-ended queue)** to maintain potential max/min elements within the current window efficiently.

---

## 💥 Stack Simulation Problems

| #   | Problem                | Concept                                      | Status |
| --- | ---------------------- | -------------------------------------------- | ------ |
| 1   | **Asteroid Collision** | Stack as a state machine (resolve conflicts) | ☐      |
| 2   | **Remove K Digits**    | Maintain increasing stack of digits          | ☐      |

🧠 _Pattern:_ "Push until condition breaks, then pop"  
Used whenever future elements invalidate earlier ones.

---

## 🧩 Logic and Design Applications

| #   | Problem                   | Concept                                | Status |
| --- | ------------------------- | -------------------------------------- | ------ |
| 1   | **The Celebrity Problem** | Eliminate candidates using stack/queue | ☐      |
| 2   | **LRU Cache (IMPORTANT)** | Combine HashMap + Doubly Linked List   | ☐      |
| 3   | **LFU Cache**             | HashMap + frequency map + ordered sets | ☐      |

🧠 _Pattern:_ Use **Stack/Queue logic for elimination** + **Linked List for recency tracking**.

---

## 🧠 Concepts to Remember

| Concept                      | Summary                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------ |
| **Monotonic Stack**          | Always sorted (increasing/decreasing) to find next greater/smaller efficiently |
| **Prefix/Suffix Boundaries** | Use NSE/NGE to calculate how much each element contributes to sums/areas       |
| **Stack + State Machine**    | For dynamic decisions like collisions, digit removals                          |
| **Deque for Windows**        | Handles sliding max/min in O(1) per step                                       |
| **Expression Evaluation**    | Stack for operators + operands based on precedence                             |
| **HashMap + DLL**            | Design backbone for LRU/LFU caches                                             |

---

## 📆 Study Plan (7 Weeks)

| Week       | Focus                 | Key Topics                          |
| ---------- | --------------------- | ----------------------------------- |
| **Week 1** | Core Implementations  | Build Stack/Queue manually          |
| **Week 2** | Expression Evaluation | Parentheses + infix/postfix/prefix  |
| **Week 3** | Monotonic Stacks      | NGE/NSE + small range problems      |
| **Week 4** | Range Problems        | Histogram, Rainwater, Subarray Sums |
| **Week 5** | Deque Problems        | Sliding Window, Stock Span          |
| **Week 6** | Simulation            | Asteroid Collision, Remove K Digits |
| **Week 7** | Design                | Celebrity, LRU, LFU Caches          |

---

## ✅ Progress Tracker

Use this checklist to monitor progress as you master each section.

### Basic Implementations

- [ ] Stack using Array
- [ ] Queue using Array
- [ ] Stack using Queue
- [ ] Queue using Stack
- [ ] Stack using Linked List
- [ ] Queue using Linked List

### Expression Evaluation

- [ ] Balanced Parentheses
- [ ] Infix to Postfix
- [ ] Prefix to Infix
- [ ] Prefix to Postfix
- [ ] Postfix to Prefix
- [ ] Postfix to Infix
- [ ] Infix to Prefix

### Monotonic Stack

- [ ] Next Greater Element
- [ ] Next Greater Element II
- [ ] Next Smaller Element
- [ ] Number of NGEs to the right

### Range Problems

- [ ] Trapping Rainwater
- [ ] Sum of Subarray Minimums
- [ ] Sum of Subarray Ranges
- [ ] Largest Rectangle in Histogram
- [ ] Maximal Rectangle

### Deque and Sliding Window

- [ ] Sliding Window Maximum
- [ ] Stock Span Problem

### Simulation

- [ ] Asteroid Collision
- [ ] Remove K Digits

### Logical / Design

- [ ] Celebrity Problem
- [ ] LRU Cache
- [ ] LFU Cache

---

## 🧭 How to Use This Repository

1. Create separate folders for each section (`/Basics`, `/Expression`, `/Monotonic`, etc.)
2. Add `.cpp` or `.py` solutions with proper problem name and explanation.
3. Update the ✅ checklist as you complete problems.
4. Use this as your **GitHub learning journal** for DSA mastery.

---

## 🧩 Final Goal

By the end of this roadmap, you will:

- Be fluent in **LIFO/FIFO data structures**
- Solve all **monotonic stack**, **window**, and **range** problems
- Be confident with **expression evaluation**
- Understand **cache design logic (LRU/LFU)** — a top interview favorite
- Recognize stack/queue patterns instantly in unseen problems 🚀

---

## 💬 Author Note

> This repo is structured to be **self-contained** — no external references needed.  
> Just follow the order, implement each problem, and mark it ✅.

Happy Coding 💻  
**#DSA #Stack #Queue #MonotonicStack #LRU #InterviewPrep**
