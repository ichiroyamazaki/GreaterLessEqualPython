# GreaterLessEqualPython

A beginner-friendly Python program designed to compare two integers and determine whether the first number is less than, greater than, or equal to the second number.

## Overview

GreaterLessEqualPython is a simple console-based programming activity that demonstrates how to accept numeric input and use conditional statements to compare values.

The program asks the user to enter two numbers, converts both inputs into integers, and uses `if`, `elif`, and `else` statements to determine their relationship.

**Important:** The current `main.py` contains a variable-name error: it refers to `numi` in the comparison statements instead of `num1`. As a result, the program raises a `NameError` before it can display the comparison result. This documentation describes the intended functionality and identifies the current issue.

## Intended Features

- **Two-number input:** Prompts the user to enter two integers.
- **Integer conversion:** Converts input strings to integers using `int()`.
- **Number comparison:** Uses conditional statements to compare two values.
- **Three possible outcomes:** Identifies whether the first number is less than, greater than, or equal to the second number.
- **Console output:** Displays a descriptive message for the comparison result.

## Requirements

- Python 3
- A terminal or Python-compatible IDE, such as Visual Studio Code or IDLE

No external libraries are required.

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Run the program:

   ```bash
   python main.py
   ```

   Depending on your system, use `python3 main.py` instead.

4. Enter the first integer.
5. Enter the second integer.

**Current status:** The program needs the variable-name error fixed before it can complete the comparison successfully.

## Example Output

The following is the **intended output after correcting the variable-name error**.

### First number is smaller

```text
Enter the first number: 5
Enter the second number: 10
The first number is less than the second number.
```

### First number is greater

```text
Enter the first number: 20
Enter the second number: 10
The first number is greater than the second number.
```

### Both numbers are equal

```text
Enter the first number: 15
Enter the second number: 15
The first number is equal to the second number.
```

## How It Works

1. The program requests two numbers from the user.
2. It converts both inputs to integers.
3. The `if` statement checks whether the first number is smaller than the second.
4. The `elif` statement checks whether the first number is greater than the second.
5. The `else` statement handles the case where both numbers are equal.
6. The program prints the corresponding message.

## Learning Objectives

This activity demonstrates fundamental Python concepts:

- Variables and user input
- Integer conversion
- Comparison operators (`<` and `>`)
- Conditional statements (`if`, `elif`, and `else`)
- Console output
- Basic algorithm design

## Known Issues and Limitations

- **Variable-name error:** The comparison statements use `numi` instead of `num1`, causing a `NameError`.
- Invalid input, such as letters, causes a `ValueError` during integer conversion.
- The program accepts integers rather than decimal values.
- Only one comparison is performed per execution.

## Author

**Ichiro Yamazaki**

## License

No license has been specified for this repository.
