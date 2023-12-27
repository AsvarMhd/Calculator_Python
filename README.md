# Calculator_Python
1st Python Project

This Python code defines a simple calculator program that allows the user to perform basic arithmetic operations such as addition, subtraction, multiplication, division, exponentiation, and finding the remainder. The program runs in a loop, prompting the user for input until the user chooses to terminate the program.

Arithmetic Functions:

add(a, b): Returns the sum of a and b.
subtract(a, b): Returns the difference of a and b.
multiply(a, b): Returns the product of a and b.
divide(a, b): Returns the result of dividing a by b. It handles exceptions in case of division by zero.
power(a, b): Returns a raised to the power of b.
remainder(a, b): Returns the remainder when a is divided by b.
Operation Selection Function:

select_op(choice): Takes a user's input choice and performs the corresponding arithmetic operation. It also handles termination and reset requests.
Main Loop:

The program runs an infinite loop (while True) that repeatedly prompts the user to select an operation.
The user is presented with a menu of operations and is prompted to enter a choice.
The user's input is then passed to the select_op function to perform the desired operation.
If the user enters #, the program terminates. If the user enters $, it resets the calculator.
Menu Display:

The user is presented with a menu showing the available operations, termination, and reset options.
User Input:

The user is prompted to enter a choice, and the entered choice is then processed.
Exit and Reset:

If the user enters #, the program prints "Done. Terminating" and exits.
If the user enters $, the program resets, allowing the user to perform more calculations.
Input Validation:

The code attempts to convert user inputs to floating-point numbers, validating the input. If the input is not a valid number, the user is prompted to enter it again.
