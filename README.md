# 📚 Library Management System (C++)

A **console-based Library Management System** built using **C++** and **file handling**, designed to manage book and student records efficiently. This project is ideal for understanding OOP, binary file handling, and creating CRUD systems in C++.

---

## 💡 Features

### 🔖 Book Management
- 📌 Add new books
- ✏️ Modify book details
- ❌ Delete books
- 🔍 Search book by number
- 📃 Display all book records

### 🎓 Student Management
- 👤 Register new students
- ✏️ Modify student info
- ❌ Delete student records
- 🔍 Search student by admission number
- 📃 Display all student records

### 🔄 Book Issue & Return
- ✅ Issue books to students (only 1 book at a time)
- 🔁 Accept returned books
- 🧾 Calculates fine if returned after 15 days (₹1/day)
- ⛔ Blocks issue if previous book not returned

---

## 💾 Data Storage

- Stores data in binary files:
  - `book.dat` – Stores book records
  - `student.dat` – Stores student records

No external database required. All operations are done using fstream and binary serialization.

---

## 🧠 Concepts Used

- **Object-Oriented Programming (OOP)**
- **File Handling in C++**
- **Serialization of Classes**
- **Menu-Driven Programs**
- **Data Persistence without a Database**

---

## 📁 Folder Structure

