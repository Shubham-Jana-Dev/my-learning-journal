# 📔 Learning Journal | Feb 2, 2026

## 🕒 Session 1: 04:00 AM – 05:30 AM
**Focus:** Search Algorithm Efficiency & Mathematical Proof

### 📝 Topics Covered
* **Binary Search Logic:** The "divide and conquer" approach.
* **Math Derivation:** Proving $k = \log_2 n$ via algebraic steps.
* **Complexity Mapping:** Comparing $O(n)$ vs $O(\log n)$ growth rates.

### 📊 Visual Progress
**Growth Comparison:**
![Binary Search vs Linear Search](https://raw.githubusercontent.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/main/Day12/assets/Binary_search_graph.png)

---

## 🕒 Session 2: 06:00 AM – 07:50 AM
**Focus:** Iterative vs. Recursive Search Patterns

### 🛠️ Tasks Completed
1. **Refactored Day 09 Code:** - Moved the iterative Binary Search into a standalone function.
   - Fixed the `length` parameter bug to handle pointer decay correctly.
   - [View Code](https://github.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/blob/main/Day09/binary_shearch.c)
2. **Recursive Binary Search:** - Implemented `recursiveSearch` using a divide-and-conquer approach.
   - Applied **Pointer Arithmetic** to interface with memory addresses directly.
   - [View Code](https://github.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/blob/main/Day12/Recursive_Binary_Search.c)

### 💡 Reflection
The gap between 100 items and 1 billion items is massive, but for binary search, it's only a difference of 23 comparisons (7 vs 30). Math is powerful. Understanding how the call stack handles boundaries ($low$ and $high$) makes the recursive logic much more intuitive than nested loops.

### 🔗 Asset Links
- **Logic Diagram:** ![Binary Search Flow](https://raw.githubusercontent.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/main/Day12/assets/binary-logic.png)
- **Day 12 Technical Notes:** [View Documentation](https://github.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/tree/main/Day12)
---
---

## 🕒 Session 3: 09:00 AM – 03:45 PM
**Focus:** University Lectures

---

## 🕒 Session 4: 05:00 PM – 06:00 PM
**Focus:** Hash Maps Concept Exploration
* Watched introductory material on Hash Map theory and collision handling.

---

## 🕒 Session 5: 06:30 PM – 09:00 PM
**Focus:** Transitioning to C++ for DSA
* **Objective:** Evaluating the switch from C to C++ for the DSA journey to leverage the Standard Template Library (STL).
* **Strategy:** Decided to keep the DAA (Design and Analysis of Algorithms) journey in C for low-level memory mastery while using C++ for advanced data structures.

---

## 🕒 Session 6: 10:00 PM – 11:00 PM
**Focus:** C++ Basic Syntax & I/O Operations

### 🛠️ Tasks Completed
1. **Basic I/O:** Explored `cin`, `cout`, and `endl` for standard input and output streams.
2. **String Handling:** - Practiced standard string input.
   - Implemented `getline(cin, fullName)` to handle spaces in user input.
3. **Math Implementation:** Used the `cmath` library to calculate the area of a circle.
   - [View Basic C++ Code](https://github.com/Shubham-Jana-Dev/Learning-by-myself/blob/main/Basic.cpp)

### 💡 Reflection
Switching to C++ feels like a natural progression. The `iostream` and `string` libraries significantly simplify input/output compared to `scanf` and `printf` in C. Using `getline` was a key takeaway for handling full-name strings without losing data after a whitespace.

### 🔗 Asset Links
- **Working Area:** [Basic.cpp](https://github.com/Shubham-Jana-Dev/Learning-by-myself/blob/main/Basic.cpp)
