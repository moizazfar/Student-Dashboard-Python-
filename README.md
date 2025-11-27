
# 🎓 Student Dashboard (Python)

A simple, interactive **Student Management System** built using Python.  
This program allows users to add students, record marks, delete records, and view detailed student information through a menu-driven console interface.
## Table of Contents

- [Features](#-features)
- [How It Works](#-how-it-works)
- [Project Structure](#-project-structure)
- [Usage](#-usage)
- [Example Output](#-example-output)
- [Future Improvements](#-future-improvements)
- [License](#-license)


## 🚀 Features


### ✔ Add Students  
Add new student names to the system with automatic formatting.

### ✔ Delete Students  
Remove existing students from the list.

### ✔ Add Student Marks  
Store marks for three subjects per student.  
Marks are aligned with the student list using matching index positions.

### ✔ View Student Details  
Displays:
- Student names  
- Individual subject marks  
- Total marks  
- Status for students without marks  

### ✔ Exit Option  
Cleanly ends the dashboard interface.


## 🧠 How It Works

The program uses:
- **Lists** to store students and their marks  
- **Functions** for modular operations  
- A **while loop** to handle menu-based navigation  

Each option triggers the relevant function.
## 📁 Project Structure

student_dashboard_(Python).ipynb

Main functions included:
- `student_dashboard(students, student_marks)`
- `add_student(students)`
- `delete_student(students)`
- `add_student_marks(students, student_marks)`
- `view_student_details(students, student_marks)`
## ▶️ Usage

### 1. Clone the repository
```bash
git clone https://github.com/moizazfar/Student-Dashboard-Python.git
```

### 2. Open the file
Using Anaconda (Jupyter Notebook)

### 3. Use the menu to manage student data
You will be prompted with a dashboard:

## 🖥️ Example Output
```python
______________________________________

          Student Dashboard
______________________________________

  PRESS 1 TO ADD STUDENT
  PRESS 2 TO DELETE STUDENT
  PRESS 3 TO ADD STUDENT MARKS
  PRESS 4 TO VIEW STUDENT
  PRESS 5 TO STOP

______________________________________

Press number: 1
Enter student name to add student to list: Alice
*STUDENT ADDED SUCCESSFULLY*

Press number: 3
Enter name of student to add their marks: Alice
Enter marks of subject 1: 90
Enter marks of subject 2: 85
Enter marks of subject 3: 88
Marks added successfully

Press number: 4

______________________________________

      ALL STUDENTS WITH THEIR MARKS
______________________________________

Student details...
Name: Alice | Marks: 90, 85, 88 | Total: 263
```





## 🔮 Future Improvements

- Save/load data using text or JSON files
- Validate inputs to avoid crashes
- Add more subjects or grading system
- Build a GUI-based version using Tkinter/PyQt
- Convert project into a class-based OOP program
## 📜 License

This project is open-source. You may modify or use it freely.
