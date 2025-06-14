# Lab Activity 2: Employee Information System (Part 2)

This folder contains a Java program developed as part of a laboratory activity for a Java programming course. The objective of this program is to simulate an **Employee Information System** that collects basic user input and performs multiple salary-related computations.

## 📄 File
- `LabActivity2EmployeeInformationSystemPart2.java`

## ✅ Program Overview
This Java console application prompts the user to input personal and work-related information, then calculates and displays the following:
- Daily, weekly, monthly, and gross yearly salaries  
- Net yearly salary after deductions  
- Years remaining until retirement (assuming retirement at age 65)

## ⚙️ Features

| Feature                  | Description |
|--------------------------|-------------|
| **User Input**           | Collects first name, last name, age, hours worked, and hourly wage. |
| **Salary Calculation**   | Computes salaries based on user input. |
| **Tax and Deduction**    | Applies a 32% tax and a fixed PHP 1,500 deduction. |
| **Retirement Estimation**| Calculates years left to retirement. |
| **Formatted Output**     | Displays results in a neat, readable format. |

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
   javac LabActivity2EmployeeInformationSystemPart2.java
   ```
3. Run the compiled class:
   ```bash
   java LabActivity2EmployeeInformationSystemPart2
   ```

### ▶️ Steps via IDE
1. Open your preferred Java IDE.
2. Create a new project or class file named `LabActivity2EmployeeInformationSystemPart2`.
3. Copy and paste the Java code into the editor.
4. Click **Run** or **Execute**.

## 📊 Salary Computation Summary
- Daily Salary = Hours Worked × Hourly Wage (rounded)
- Weekly Salary = Daily Salary × 5
- Monthly Salary = Weekly Salary × 4
- Gross Yearly Salary = Monthly Salary × 12
- Deductions = 32% of Gross + PHP 1,500
- Net Yearly Salary = Gross - Deductions (rounded to 1 decimal place)

## 🧾 Sample Output
```
Enter your first name: Joshua
Enter your last name: De Guzman
Enter your age: 25
Enter hours worked: 8
Enter hourly wage: 120

Employee Information
---------------------
Full Name:                DE GUZMAN, JOSHUA
Age:                      25 years old
Years to Retirement:      40 years old
Daily Salary:             PHP 960.00
Weekly Salary:            PHP 4800.00
Monthly Salary:           PHP 19200.00
Gross Yearly Salary:      PHP 230400.00
Net Yearly Salary:        PHP 155172.0
```

## 👨‍🎓 Author
**Name:** Joshua Dredd Stephen B. De Guzman  
**Course:** Bachelor of Science in Computer Science  
**Activity:** Lab Activity 2 – Java Programming

## 📁 Repository Structure
```
JavaLabActivities/
└── LabActivity2EmployeeInformationSystemPart2/
    ├── LabActivity2EmployeeInformationSystemPart2.java
    └── README.md
```

## 📌 Notes
- Assumes a 5-day workweek and 4-week months.
- Applies basic Java syntax: variables, scanner input, arithmetic operations, and formatted output.
- Great for beginner practice in Java and console-based applications.
