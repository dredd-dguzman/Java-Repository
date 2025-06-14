# Lab Activity 6: To-Do List Application (Java Swing)

This Java Swing-based application implements a simple **To-Do List** with task creation, status tracking, and table display. It showcases modular GUI design using two windows: the main viewer and a pop-up task form.

## 📄 File
- `LabActivity6SwingToDoList.java`

---

## 🧠 Program Overview

The program features:
- A **main window** displaying tasks in a table
- An **"Add Task" button** to open a secondary form window
- A **form pop-up** where users can enter task details and choose status
- Upon saving, the task appears in the main table

---

## 📋 Features

| Feature                  | Description |
|--------------------------|-------------|
| **Java Swing GUI**       | Uses `JFrame`, `JTable`, `JTextField`, `JComboBox`, etc. |
| **Task Management**      | Add tasks with name, description, and status |
| **Popup Form**           | Cleanly designed input form for adding tasks |
| **Status Dropdown**      | Choose between *Not Started*, *Ongoing*, or *Completed* |
| **Auto-Center Windows**  | Both windows are centered on screen or relative to each other |
| **Validation**           | Input validation with error message using `JOptionPane` |

---

## 🖥️ How to Run

### Requirements
- Java JDK 8 or higher
- IDE (e.g., IntelliJ, Eclipse) or Terminal

### Via Terminal
```bash
cd path/to/project
javac LabActivity6SwingToDoList.java
java LabActivity6SwingToDoList
```

---

## ✅ Sample Flow

1. Click **"Add Task"**
2. A form window opens:
   - Enter **Task Name**
   - Optionally write a **Description**
   - Select a **Status** from the dropdown
3. Click **"Save Task"**
4. The task is added to the main table in the viewer window

---

## 🧾 Example Output

| Task Name     | Task Description       | Status     |
|---------------|------------------------|------------|
| Final Project | Implement login system | Ongoing    |
| Buy Groceries | Milk, Bread, Eggs      | Not Started|

---

## 📁 Project Structure

```
JavaLabActivities/
└── LabActivity6SwingToDoList/
    ├── LabActivity6SwingToDoList.java
    └── README.md
```

---

## 👨‍🎓 Author

**Name:** Joshua Dredd Stephen B. De Guzman  
**Course:** Bachelor of Science in Computer Science  
**Activity:** Lab Activity 6 – Java Programming (Swing GUI)

---

## 🛠️ Notes

- Tasks are stored in memory only (no file or database persistence)
- You can extend this app by adding edit/delete functionality, deadlines, or task priorities
