# Employee Information System

This repository contains a simple Java console application designed to collect and display basic employee information, including their daily salary. This project serves as a fundamental example of user input handling and basic data processing in Java.

---

## Project Structure

This project consists of a single Java file:

* `LabActivity1EmployeeInformationSystem.java`: Contains the main application logic for gathering employee details and calculating their daily salary.

---

## Features

The Employee Information System performs the following actions:

* **User Input**: Prompts the user to enter their **first name**, **last name**, **age**, **hours worked**, and **hourly wage**.
* **Data Collection**: Utilizes the `Scanner` class to efficiently capture various data types (String, int, float) from the console.
* **Information Display**: Presents a formatted summary of the collected employee data, including their full name and age.
* **Salary Calculation**: Automatically calculates the employee's **daily salary** based on the entered hours worked and hourly wage.
* **Formatted Output**: Displays the daily salary formatted to two decimal places for clear financial representation.
* **Resource Management**: Properly closes the `Scanner` object to prevent resource leaks.

---

## How to Run

To run this Java application, follow these steps:

1.  **Ensure Java is Installed**: Make sure you have a Java Development Kit (JDK) installed on your system. You can download it from the [Oracle website](https://www.oracle.com/java/technologies/downloads/) or use an open-source alternative like OpenJDK.

2.  **Save the Source Code**: Save the provided Java code into a file named `LabActivity1EmployeeInformationSystem.java`.

3.  **Compile the Code**: Open a terminal or command prompt, navigate to the directory where you saved the file, and compile the Java code using the Java compiler:

    ```bash
    javac LabActivity1EmployeeInformationSystem.java
    ```

4.  **Run the Application**: After successful compilation, run the application using the Java Virtual Machine:

    ```bash
    java LabActivity1EmployeeInformationSystem
    ```

    The application will then prompt you to enter the required employee information directly in the console.

---

## Code Explanation

The `LabActivity1EmployeeInformationSystem.java` file contains the `main` method, which is the entry point of the application.

* **`import java.util.Scanner;`**: Imports the `Scanner` class, which is essential for reading input from the console.
* **`Scanner Scanner = new Scanner(System.in);`**: Initializes a `Scanner` object to handle user input from the standard input stream (`System.in`).
* **Input Prompts**:
    * `System.out.print("Enter your first name: ");`
    * `String FirstName = Scanner.nextLine();`
    * Similar lines are used to collect the last name, age, hours worked, and hourly wage, using appropriate `Scanner` methods like `nextLine()`, `nextInt()`, and `nextFloat()` for each data type.
* **`System.out.println("\nEmployee Information");`**: Prints a header for the employee information display.
* **`System.out.println("Full Name : " + FirstName + " " + LastName);`**: Concatenates the first and last names to display the full name.
* **`System.out.println("Age : " + Age + " years old");`**: Displays the entered age.
* **`Float DailySalary = HoursWorked * HourlyWage;`**: Calculates the daily salary by multiplying hours worked and hourly wage.
* **`System.out.printf("Daily Salary: PHP %.2f\n", DailySalary);`**: Uses `printf` for formatted output, ensuring the `DailySalary` is displayed with exactly two decimal places and a "PHP" prefix.
* **`Scanner.close();`**: Closes the `Scanner` object. This is a crucial step to release system resources associated with the scanner, preventing potential resource leaks.

---
