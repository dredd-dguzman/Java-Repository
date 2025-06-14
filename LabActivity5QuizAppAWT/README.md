# Lab Activity 5: Quiz Application (Java AWT)

This project is a simple **Quiz Application** built with Java using the **Abstract Window Toolkit (AWT)** for graphical user interface. It presents multiple-choice questions, accepts user answers, validates input, and displays the final score.

## 📄 File
- `LabActivity5QuizAppAWT.java`

---

## 🧠 Program Overview

This GUI application presents a **3-question quiz**. Each question offers four options, and the user selects one using radio-style checkboxes. It includes input validation (ensuring an answer is selected), score tracking, and displays the final result at the end.

---

## 📋 Features

| Feature                | Description |
|------------------------|-------------|
| **AWT-Based GUI**      | Frame, Label, Button, CheckboxGroup, and Layouts |
| **Multiple-Choice UI** | 2x2 grid of options using radio-style checkboxes |
| **Dynamic Questioning**| Auto-updates to next question upon clicking 'Next' |
| **Score Tracking**     | Tracks number of correct answers |
| **Error Messaging**    | Prompts if no option is selected before proceeding |
| **Final Score Output** | Shows result after the last question |
| **Custom Styling**     | Fonts, colors, and cursor customizations |

---

## ❓ Sample Questions

1. What is the capital of France?  
2. Which language is used for Android development?  
3. What is the result of 2 + 2 * 2?

Each has 4 multiple-choice options rendered via checkboxes.

---

## 🖥️ How to Run

### Requirements
- Java JDK 8 or later
- Terminal or IDE (e.g., IntelliJ, Eclipse, NetBeans)

### Via Terminal
```bash
cd path/to/your/folder
javac LabActivity5QuizAppAWT.java
java LabActivity5QuizAppAWT
```

### Via IDE
1. Create a new Java project.
2. Add `LabActivity5QuizAppAWT.java` to the source folder.
3. Run the application.

---

## 🧾 Example Output

```
Q1: What is the capital of France?
[A] Paris  [B] Rome  [C] Berlin  [D] Madrid

[User selects "A. Paris", clicks Next...]

...

[After all questions answered]
Quiz Completed! Your score: 3 out of 3
```

---

## 👨‍🎓 Author

**Name:** Joshua Dredd Stephen B. De Guzman  
**Course:** Bachelor of Science in Computer Science  
**Activity:** Lab Activity 5 – Java Programming (AWT GUI)

---

## 📁 Project Structure

```
JavaLabActivities/
└── LabActivity5QuizAppAWT/
    ├── LabActivity5QuizAppAWT.java
    └── README.md
```

---

## ✅ Notes

- You can expand this quiz by adding more questions to the `questions`, `options`, and `answers` arrays.
- Optionally, this project could be upgraded to Java Swing or JavaFX for enhanced styling and UX.
