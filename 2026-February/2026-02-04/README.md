# 📔 Learning Journal | Feb 4, 2026

## 🕒 Session 1: 04:00 AM – 08:00 AM
**Focus:** C++ Logic Visualization & Modern Iteration

### 🛠️ Tasks Completed
1. **Nested Loop Mastery (Pattern Printing):**
   - **`dynamicPartten`**: Implemented a dynamic square matrix generator.
   - **`dynamicRightangleTriangle`**: Developed coordinate-based logic `if(i+j >= rows_num)` to render mirrored triangles.
2. **Modern C++ Array Handling:**
   - Implemented **Range-based for loops** (`for(int x : array)`) for cleaner, safer iteration.
   - Practiced array length calculation using `sizeof(array)/sizeof(array[0])`.
3. **Encapsulation:**
   - Created reusable utility functions like `arrayPrint` and `findMax`.

**Working Area:** [Basic.cpp (Learning-by-myself)](https://github.com/Shubham-Jana-Dev/Learning-by-myself/blob/main/Basic.cpp)

---

## 🕒 Session 2: 10:00 AM – 03:30 PM
**Focus:** University Lectures
- Attended B.Tech CSE core curriculum sessions.

---

## 🕒 Session 3: 06:00 PM – 10:00 PM
**Focus:** Data Structures Lab (Python) | Day 19

### 📝 Key Concepts: List vs. Tuple vs. Set
Explored the fundamental differences in how Python manages memory, uniqueness, and mutability.

| Feature | List (`[]`) | Tuple (`()`) | Set (`{}`) |
| :--- | :--- | :--- | :--- |
| **Ordered** | Yes | Yes | No |
| **Mutable** | Yes (Append/Remove) | **No** (Immutable) | Yes (Add/Remove) |
| **Uniqueness** | Allows Duplicates | Allows Duplicates | **Unique Only** |
| **Access** | Index-based | Index-based | Value-based |



### 🛠️ Practical Implementations
* **Data Cleaning:** Built `create_unique_list()` using set-casting to remove duplicates in $O(n)$ time.
* **Indexing Verification:** Proved that while Tuples are immutable, they still support positional indexing like Lists.
* **Set "Updates":** Since Sets are unordered, implemented a workaround to "update" values by removing the old element and adding the new one.

### 💡 Engineering Insight: Hashing vs. Linear Search
In the context of B.Tech studies, the choice between these structures is about **Time Complexity**:
- **List Search:** $O(n)$ (Linear scan).
- **Set Search:** **$O(1)$** (Hashing), making it significantly faster for large-scale membership testing.

**Working Area:** [PBSSD-Python-Learning/Day_19](https://github.com/Shubham-Jana-Dev/PBSSD-Python-Learning/tree/main/Day_19)

---

### 💡 Reflection
Today was a study in contrasts: handling manual memory logic in C++ patterns this morning, then leveraging high-level hashing logic in Python this evening. The transition to C++ for logic practice is feeling more natural, especially with range-based loops, while the Python lab reinforced the importance of choosing the right container for memory performance.

### 🔗 Quick Links
- **C++ Exploration:** [Basic.cpp](https://github.com/Shubham-Jana-Dev/Learning-by-myself/blob/main/Basic.cpp)
- **Python Lab Repo:** [Day 19: Advanced Data Structures](https://github.com/Shubham-Jana-Dev/PBSSD-Python-Learning/tree/main/Day_19)
