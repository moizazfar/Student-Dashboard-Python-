# 🎓 Student Dashboard (Python)

A simple, interactive **Student Management System** built using Python.  
This program allows users to add students, record marks, delete records, and view detailed student information through a menu-driven console interface.

---

## 📑 Table of Contents
- [Features](#-features)
- [How It Works](#-how-it-works)
- [Project Structure](#-project-structure)
- [Usage](#-usage)
- [Example Output](#-example-output)
- [Future Improvements](#-future-improvements)
- [License](#-license)

---

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

---

## 🧠 How It Works

The program uses:
- **Lists** to store students and their marks  
- **Functions** for modular operations  
- A **while loop** to handle menu-based navigation  

Each option triggers the relevant function.

---

## 📁 Project Structure


Main functions included:
- `student_dashboard(students, student_marks)`
- `add_student(students)`
- `delete_student(students)`
- `add_student_marks(students, student_marks)`
- `view_student_details(students, student_marks)`

---

## ▶️ Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
