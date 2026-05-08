Score to Grade Converter 🎓

## Description
This Python program evaluates a numerical score entered by the user (between 0.0 and 1.0) and converts it into a standard letter grade (A, B, C, D, or F). It includes input validation to ensure the program handles out-of-range values gracefully before attempting any calculations.

## Context
This project was built as an exercise for the "Programming for Everybody (Getting Started with Python)" course from the University of Michigan on Coursera. It focuses on practicing multi-way branching and error handling in Python.

## Skills Demonstrated
* **Multi-way Branching:** Using chained `if`, `elif`, and `else` statements to evaluate multiple conditions sequentially.
* **Data Validation:** Checking if the input falls within the acceptable range (0.0 to 1.0) and using the `quit()` function to halt execution if the data is invalid.
* **Type Casting:** Converting string inputs into floating-point numbers.

## Grade Scale
* >= 0.9 : A
* >= 0.8 : B
* >= 0.7 : C
* >= 0.6 : D
* < 0.6 : F

## Usage
Run the script in your terminal. You will be prompted to enter a score:

**Valid Input Example:**
```text
Enter Score: 0.85
B
