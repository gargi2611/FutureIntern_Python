# FutureIntern_Python
This GitHub repo showcases Python projects created during my internship at Future Intern. It includes a variety of tasks such as a calculator, number guessing game, snake game, tic-tac-toe game, random password generator, and rock-paper-scissors game. Each project demonstrates my coding skills and problem-solving abilities.


# Calculator

This Python script creates a graphical user interface (GUI) application for a standard calculator. The application allows the user to perform basic arithmetic operations and includes several special functions. The GUI is built using the Tkinter library.

**Features**
Basic Arithmetic Operations: Addition, subtraction, multiplication, division.

Special Operations: Modulus, percentage, square root, and square.

Utility Functions: Backspace, clear entry, decimal point.

User-Friendly Interface: Interactive buttons that change color on hover.

Tkinter: This library is used for creating the GUI. It is the standard Python interface to the Tk GUI toolkit.

MessageBox: Used for displaying error messages to the user if there are any issues with the calculation.

Math Library: Utilized to perform square root operations.

Eval Function: Used to evaluate mathematical expressions entered by the user. It is important to note that the eval function can be dangerous if used with untrusted input.

Button Bindings: The buttons change color on hover to improve user experience.


# Number Guessing Game

This Python script creates a graphical user interface (GUI) application for a number guessing game. The user is asked to guess a number between 1 and 100, and the application provides feedback on whether the guess is too high or too low until the correct number is guessed. The GUI is built using the Tkinter library.

**Features**

Random Number Generation: A random number between 1 and 100 is generated for the user to guess.

User Input: An entry field is provided for the user to input their guess.

Feedback: The application provides feedback indicating whether the guess is too high, too low, or correct.

Attempt Counter: The number of attempts taken to guess the correct number is tracked.

Game Completion: When the correct number is guessed, the game congratulates the user and disables further input.

Tkinter: This library is used for creating the GUI. It is the standard Python interface to the Tk GUI toolkit.

Random Library: Utilized to generate a random number between 1 and 100 using randint.

**Main Components:**

Label Widgets: Used to display text messages to the user.

Entry Widget: Used to capture user input for the guess.

Button Widget: Used to trigger the guess-checking function.

Check Guess Function: This function is called when the user clicks the "Guess" button. It checks the user's guess against the randomly generated number and updates the feedback label accordingly. It also tracks the number of attempts made by the user.

**User Interaction**

User Input: The user enters a number between 1 and 100 in the entry field.

Guess Check: Upon clicking the "Guess" button, the application evaluates the guess.

Feedback: The application updates the result label with feedback:
----> If the guess is correct, a congratulatory message is displayed, including the number of attempts, and the guess button is disabled.
----> If the guess is too high or too low, a hint message is displayed, encouraging the user to try again.


