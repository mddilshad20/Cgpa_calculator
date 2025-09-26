# 🎓 CGPA Calculator (C++)

This is a simple **CGPA Calculator** program written in **C++**.  
It allows students to enter course details (name, grade, and credit hours),  
then calculates their **Cumulative Grade Point Average (CGPA)**.

---

## 📌 Features
- Input any number of courses.
- Validate grades (A+, A, B+, B, C+, C, D, F).
- Validate credit hours (must be positive).
- Convert grades to grade points.
- Calculate CGPA using the formula:

\[
CGPA = \frac{\text{Total Grade Points}}{\text{Total Credits}}
\]

- Display a **course-wise summary table** with grades and credits.
- Show final **Total Credits, Total Grade Points, and CGPA**.

---

## 🛠️ How to Compile
Use **g++** (GNU C++ Compiler):

```bash
g++ cgpa_calculator.cpp -o cgpa_calculator
```

This will create an executable named `cgpa_calculator`.

---

## ▶️ How to Run
Run the compiled program:

```bash
./cgpa_calculator
```

On Windows (MinGW):

```bash
cgpa_calculator.exe
```

---

## 🖥️ Example Usage
```
📘 CGPA Calculator
-------------------------
Enter the number of courses: 3

📚 Enter details for Course 1:
Course Name: Mathematics
Grade (A+, A, B+, B, C+, C, D, F): A
Credit Hours: 4

📚 Enter details for Course 2:
Course Name: Physics
Grade (A+, A, B+, B, C+, C, D, F): B+
Credit Hours: 3

📚 Enter details for Course 3:
Course Name: Chemistry
Grade (A+, A, B+, B, C+, C, D, F): C
Credit Hours: 2

📋 Course-wise Grade Summary:
-----------------------------------------
  No.        Course Name     Grade   Credits
    1         Mathematics        A         4
    2             Physics       B+         3
    3           Chemistry        C         2
-----------------------------------------
🎯 Total Credits: 9
🌟 Total Grade Points: 69
📈 Final CGPA: 7.67
```

---

## 📂 File Structure
```
cgpa_calculator.cpp   # Main program source code
README.md             # Project documentation
```

---

## ✅ Requirements
- C++11 or higher
- g++ / clang / MSVC compiler

---

## 👨‍💻 Author
Made with ❤️ by *[Your Name]*
