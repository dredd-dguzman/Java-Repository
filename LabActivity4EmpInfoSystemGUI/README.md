# Lab Activity 4: Employee Information System with GUI (AWT)

This project implements a **Java GUI-based Employee Information System** using **Abstract Window Toolkit (AWT)**. It allows users to input employee data through a graphical interface, validate entries, and compute the employee's daily salary.

## 📄 File
- `LabActivity4EmpInfoSystemGUI.java`

---

## 🪟 Program Overview

This Java program uses the `java.awt` package to create a **graphical user interface** with input fields and a read-only text area for output. It includes **basic validation**, **event handling**, and **salary calculation** functionality.

### 👨‍💼 The program collects:
- First Name and Last Name
- Age (integer)
- Hours Worked (decimal)
- Hourly Rate (decimal)

### 💸 The program outputs:
- Full Name
- Age
- Daily Salary (hours × hourly rate), formatted to 2 decimal places

---

## ⚙️ Features

| Feature                   | Description |
|---------------------------|-------------|
| **AWT-Based GUI**         | Utilizes Frame, Label, TextField, Button, and TextArea components |
| **Input Validation**      | Checks for empty fields and valid numerical values |
| **Salary Computation**    | Calculates daily salary based on user inputs |
| **Error Handling**        | Displays error messages in the output area instead of crashing |
| **Responsive Output**     | Displays results in a clean and readable format |
| **Window Close Support**  | Exits the application when the close button is clicked |

---

## 💻 How to Run

### 🖥️ Prerequisites
- Java JDK (version 8 or higher)
- Terminal or an IDE (e.g., IntelliJ, Eclipse, NetBeans, VS Code)

### 🔧 Steps via Command Line
1. Open terminal and go to the directory containing the `.java` file:
   ```bash
   cd path/to/your/folder
   ```

2. Compile the program:
   ```bash
   javac LabActivity4EmpInfoSystemGUI.java
   ```

3. Run the application:
   ```bash
   java LabActivity4EmpInfoSystemGUI
   ```

### ▶️ Steps via IDE
1. Open your IDE and create a Java project.
2. Add a file named `LabActivity4EmpInfoSystemGUI.java`.
3. Paste the code.
4. Click **Run** or **Execute**.

---

## 🧾 Sample Output

```
[After user inputs the following:]
First Name: Joshua
Last Name: De Guzman
Age: 21
Hours Worked: 8
Hourly Rate: 100

[Output area displays:]
Full Name: Joshua De Guzman
Age: 21 years old
Daily Salary: PHP 800.00
```

---

## 👨‍🎓 Author

**Name:** Joshua Dredd Stephen B. De Guzman  
**Course:** Bachelor of Science in Computer Science  
**Activity:** Lab Activity 4 – Java Programming (AWT GUI)

---

## 📁 Project Structure

```
JavaLabActivities/
└── LabActivity4EmpInfoSystemGUI/
    ├── LabActivity4EmpInfoSystemGUI.java
    └── README.md
```

---

## 📝 Notes
- This activity is designed to demonstrate the basics of Java GUI development using AWT.
- Enhancements may include form resets, more user feedback, or moving to Swing for richer GUI controls.

