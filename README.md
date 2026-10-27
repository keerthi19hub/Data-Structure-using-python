# Data Structures and Algorithms in Python (DSA Portfolio)

> **A comprehensive collection of 35+ implementations of core Data Structures and Algorithms in Python, featuring Stacks, Queues, Linked Lists, Binary Search, and Recursion.**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://python.org)
[![DSA](https://img.shields.io/badge/Subject-Data%20Structures%20%26%20Algorithms-orange)](https://github.com/keerthi19hub)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org)

---

## 1. Repository Overview

This repository serves as a practical, hands-on repository of **Data Structures and Algorithms (DSA)** written in Python. It documents self-contained Jupyter notebooks covering standard linear and hierarchical data structures, custom class-based implementations, recursive algorithms, and classic interview problem patterns.

Each notebook contains:
- Problem statements and theoretical motivation.
- Step-by-step algorithmic logic.
- Time and Space complexity assessments.
- Test cases validating boundary and edge conditions.

---

## 2. Topic Taxonomy & Notebook Catalog

### 📚 Stacks (LIFO) & Monotonic Stacks
| Notebook Name | Algorithmic Concepts & Focus | Time Complexity | Space Complexity |
| :--- | :--- | :---: | :---: |
| `Undo_Redo System Using Two Stacks.ipynb` | State management using application undo/redo stack pairs | $O(1)$ per op | $O(N)$ |
| `Next Greater Element .ipynb` | Monotonic stack pattern for nearest greater element lookup | $O(N)$ | $O(N)$ |
| `Finding minimum element in stack.ipynb` | $O(1)$ Min-Stack implementation with auxiliary tracking | $O(1)$ | $O(N)$ |
| `implement a stack that supports getting the middle element.ipynb` | Doubly linked list stack with middle pointer tracking | $O(1)$ | $O(N)$ |
| `stack using two queues.ipynb` | Stack simulation using FIFO queue primitives | $O(N)$ push / $O(1)$ pop | $O(N)$ |
| `Reversing a stack using stack.ipynb` | Stack reversal using secondary buffers | $O(N)$ | $O(N)$ |
| `Reversing a stack.ipynb` | In-place stack reversal using recursive call stack | $O(N^2)$ | $O(N)$ |
| `Remove Duplicates from a Stack.ipynb` | Stack deduplication preserving entry ordering | $O(N)$ | $O(N)$ |
| `check if a stack is a palindrome.ipynb` | Palindrome verification via half-stack comparison | $O(N)$ | $O(N)$ |
| `stack sort algorithm .ipynb` | Sorting elements using a temporary stack | $O(N^2)$ | $O(N)$ |
| `practice questions of stack.ipynb` | Supplementary algorithmic challenges on stack evaluation | Varies | Varies |

### 🔄 Queues (FIFO) & Double-Ended Structures
| Notebook Name | Algorithmic Concepts & Focus | Time Complexity | Space Complexity |
| :--- | :--- | :---: | :---: |
| `Queue_using_array .ipynb` | Circular array-based queue with front and rear pointers | $O(1)$ | $O(N)$ |
| `Queue_using_linkedlist.ipynb` | Dynamic memory linked list queue without fixed bounds | $O(1)$ | $O(N)$ |
| `Queue_using_list.ipynb` | Python list queue behavior and amortized complexity | $O(1)$ amortized | $O(N)$ |
| `Queue using two stacks without using not keyword (2).ipynb` | Queue via dual stacks with strict constraint programming | $O(1)$ amortized | $O(N)$ |
| `Design a Queue that Supports max() Operation.ipynb` | Monotonic deque tracking max element in $O(1)$ | $O(1)$ | $O(N)$ |
| `implement a Queue that Supports contains(x) Operation.ipynb` | Queue augmented with hash set membership testing | $O(1)$ | $O(N)$ |
| `Implement a Queue to Reverse Words in a Sentence.ipynb` | Tokenization and sentence inversion via FIFO buffers | $O(N)$ | $O(N)$ |
| `Implement a Queue with Count of Specific Element.ipynb` | Frequency-aware queue with associative counters | $O(1)$ lookup | $O(N)$ |
| `reverse a queue using a stack.ipynb` | Queue inversion using temporary LIFO stack | $O(N)$ | $O(N)$ |
| `2. Reverse a Queue Using Recursion.ipynb` | Recursive queue reversal without auxiliary data structures | $O(N)$ | $O(N)$ call stack |
| `merge2queues.ipynb` | Interleaving and merging distinct queue streams | $O(N + M)$ | $O(N + M)$ |

### 🔢 Arrays, Sorting & Searching
| Notebook Name | Algorithmic Concepts & Focus | Time Complexity | Space Complexity |
| :--- | :--- | :---: | :---: |
| `BINARY SEARCH.ipynb` | Iterative and recursive logarithmic search on sorted arrays | $O(\log N)$ | $O(1)$ |
| `Linear_searching.ipynb` | Sequential search and worst-case comparison bounds | $O(N)$ | $O(1)$ |
| `Array operations.ipynb` | Insertion, deletion, slicing, and index manipulation | $O(N)$ | $O(1)$ |
| `Creating an array.ipynb` | Array memory allocation and dynamic resizing mechanisms | $O(1)$ | $O(N)$ |
| `Descending order without built in sort.ipynb` | Selection/Bubble sort implementation without `sorted()` | $O(N^2)$ | $O(1)$ |
| `remove duplicate elements in an array.ipynb` | Two-pointer in-place deduplication on arrays | $O(N)$ | $O(1)$ |
| `removes all element less than x.ipynb` | In-place array partitioning and filtering | $O(N)$ | $O(1)$ |
| `find the sum and average of an array.ipynb` | Linear accumulation and statistical aggregations | $O(N)$ | $O(1)$ |
| `finding max and min of an array.ipynb` | Tournament and pairwise min-max discovery | $O(N)$ | $O(1)$ |
| `sorting method (1).ipynb` | Comparison of fundamental sorting paradigms | $O(N \log N)$ / $O(N^2)$ | $O(1)$ |
| `RECURSION-1.ipynb` | Recursive base cases, call trees, and call stack frames | $O(N)$ | $O(N)$ |

---

## 3. Technology Stack

- **Language:** Python 3.10+
- **Environment:** Jupyter Notebook
- **Core Libraries:** Native Python data structures (`collections.deque`, lists, classes)

---

## 4. Setup & Running

```bash
# 1. Clone repository
git clone https://github.com/keerthi19hub/Data-Structure-using-python.git
cd Data-Structure-using-python

# 2. Virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Linux/macOS

# 3. Dependencies
pip install jupyter

# 4. Launch notebook server
jupyter notebook
```

---

## 5. Author & Academic Context

- **Author:** **Keerthi N** (*Alliance University, BCA*)
- **Subject:** Data Structures & Algorithms
- **Verified Contribution:** Implemented all 35+ algorithms, queue/stack abstractions, search routines, and recursive solutions.

---

## 6. License

Released under the [MIT License](https://opensource.org/licenses/MIT).
