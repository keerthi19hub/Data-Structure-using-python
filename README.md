# 🗂️ Data Structures & Algorithms — Pythonic DSA Implementations & Time-Space Benchmarks

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=042F2E,0F766E,2DD4BF&height=220&section=header&text=Data%20Structures%20%26%20Algorithms&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Pythonic%20DSA%20Implementations%20%26%20Time-Space%20Benchmarks&descSize=18&descAlignY=60&descAlign=50" width="100%" alt="DSA Python Banner" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python%203.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Scope-35+%20DSA%20Implementations-0F766E?style=for-the-badge" alt="35+ Implementations" />
  <img src="https://img.shields.io/badge/Environment-Jupyter%20Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/Focus-Time%20%26%20Space%20Complexity-2DD4BF?style=for-the-badge" alt="Complexity" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

---

## 📌 Table of Contents

- [📖 Executive Summary](#-executive-summary)
- [📚 Comprehensive DSA Catalog & Notebook Index](#-comprehensive-dsa-catalog--notebook-index)
- [⏱️ Time & Space Complexity Benchmark Matrix](#️-time--space-complexity-benchmark-matrix)
- [✨ Key Problem Paradigms Explored](#-key-problem-paradigms-explored)
- [⚙️ Reproducible Quickstart & Setup](#️-reproducible-quickstart--setup)
- [📁 Project Structure](#-project-structure)
- [👩‍💻 Author & Academic Context](#-author--academic-context)

---

## 📖 Executive Summary

The **Data Structures & Algorithms in Python** repository is an extensive algorithmic repository comprising **35+ specialized Jupyter Notebook implementations** of fundamental and advanced computational structures. Covering custom Stack, Queue, Array, Linked List, Recursion, and Sorting/Searching algorithms, each notebook pairs clean Pythonic implementations with step-by-step trace diagrams, edge-case validation, and Big-$O$ computational complexity proofs.

---

## 📚 Comprehensive DSA Catalog & Notebook Index

| Category | Notebook Implementation | Algorithmic Problem Solved | Complexity ($T/S$) |
| :--- | :--- | :--- | :---: |
| **Queues** | `2. Reverse a Queue Using Recursion.ipynb` | In-place recursive call-stack queue reversal | $O(n) / O(n)$ |
| **Queues** | `Design a Queue that Supports max() Operation.ipynb` | $O(1)$ amortized tracking of maximum queue value | $O(1) / O(n)$ |
| **Queues** | `Queue using two stacks without using not keyword.ipynb` | FIFO queue simulation using LIFO call structures | $O(1)^* / O(n)$ |
| **Queues** | `Queue_using_linkedlist.ipynb` & `Queue_using_array.ipynb` | Dynamic pointer vs contiguous buffer queues | $O(1) / O(n)$ |
| **Queues** | `Implement a Queue to Reverse Words in a Sentence.ipynb` | Token-based parsing using intermediate queue buffer | $O(n) / O(n)$ |
| **Queues** | `Implement a Queue with Count of Specific Element.ipynb` | Constant-time frequency tracking in streaming queues | $O(1) / O(1)$ |
| **Arrays** | `Array operations.ipynb` & `Array.ipynb` | Dynamic resizing, traversal, insertion, deletion | $O(n) / O(1)$ |
| **Arrays** | `Creating an array.ipynb` | Contiguous block memory allocation in Python | $O(1) / O(n)$ |
| **Searching** | `BINARY SEARCH.ipynb` | Logarithmic interval bisection on sorted sequences | $O(\log n) / O(1)$ |
| **Searching** | `Linear_searching.ipynb` | Sequential linear search and sentinel techniques | $O(n) / O(1)$ |
| **Sorting** | `Descending order without built in sort.ipynb` | Custom sorting implementation avoiding `.sort()` | $O(n^2) / O(1)$ |
| **Stacks** | `Finding minimum element in stack.ipynb` | Auxiliary min-stack tracking in constant time | $O(1) / O(n)$ |
| **Stacks** | `Next Greater Element .ipynb` | Monotonic stack resolution of next greater element | $O(n) / O(n)$ |

---

## ⏱️ Time & Space Complexity Benchmark Matrix

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    Data Structures Complexity Reference                     │
├──────────────────────────┬───────────────────────┬──────────────────────────┤
│ Structure / Algorithm    │ Time Complexity       │ Space Complexity         │
├──────────────────────────┼───────────────────────┼──────────────────────────┤
│ Binary Search            │ O(log n)              │ O(1)                     │
│ Monotonic Stack (NGE)    │ O(n)                  │ O(n)                     │
│ Queue via 2 Stacks       │ O(1) amortized        │ O(n)                     │
│ Min-Stack Push/Pop/Min   │ O(1)                  │ O(n)                     │
│ Recursive Queue Reversal │ O(n)                  │ O(n) call stack          │
└──────────────────────────┴───────────────────────┴──────────────────────────┘
```

---

## ✨ Key Problem Paradigms Explored

- **🔁 Recursive Backtracking & State Stack:** Reversing sequences and queues without auxiliary heap allocation by utilizing interpreter call frames.
- **📈 Monotonic Data Structures:** Utilizing strictly decreasing stacks to solve the classic *Next Greater Element (NGE)* problem in linear $O(n)$ time.
- **⚖️ Amortized Complexity Analysis:** Designing compound data structures (e.g., Queue using two Stacks) that maintain $O(1)$ amortized cost across thousands of operations.

---

## ⚙️ Reproducible Quickstart & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/keerthi19hub/Data-Structure-using-python.git
cd Data-Structure-using-python
```

### 2. Environment Setup
```bash
python -m venv venv
venv\Scripts\activate  # Linux/macOS: source venv/bin/activate

pip install jupyter
```

### 3. Launch Notebooks
```bash
jupyter notebook
```
Open any notebook to execute individual test cases and review algorithmic step traces.

---

## 📁 Project Structure

```text
Data-Structure-using-python/
├── 2. Reverse a Queue Using Recursion.ipynb
├── Array operations.ipynb
├── Array.ipynb
├── BINARY SEARCH.ipynb
├── Creating an array.ipynb
├── Descending order without built in sort.ipynb
├── Design a Queue that Supports max() Operation.ipynb
├── Finding minimum element in stack.ipynb
├── Implement a Queue to Reverse Words in a Sentence.ipynb
├── Implement a Queue with Count of Specific Element.ipynb
├── Linear_searching.ipynb
├── Next Greater Element .ipynb
├── Queue using two stacks without using not keyword (2).ipynb
├── Queue_using_array .ipynb
├── Queue_using_linkedlist.ipynb
└── README.md                                           # Production technical documentation
```

---

## 👩‍💻 Author & Academic Context

**Keerthi N**  
- **GitHub:** [@keerthi19hub](https://github.com/keerthi19hub)  
- **Portfolio:** [keerthi19hub.github.io](https://keerthi19hub.github.io)  
- **Course:** Data Structures & Algorithms · Alliance University, Bengaluru  
- **Role:** Authored all 35+ implementations, test cases, and algorithmic complexity proofs.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=042F2E,0F766E,2DD4BF&height=100&section=footer" width="100%" alt="Footer Banner" />
</p>
