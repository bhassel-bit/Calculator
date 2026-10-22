# Calculator
Java calculator app

Overview
This is a simple command-line calculator written in Java. It asks the user to enter two numbers, choose a math operation, and then displays the result.

I created this project to practice Java fundamentals, including user input, variables, conditional statements, and basic arithmetic.
Features
- Addition
- Subtraction
- Multiplication
- Division
- Prevents division by zero
- Displays a message if the user chooses an invalid menu option

Technologies Used

- Java
- Scanner class for reading keyboard input

How to Run

Requirements: Java Development Kit (JDK) installed.
1. Save Calculator.java inside a folder named day3, matching the package day3; declaration in the code.
2. Open a terminal in the folder containing day3.
3. Compile the program:
   javac day3/Calculator.java
4. Run the program:
   java day3.Calculator
5. Follow the prompts to enter two numbers and select an operation (1–4).

Example

Enter the first number
10
10.0
Enter the second number
5
5.0
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
1
1
Result: 15.0

How It Works

1. The program uses Scanner to collect two numbers as double values.
2. It displays four operation choices.
3. The user selects an operation by entering a number from 1 to 4.
4. An if / else if statement performs the selected calculation.
5. The program prints the result, or an error message for division by zero or an invalid operation choice.

Current Limitations

- The program performs one calculation each time it runs.
- Entering text instead of a valid number or menu choice can cause an input error.

Possible Future Improvements

- Allow users to perform multiple calculations without restarting.
- Add input validation for non-numeric entries.
- Organize the arithmetic operations into separate methods.
