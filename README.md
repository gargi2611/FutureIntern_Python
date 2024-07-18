# FutureIntern_Python
This GitHub repo showcases Python projects created during my internship at Future Intern. It includes a variety of tasks such as a calculator, number guessing game, snake game, tic-tac-toe game, random password generator, and rock-paper-scissors game. Each project demonstrates my coding skills and problem-solving abilities.


# Calculator

This Python script code creates a graphical user interface (GUI) application for a standard calculator. The application allows the user to perform basic arithmetic operations and includes several special functions. The GUI is built using the Tkinter library.

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

This Python script code creates a graphical user interface (GUI) application for a number guessing game. The user is asked to guess a number between 1 and 100, and the application provides feedback on whether the guess is too high or too low until the correct number is guessed. The GUI is built using the Tkinter library.

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



# Rock Paper Scissor Game

Rock, Paper, Scissors Game
This Python script code creates a graphical user interface (GUI) application for the classic game of Rock, Paper, Scissors. The user plays against the computer, and the game keeps track of the scores.

**Features**

Player and Computer Choices: The user can select rock, paper, or scissors by clicking the corresponding button.

Random Computer Choice: The computer randomly selects rock, paper, or scissors.

**Game Logic**: The game determines the winner based on the classic rules:
**Rock beats scissors.
Scissors beat paper.
Paper beats rock.**

-----> If the player's choice and the computer's choice are the same, it's a tie.
-----> If the player's choice beats the computer's choice, the player wins.
-----> Otherwise, the computer wins.


Score Tracking: The game keeps track of the player's and computer's scores.

Result Display: The game displays the choices made by the player and the computer, as well as the result of each round.

Tkinter: This library is used to create the GUI. It provides various widgets such as labels, buttons, and frames to build the interface.

Random Library: Utilized to generate the computer's choice randomly from "rock", "paper", or "scissors".

**Main Components:**

Labels: Used to display scores, player and computer choices, and results.

Buttons: Used to capture the player's choice of rock, paper, or scissors.

Play Method: This method is called when a player makes a choice. It determines the computer's choice, compares the two choices, updates the scores, and displays the result.


**User Interaction**

User Choice: The user selects rock, paper, or scissors by clicking the corresponding button.

Computer Choice: The computer randomly selects rock, paper, or scissors.

Result Determination: The game logic determines the winner based on the choices.

Score Update: The scores for the player and the computer are updated accordingly.

Display Results: The choices and results are displayed on the screen.




# Tic Tac Toe Game
This Python script code creates a graphical user interface (GUI) application for the classic game of Tic Tac Toe. Two players can play against each other, taking turns to place their marks (⭕ and ❌) on a 3x3 grid.

**Features**

Two-player Game: Two players take turns to place their marks on the grid.

Turn Indicator: The game displays whose turn it is.

Win Detection: The game detects when a player wins.

Draw Detection: The game detects when the game is a draw.

Reset Button: Players can reset the game to start a new match.

Message Boxes: Informative pop-up boxes to announce the winner or a draw.

**Game Logic:**

Click Method: Handles the player's move by updating the button text with the player's mark and checking for a win or draw.

Check Win Method: Checks rows, columns, and diagonals for three matching marks to determine a win.

Check Draw Method: Checks if all buttons are filled without a winner to determine a draw.

Reset Method: Resets the game state, clearing all button texts and resetting the player's turn.

**Main Components:**

Tkinter: This library is used to create the GUI. It provides various widgets such as labels, buttons, and frames to build the interface.

MessageBox: Utilized to display pop-up messages for game events like winning or drawing.

Buttons: Represent the 3x3 grid where players place their marks. Buttons are dynamically created in a nested loop and stored in a 2D list.

Labels: Used to display the current player's turn and game status.

Reset Button: Allows the players to reset the game and start over.

**User Interaction**

Player Move: The current player clicks on an empty button to place their mark (⭕ or ❌).

Turn Switch: The game switches the turn to the other player.

Win/Draw Check: After each move, the game checks if there is a winner or if the game is a draw.

Game Over: If a player wins or the game is a draw, the game displays the result and disables further moves until the reset button is clicked.

Reset: Players can click the reset button to start a new game.


# Snake Game
This is a classic Snake game implemented using Python and the Pygame library. The objective is to control the snake to eat food and grow in length, while avoiding collisions with the walls or itself.

**Features:**

User Control: Use the arrow keys to control the direction of the snake.

Food: Randomly placed on the screen, eating food increases the snake's length.

Collision Detection: Game ends if the snake collides with the walls or itself.

**Requirements:**
Python 3.x
Pygame library


**How to Run:**
Install Pygame: pip install pygame
Run the script: python snake_game.py


# Random Password Generator
This is a Random Password Generator application created using Python and Tkinter. It allows users to generate strong and secure passwords with customizable length and character sets.

**Features:**

Customizable Length: Users can specify the length of the password.
Character Sets: Users can include uppercase letters, lowercase letters, numbers, and special characters.
GUI: User-friendly interface built with Tkinter.


**Requirements:**
Python 3.x
Tkinter library (usually included with Python)
