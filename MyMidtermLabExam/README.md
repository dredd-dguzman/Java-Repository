# Midterm Lab Exam: IT Ticket Processing System (Java Console App)

This Java console-based application simulates a simple **IT Ticket Processing System**. It allows users to add, update, display, and generate reports on IT service tickets. This lab exercise demonstrates effective use of arrays, loops, input validation, and control structures.

## 📄 File
- `MyMidtermLabExam.java`

---

## 🧠 Program Overview

The system features a menu-driven interface that performs the following operations:
- Add new support tickets with urgency and default status
- Update the status of existing tickets
- Display all tickets with their current status
- Generate a summary report of ticket statuses

---

## 📋 Features

| Feature                    | Description |
|----------------------------|-------------|
| **Array-based Storage**    | Uses arrays to hold ticket data (description, urgency, status) |
| **Ticket Limit**           | Supports up to 5 tickets only (as per lab requirement) |
| **Menu Interface**         | Repeats until user selects "Exit" |
| **Input Validation**       | Prevents invalid inputs for menu, urgency, and status fields |
| **Update Protection**      | Prevents updating a ticket already marked as "Resolved" |
| **Report Generation**      | Counts and displays total, pending/in progress, and resolved tickets |

---

## 📁 Project Structure

```
JavaLabActivities/
└── MidtermLabExam/
    ├── MyMidtermLabExam.java
    └── README.md
```

---

## 🖥️ How to Run

### Requirements
- Java JDK 8 or higher
- IDE (e.g., IntelliJ, Eclipse) or Terminal

### Via Terminal
```bash
cd path/to/project
javac MyMidtermLabExam.java
java MyMidtermLabExam
```

---

## 💡 Sample Menu Flow

```
=== IT Ticket Processing System ===
1. Add Ticket
2. Update Ticket Status
3. Show All Tickets
4. Generate Report
5. Exit
Enter Choice:
```

### Example Ticket Display
```
--- Ticket List ---
1. [High] Wi-Fi not working - Status: Pending
2. [Medium] Printer jammed - Status: In Progress
```

---

## ✅ Status Options

| Field        | Valid Inputs             |
|--------------|---------------------------|
| **Urgency**  | Low, Medium, High         |
| **Status**   | Pending (default), In Progress, Resolved |

---

## 👨‍🎓 Author

**Name:** Joshua Dredd Stephen B. De Guzman  
**Course:** Bachelor of Science in Computer Science  
**Activity:** Midterm Laboratory Exam – Java Programming

---

## 🛠️ Notes

- This is a **console application** with no GUI
- Tickets are stored only during runtime (no file/database persistence)
- Good starting point for transitioning to object-oriented ticket systems in Java

