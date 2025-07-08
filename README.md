# 📝 Todo List CLI Application (C++)

A simple command-line Todo List application written in C++. It allows you to manage tasks by adding, displaying, marking them as completed, and removing them — all from your terminal.

---

## 🚀 Features

- ✅ Add a new task with:
  - Description
  - Due Date
  - Category
- 📋 View all tasks in a formatted table
- ✔️ Mark tasks as complete
- ❌ Remove tasks from the list
- 💡 Organized CLI-based interaction
- 🧼 Auto-refresh interface using `system("CLS")` for clean display

---

## 🖥️ Demo

```bash
Todo List Application
1. Add Task
2. Mark Task as Complete
3. Remove Task
4. Display Tasks
0. Exit

Enter your choice:
```

---

## 🧱 Code Structure

- **`struct Task`** — Represents an individual task
- **`class TodoList`** — Manages the list of tasks with methods:
  - `addTask()`
  - `markTaskComplete()`
  - `removeTask()`
  - `displayTasks()`

- **`main()`** — Handles CLI logic and interaction

---

## 📦 Requirements

- C++11 or later
- Compatible with all major operating systems that support standard C++ compilers

---

## ⚙️ How to Run

### 🧑‍💻 Compile and Run using g++

```bash
g++ todo.cpp -o todo
./todo
```

Or using any C++ IDE like Code::Blocks, Visual Studio, or Dev C++.

---

## 🛠️ Future Improvements

- Persistent storage using file I/O or database
- Colored CLI output for categories and status
- Filtering by category or due date
- Sort by due date or completion status
- Add reminder/notification support

---

## 👨‍💻 Author

Made with 💻 by Abhishek 

Feel free to contribute or suggest improvements!

---
