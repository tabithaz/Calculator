# Java Swing Calculator

A basic calculator application built in Java using **Swing** for the GUI.  
Supports basic arithmetic operations: addition, subtraction, multiplication, and division.

## Features
- Graphical interface with **SpringLayout** for display and **GridLayout** for buttons.
- Supports `+`, `-`, `x`, `/` operations.
- Decimal number input.
- Prevents multiple decimal points.
- Displays results instantly after pressing `=`.

## Tech Stack
- Java 8+
- Swing (GUI)
- MVC-style separation with `CalculatorGui`, `CalculatorService`, and `CommonConstants`.

## How to Run
1. Compile all `.java` files:
```bash
javac -d . *.java
```

2. Run the application:

```bash
java CalculatorApp
```
