# Student Grade Calculator

A Python command-line application that takes a student's details and marks across five subjects to calculate their total score, average, percentage, final grade, and pass/fail status.

## Features
- **Student Details:** Records student name and roll number.
- **Custom Subjects:** Allows entering any 5 subject names and their corresponding marks (out of 100 each).
- **Complete Result Summary:** Calculates and displays:
  - Total marks (out of 500)
  - Average score
  - Overall percentage
  - Letter grade (`A` to `F`)
  - Final `PASS` or `FAIL` status

## Grading Criteria (Out of 500)

| Total Marks | Grade |
| :--- | :--- |
| 450 and above | **A** |
| 400 – 449 | **C** |
| 350 – 399 | **D** |
| 300 – 349 | **E** |
| Below 300 | **F** |

- **Pass Condition:** Total marks greater than **200** (`PASS`), otherwise `FAIL`.

## Requirements
- Python 3.x

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Smriti-Rajput/Student-grade-calculator.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Student-grade-calculator
   ```
3. Run the Python script *(replace `calculator.py` with your actual `.py` filename)*:
   ```bash
   python calculator.py
   ```

## Sample Output
```text
========================================
           STUDENT RESULT
========================================
Student's Name: Smriti
Student's Rollno: 101
Subject1 : Math
Subject2 : Science
Subject3 : English
subject4: History
Subject5: Computer
Marks obtained in Math: 92
Marks obtained in Science: 88
Marks obtained in English: 85
Marks obtained in History: 90
Marks obtained in Computer: 95
Total Marks obtained out of 500 : 450.0
Average : 90.0
Percentage: 90.0
Grade : A
PASS
```
