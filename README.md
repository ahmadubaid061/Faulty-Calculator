# Faulty-Calculator
This repository contains a faulty calculator implemented using JavaScript, designed to perform incorrect operations 10% of the time for a fun twist. The calculator takes two numbers as input from the user and executes the following intentionally wrong operations:

- Addition (`+`) becomes subtraction (`-`)
- Multiplication (`*`) becomes addition (`+`)
- Subtraction (`-`) becomes division (`/`)
- Division (`/`) becomes multiplication (`*`)

# Techniques
The implementation is provided using three different JavaScript techniques:

1. **Using Simple If-Else Statements**: A straightforward approach where conditional statements determine the operation based on user input, with a random 10% chance to apply the faulty logic.
2. **Using Readline for Taking Input from Users**: This method utilizes the `readline` module to interactively collect user input from the console, adding a dynamic input-handling feature.
3. **Using eval() Function**: The easiest approach, leveraging the `eval()` function to evaluate expressions, with a 10% chance of swapping operations for the faulty behavior.

This project showcases creative problem-solving and different programming styles in JavaScript.
