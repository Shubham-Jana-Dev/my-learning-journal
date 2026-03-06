# 📔 Learning Journal | March 04, 2026

## 🕒 Session 1: 05:00 AM – 07:00 AM
**Focus:** Python Data Structures | Advanced Dictionary Manipulation

### 🚀 Implementation Lab
Worked on a futuristic data simulation to practice membership testing and formatted iteration.
* **Logic Gap Identified:** Discovered that `list(dict)` only returns keys. Implemented a `for` loop to capture both keys and values in a formatted string list.
* **Operations:** Practiced `pop()` for deletion and conditional checks using the `in` keyword to prevent access errors.

---

## 🕒 Session 2: 07:30 AM – 10:00 AM
**Focus:** C++ OOP | Encapsulation, State, and Validation

### 🛠️ The Three-Level Challenge
Progressed through three distinct levels of Object-Oriented programming to master data hiding.

1. **Level 1 (The Bank):** Built an `owner` class with transaction logic. Used `double` for precision and implemented checks to prevent withdrawals exceeding the current balance.
2. **Level 2 (The State):** Created a Smart Light controller. Managed a `Brightness` state strictly between 0 and 100, ensuring `dim()` and `brighten()` calls never breached these boundaries.
3. **Level 3 (Data Integrity):** Developed a Student Portal. Implemented 4-digit roll number validation and a 0.0–4.0 GPA scale. Added a derived logic function `isHonorStudent()` to process student status.

---

## 🕒 Session 3: 10:00 AM – 11:15 AM
**Focus:** Technical Research | GitHub Linguist & Repository Analytics

### 🔍 Research Summary
Investigated why GitHub often mislabels projects as "Jupyter Notebook" instead of "Python."
* **The Root Cause:** GitHub uses a library called **Linguist**. Because `.ipynb` files are JSON-based and contain large amounts of metadata/images, they often overshadow actual code in language statistics.
* **The Engineering Fix:** Discovered the use of `.gitattributes` for language overrides. 
* **Implementation:** Adding `*.ipynb linguist-language=Python` forces the platform to accurately count the underlying logic.

---

## 🕒 Session 4: 07:00 PM – 09:00 PM
**Focus:** Academic Review
* Consolidated university lecture notes and reviewed the day's practical implementations for long-term retention.

---

### 💡 Reflection
Today highlighted the importance of "Defensive Programming." Whether it was preventing a bank account from going negative or forcing a GPA to stay within a 4.0 limit, I learned that a class is only as good as the rules it enforces. Additionally, researching the GitHub Linguist issue taught me that even global platforms have technical limitations that we, as developers, can solve with the right configuration.

### 🔗 Quick Links
- **C++ Challenges:** [OOP Encapsulation Lab](https://github.com/Shubham-Jana-Dev/Low-Level-Architecture)
- **Python Dictionaries:** [lmg_2036_logic.py](https://github.com/Shubham-Jana-Dev/PBSSD-Python-Learning)
-
