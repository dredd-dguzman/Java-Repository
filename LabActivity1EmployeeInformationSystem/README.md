# Lab Activity 1: Employee Information System

This folder contains a basic Java program created for a laboratory activity. The goal of this program is to simulate an **Employee Information System** that collects personal and work-related input from the user and calculates the employee's daily salary.

## 📄 File
- `LabActivity1EmployeeInformationSystem.java`

## ✅ Program Overview
This Java console-based program uses `Scanner` to capture user input and calculates the daily salary using the number of hours worked and the hourly wage.

### It collects:
- First Name and Last Name
- Age
- Hours Worked
- Hourly Wage

### It calculates:
- Daily Salary (Hours Worked × Hourly Wage)

---

## ⚙️ Features

| Feature              | Description |
|----------------------|-------------|
| **User Input**       | Captures employee name, age, hours worked, and hourly wage. |
| **Salary Calculation**| Multiplies hours worked by hourly wage to get daily salary. |
| **Formatted Output** | Displays the daily salary with two decimal places. |

---

## 💻 How to Run

### 🖥️ Prerequisites
- Java JDK installed (version 8 or higher)
- A terminal/command prompt or an IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)

### 🔧 Steps via Command Line
1. Navigate to the directory containing the `.java` file:
   ```bash
   cd path/to/your/folder
   ```
2. Compile the Java file:
   ```bash
   javac LabActivity1EmployeeInformationSystem.java
   ```
3. Run the compiled class:
   ```bash
   java LabActivity1EmployeeInformationSystem
   ```

### ▶️ Steps via IDE
1. Open your preferred Java IDE.
2. Create a new project or class file named `LabActivity1EmployeeInformationSystem`.
3. Paste the code into the editor.
4. Click **Run** or **Execute**.

---

## 🧾 Sample Output

```
Enter your first name: Joshua
Enter your last name: De Guzman
Enter your age: 25
Enter hours worked: 8
Enter hourly wage: 120

Employee Information
---------------------
Full Name   : Joshua De Guzman
Age         : 25 years old
Daily Salary: PHP 960.00
```

---

## 👨‍🎓 Author

**Name:** Joshua Dredd Stephen B. De Guzman  
**Course:** Bachelor of Science in Computer Science  
**Activity:** Lab Activity 1 – Java Programming

---

## 📁 Repository Structure

```
JavaLabActivities/
└── LabActivity1EmployeeInformationSystem/
    ├── LabActivity1EmployeeInformationSystem.java
    └── README.md
```

---

## 📌 Notes
- Great for beginners to practice Java basics such as user input, variables, arithmetic operations, and formatted output.
- This activity lays the foundation for more advanced versions like Lab Activity 2, which adds multi-level salary computations.
