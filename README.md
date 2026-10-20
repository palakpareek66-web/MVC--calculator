# MVC Calculator (Java Swing)

A simple **Calculator application** built in Java using the **MVC (Model-View-Controller)** design pattern with a **Swing GUI**. The project cleanly separates business logic, UI, and event handling into three components, making it easy to understand, maintain, and extend.

## Features

- Basic arithmetic operations: Addition, Subtraction, Multiplication, Division
- Clean separation of concerns using the MVC pattern
- Simple and intuitive Swing-based user interface
- Division by zero is safely handled

## Project Structure

```
├── CalculatorModel.java       # Business logic (Model)
├── CalculatorView.java        # GUI components (View)
├── CalculatorController.java  # Event handling & logic binding (Controller)
└── Main.java                  # Entry point of the application
```

## Tech Stack

- Java
- Java Swing (javax.swing)
- AWT Event Handling (java.awt.event)
- MVC Architecture

## How It Works

- **Model** (`CalculatorModel.java`) – Contains the core arithmetic operations (add, subtract, multiply, divide).
- **View** (`CalculatorView.java`) – Builds the GUI with input fields, operator buttons, and a result field.
- **Controller** (`CalculatorController.java`) – Listens for button clicks, fetches input from the View, performs calculations via the Model, and updates the View with the result.
- **Main** (`Main.java`) – Initializes the Model, View, and Controller together.

## How to Run

1. Clone the repository
   ```bash
   git clone <your-repo-link>
   ```
2. Open the project in any Java IDE (VS Code / Eclipse / IntelliJ)
3. Compile all files
   ```bash
   javac *.java
   ```
4. Run the application
   ```bash
   java Main
   ```

## Sample Output

```
------------------------------
|      MVC Calculator        |
------------------------------
First Number    [ 25         ]
Second Number   [ 10         ]
 [+] [-] [*] [/]
Result          [ 35.0       ]
------------------------------
```

## Author

Made with Java Swing following the MVC design pattern.
<img width="283" height="208" alt="image" src="https://github.com/user-attachments/assets/b37e039b-19e1-401c-b8c8-01622de0bbb1" />
