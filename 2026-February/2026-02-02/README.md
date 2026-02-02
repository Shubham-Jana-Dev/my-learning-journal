# 📔 Learning Journal | Feb 2, 2026
**Time Block:** 04:00 AM – 05:30 AM

## 🎯 Focus: Search Algorithm Efficiency
Today's session was dedicated to the mathematical proof of $O(\log n)$ and visualizing how binary search outperforms linear search as datasets grow.

### 📝 Topics Covered
* **Binary Search Logic:** The "divide and conquer" approach.
* **Math Derivation:** Proving $k = \log_2 n$ via algebraic steps.
* **Complexity Mapping:** Comparing $O(n)$ vs $O(\log n)$ growth rates.

### 📊 Visual Progress
**Growth Comparison:**
![Binary Search vs Linear Search](https://raw.githubusercontent.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/main/Day12/assets/Binary_search_graph.png)

### 🔗 Related Code/Notes
* [Day 12: Binary Search Notes](https://github.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/tree/main/Day12)

---
**Reflections:** The gap between 100 items and 1 billion items is massive, but for binary search, it's only a difference of 23 comparisons (7 vs 30). Math is powerful.
---
# Day 12 | Feb 02, 2026

## 🕒 Session: 06:00 AM - 07:50 AM
**Focus:** Iterative vs. Recursive Search Patterns.

### 🛠️ Tasks Completed
1.  **Refactored Day 09 Code:** - Moved the iterative Binary Search into a standalone function.
    - Fixed the `length` parameter bug to handle pointer decay correctly.
    - [View Code](https://github.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/blob/main/Day09/binary_shearch.c)
2.  **Recursive Binary Search:** - Implemented `recursiveSearch` using a divide-and-conquer approach.
    - Applied **Pointer Arithmetic** to interface with memory addresses directly.
    - [View Code](https://github.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/blob/main/Day12/Recursive_Binary_Search.c)



### 💡 Reflection
The jump from $O(n)$ to $O(\log n)$ is massive for large datasets. Understanding how the call stack handles the recursive boundaries ($low$ and $high$) makes the logic much more intuitive than nested loops.

### 🔗 Asset Links
- **Logic Diagram:** ![Binary Search Flow](https://raw.githubusercontent.com/Shubham-Jana-Dev/Learning-DAA-by-Myself/main/Day12/assets/binary-logic.png)
