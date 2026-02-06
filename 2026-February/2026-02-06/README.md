# 📔 Learning Journal | Feb 6, 2026

## 🕒 Session 1: 04:00 AM – 07:00 AM
**Focus:** Advanced Python Functionality & Error Resilience

### 🛠️ Tasks Completed
1. **Error Handling Architecture**:
   - Implemented `try-except` blocks to catch `NameError` and `ValueError`.
   - Used recursion in `ValueErrorHandling()` to ensure user input matches the expected data type.
2. **Variable Length Arguments (`*args`, `**kwargs`)**:
   - Mastered tuple packing/unpacking and keyword dictionary mapping.
   - Built a **Smart Billing** algorithm that cross-references items in `args` against a pricing table in `kwargs`.



**Working Area:** [PBSSD-Python-Learning/Day_20](https://github.com/Shubham-Jana-Dev/PBSSD-Python-Learning)

---

## 🕒 Session 2: 11:00 AM – 01:00 PM
**Focus:** PBSSD Web Development | CSS Layout & Depth

### 📝 Key Concepts Covered
* **`position`**: Explored the differences between `static`, `relative`, `absolute`, and `fixed`.
* **`z-index`**: Managed the stacking order of elements on the 3D Z-axis.
* **Layout Control**: Utilized `float` and `clear` for traditional grid structures.



---

## 🕒 Session 3: 02:00 PM – 05:00 PM
**Focus:** PBSSD Python | Deep Dive into Data Input

### 📝 Topics Covered
* **Advanced Input Methods**: Practiced capturing complex data using `map()`, `.split()`, and `eval()`.
* **Data Types**: Reviewed internal storage for `complex` numbers and nested structures (lists inside sets/dicts).
* **Efficiency**: Using `map(int, input().split())` for space-separated integer inputs.

---

## 🕒 Session 4: 07:00 PM – 11:00 PM
**Focus:** Problem Solving & Troubleshooting

### 🚀 Progress
- Spent the evening tackling a complex unsolved problem in the Python repository.
- **Victory**: Refined the `smart_bill1` function to use membership testing (`if i in kwargs`), improving lookup time from $O(n^2)$ (nested loop) to $O(n)$ average case.

---

### 💡 Reflection
The "Smart Billing" challenge was the highlight of the day. It forced me to think about how data is structured in memory. In my first version, I used nested loops, but in `smart_bill1`, I realized that checking a dictionary key is significantly faster. This connects back to my DAA studies on efficiency. On the CSS side, mastering `z-index` is a game-changer for the UI of my Book Billing project—it will help in creating modal overlays and sticky headers.

### 🔗 Quick Links
- **Python Practice Repo:** [PBSSD-Python-Learning](https://github.com/Shubham-Jana-Dev/PBSSD-Python-Learning)
- **Problem Solving:** [Basic.py Implementation](https://github.com/Shubham-Jana-Dev/Learning-by-myself/blob/main/Basic.cpp)
