# Simple Calculator in Java

## Input from the User:
- The program uses the `Scanner` class to read input from the user.
- It prompts the user to enter two numbers (`num1` and `num2`).
- The user is also asked to choose an arithmetic operation: 
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)

## Switch Case to Perform Operation:
- A switch statement is used to handle the operation based on the user's choice:
  - **Addition (`+`)**: Adds the two numbers.
  - **Subtraction (`-`)**: Subtracts the second number from the first.
  - **Multiplication (`*`)**: Multiplies the two numbers.
  - **Division (`/`)**: Divides the first number by the second, with a check to prevent division by zero.

## Error Handling:
- The program includes a check for division by zero. 
- If the second number is zero and the user selects division, the program outputs an error message stating that division by zero is not allowed.

## Output:
- The result of the selected arithmetic operation is printed to the console.
