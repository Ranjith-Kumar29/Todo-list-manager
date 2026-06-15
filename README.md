# 📋 Task Management System

A modern, dashboard-style desktop **To-Do List application** built with **Python (Tkinter)**, **SQLite**, and **tkcalendar**. It offers a clean dark-themed UI with real-time statistics, priority sorting, search, and due-date reminders.

<img width="1920" height="974" alt="image" src="https://github.com/user-attachments/assets/fe0e7d7d-e68a-4730-b9ce-1e5d6e4ac7cf" />


## ✨ Features

- ➕ Add tasks with **name, priority, and due date**
- ✏️ Edit existing tasks in a dedicated popup window
- ✅ Mark tasks as **Completed**
- 🗑 Delete tasks
- 🔍 Search tasks by keyword
- 📌 Sort tasks by priority (High → Medium → Low)
- 📊 Live dashboard cards showing **Total / Completed / Pending** tasks
- ⏰ Daily reminder popup for tasks due today
- 💾 Persistent storage using **SQLite**

## 🛠️ Tech Stack

- **Python 3**
- **Tkinter** & **ttk** – GUI framework
- **tkcalendar** – Date picker widget
- **SQLite3** – Local database

## 🚀 Getting Started

### Prerequisites

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python todo_v2_professional.py
```

## 📁 Project Structure

```
├── todo_v2_professional.py   # Main application file
├── requirements.txt           # Python dependencies
├── tasks.db                    # SQLite database (auto-created)
└── README.md
```

## 📦 Requirements

```
tkcalendar
```

## 👤 Author

**Ranjith Kumar**

## 📄 License

This project is licensed under the MIT License.
