# Data Structures & Algorithms in Python 💻📊

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![DSA](https://img.shields.io/badge/DSA-Computer%20Science-green.svg)](https://en.wikipedia.org/wiki/Data_structure)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🎯 Repository Purpose

A clean, modular reference repository containing optimized Python implementations of foundational **Data Structures and Algorithms (DSA)**, structured with algorithmic walkthroughs and asymptotic complexity analysis.

---

## 📑 Implementations & Topics Covered

### 1. Linked Lists
- **Circular Singly Linked List** (`Circular Single linked list.ipynb`):
  - Node structure with circular tail-to-head reference.
  - Insertion (beginning, end, arbitrary position), deletion, cycle detection, and circular traversal.

### 2. Stack Data Structure
- **LIFO Stack Operations** (`DSA Stack.ipynb`):
  - Array-based stack routines with boundary verification (`push`, `pop`, `peek`, `is_empty`).
  - Expression evaluation and parenthesis balance algorithms.

### 3. Recursion & Algorithmic Patterns
- **Recursive Problem Solving** (`Recursion.ipynb`):
  - Divide-and-conquer paradigms, recursion trees, and call-stack frame analysis.

### 4. Array Manipulation & Optimization
- **Array Operations & In-Place Processing**:
  - `creating an array.ipynb`: Dynamic array allocations.
  - `array operations.ipynb`: Search, slice, partition.
  - `find the largest and smallest element in an array.ipynb`: Optimal linear scanning $O(n)$ with minimal comparisons.
  - `remove dublicate elements in an array .ipynb`: Two-pointer in-place deduplication.

---

## ⏱️ Big-O Complexity Reference

| Structure / Algorithm | Access | Search | Insertion | Deletion | Space |
|---|---|---|---|---|---|
| **Array** | $O(1)$ | $O(n)$ | $O(n)$ | $O(n)$ | $O(n)$ |
| **Circular Linked List** | $O(n)$ | $O(n)$ | $O(1)$ (head/tail) | $O(1)$ | $O(n)$ |
| **Stack (LIFO)** | $O(n)$ | $O(n)$ | $O(1)$ (push) | $O(1)$ (pop) | $O(n)$ |

---

## 📜 License
MIT License.
