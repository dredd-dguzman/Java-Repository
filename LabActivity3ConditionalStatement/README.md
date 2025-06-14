# Lab Activity 3: Employee Information System with Conditional Statements

This folder contains a Java console program created for Lab Activity 3 in a Java programming course. It improves upon the previous employee salary system by integrating **conditional logic and validation**, including age restrictions, input validation, and role classification.

## 📄 File
- `LabActivity3ConditionalStatement.java`

## ✅ Program Overview
This Java application gathers employee data and uses **conditional statements (`if`, `else`, and `switch`)** to validate and compute salary details while enforcing input rules based on age, hours worked, and job role.

### The program collects:
- First Name and Last Name
- Age (with validation)
- Hours Worked per Day (with validation)
- Hourly Wage
- Role Code (1: Manager, 2: Supervisor, 3: Staff, 4: Intern)

### It calculates:
- Daily, Weekly, Monthly, and Gross Yearly Salaries
- Deductions based on tax and benefits
- Net Yearly Salary
- Years until Retirement

---

## ⚙️ Features

| Feature                   | Description |
|---------------------------|-------------|
| **Input Validation**      | Age restrictions (18–64), work hours must be > 0 and ≤ 24 |
| **Role Classification**   | Switch-case to assign roles based on numeric codes |
| **Salary Computation**    | Multi-level salary calculation with conditional deductions |
| **Tax Rule**              | 32% tax if gross yearly salary > PHP 250,000 |
| **Retirement Estimate**   | Displays remaining years until age 65 |
| **Formatted Output**      | Clean and readable salary report |

---

## 💻 How to Run

### 🖥️ Prerequisites
- Java JDK (version 8 or higher)
- Terminal/command prompt or an IDE (e.g., IntelliJ IDEA, Eclipse, VS Code)

### 🔧 Steps via Command Line
1. Navigate to the project directory:
   ```bash
   cd path/to/your/folder
   ```
2. Compile the Java file:
   ```bash
   javac LabActivity3ConditionalStatement.java
   ```
3. Run the program:
   ```bash
   java LabActivity3ConditionalStatement
   ```

### ▶️ Steps via IDE
1. Open your IDE and create a Java project.
2. Add a new file named `LabActivity3ConditionalStatement.java`.
3. Paste the code into the file.
4. Click **Run** or **Execute**.

---

## 🧾 Sample Output

```
Enter your first name: Joshua
Enter your last name: De Guzman
Enter your age: 22
Enter hours worked per day: 8
Enter hourly wage: 120
Enter role code (1-Manager, 2-Supervisor, 3-Staff, 4-Intern): 2

Employee Information
---------------------
Full Name:                DE GUZMAN, JOSHUA
Age:                      22 years old
Position:                 Supervisor
Years to Retirement:      43 years
Daily Salary:             PHP 960.00
Weekly Salary:            PHP 4800.00
Monthly Salary:           PHP 19200.00
Gross Yearly Salary:      PHP 230400.00
Net Yearly Salary:        PHP 228900.00
```

---

## 👨‍🎓 Author

**Name:** Joshua Dredd Stephen B. De Guzman  
**Course:** Bachelor of Science in Computer Science  
**Activity:** Lab Activity 3 – Java Programming

---

## 📁 Repository Structure

```
JavaLabActivities/
└── LabActivity3ConditionalStatement/
    ├── LabActivity3ConditionalStatement.java
    └── README.md
```

---

## 📌 Notes
- Demonstrates the practical use of conditional logic in Java.
- Provides basic error handling and data filtering based on logical rules.
- Helps build foundational understanding of `if`, `else`, and `switch` constructs.
