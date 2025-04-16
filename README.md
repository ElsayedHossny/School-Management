# 🎓 School Management System

A **console-based school management system** developed in C, designed to handle core operations such as student management, record keeping, and data search functionalities. The project showcases foundational programming concepts including **modular code**, **file handling**, and **user interaction** via a colored console UI.

---

## 🚀 Features

- 📋 Add new student records
- 🔍 Search for students by ID or name
- 🗂️ View all student data
- ✏️ Edit or delete existing records
- 🎨 Colorful console interface for improved UX
- 📁 Persistent data storage using files

---

## 🧱 Tech Stack

| Language | Tools         | Platform |
|----------|---------------|----------|
| C        | Code::Blocks  | Windows  |
|          | Console Color | CLI App  |

---

## 🗂️ Project Structure

School-Management/
│
├── main.c
│   └─ Entry point of the application. Contains the main menu and user interface logic.
│
├── function.c
│   └─ Implements core functionalities like add, search, edit, delete, and display student records.
│
├── function.h
│   └─ Header file declaring functions used in function.c.
│
├── console_color.h
│   └─ Utility header file for applying colored output in the console (for better UI experience).
│
├── students.txt
│   └─ Text file used for storing student records persistently (using file handling).
│
├── School_Management.cbp
│   └─ Code::Blocks project file, used to open and build the project easily within the IDE.
│
├── bin/
│   └─ Contains the compiled binary output (executable).
│
├── obj/
│   └─ Contains compiled object files during build process.
│
└── README.md
    └─ Project documentation file (you are reading it! 😄)

