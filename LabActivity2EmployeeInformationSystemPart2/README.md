# Lab Activity 2: Employee Information System (Part 2)

This folder contains a Java program developed as part of a laboratory activity for the Java programming course. The objective of this program is to simulate an **Employee Information System** that collects basic user input and performs multiple salary-related computations.

## 📁 File: `LabActivity2EmployeeInformationSystemPart2.java`

### ✅ Program Overview

This program allows the user to input personal details such as **first name**, **last name**, **age**, **hours worked**, and **hourly wage**. It then computes and displays the following:

- Daily, weekly, monthly, and gross yearly salary
- Net yearly salary (after deductions)
- Years remaining until retirement (based on a retirement age of 65)

### ⚙️ Key Features and Functions

| Feature                      | Description |
|-----------------------------|-------------|
| **User Input**              | Utilizes the `Scanner` class to collect data from the user via the console. |
| **Salary Computation**      | Computes salaries based on user input and standard working assumptions (5 days/week, 4 weeks/month, 12 months/year). |
| **Deductions**              | Calculates yearly deductions based on 32% tax and a fixed government benefit of PHP 1,500. |
| **Retirement Estimate**     | Displays the number of years left before the user reaches retirement age (65). |
| **Output Formatting**       | Ensures a user-friendly display using formatted strings and clear labeling. |

### 📊 Salary Computation Formula

- `Daily Salary` = `Hours Worked` × `Hourly Wage` (rounded to the nearest whole number)
- `Weekly Salary` = `Daily Salary` × 5
- `Monthly Salary` = `Weekly Salary` × 4
- `Gross Yearly Salary` = `Monthly Salary` × 12
- `Deductions` = (32% of Gross Yearly Salary) + PHP 1,500
- `Net Yearly Salary` = `Gross Yearly Salary` - `Deductions` (rounded to 1 decimal place)

### 💡 Sample Input and Output

```text
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
