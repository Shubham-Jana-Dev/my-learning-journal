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
