# future-intern-projects
Task 01 is to create a calculator which perform basic arithmetic operations:
To create a basic calculator with a GUI (Graphical User Interface) that displays the operations and results just like a real-life calculator.
Explanation:
GUI Setup:
tk.Tk() is used to create the main window.
StringVar() is used to create a variable for the calculator display.
Entry() creates the display for the calculator where the expression and results are shown.

Buttons:
The buttons represent digits 0-9, operators (+, -, *, /), a decimal point, and a clear button.
Button() is used to create each button, and command is used to bind a function to each button press.
The grid() method is used to place the buttons on the calculator interface in a grid layout.

Functions:
press(num): Updates the expression in the display when a number or operator is pressed.
equalpress(): Evaluates the expression and updates the display with the result.
clear(): Clears the current expression.

Main Loop:
gui.mainloop() keeps the calculator window open and responsive.
Running the Code:
When you run the code, a calculator window will open. You can use it just like a physical calculator by clicking the buttons, and it will display the operations and results on the screen.

Number Guessing Game is also a part of task 01 below is the explanation of number guessing game
How It Works:
Random Number Generation:
The program generates a random number between 1 and 100 when it starts and every time the game is reset.

User Input:
The user enters a guess in a text entry field.
When the user clicks the "Submit Guess" button, the program checks the guess against the random number.

Hint Display:
If the user's guess is too low or too high, a hint is displayed on the screen.
If the guess is correct, the program congratulates the user and resets the game.

GUI Setup:
The tkinter library is used to create the graphical user interface.
The interface includes labels, an entry field, and a button.

Resetting the Game:
When the correct number is guessed, the game resets by generating a new random number and clearing the entry field.

Running the Code:
Running the script opens a window where you can enter a number between 1 and 100 and receive hints until you guess the correct number.
The interface is simple and user-friendly, mimicking a basic guessing game you might find in a console, but with a graphical display.

TASK 02 (Tic Tac Toe Game)
Explanation:
Grid Creation:
The program creates a 3x3 grid using buttons. Each button corresponds to a cell in the Tic-Tac-Toe grid.

Button Click Handling:
When a button is clicked, the program checks if the button is empty and if the game is still ongoing. The button is then marked with the current player's symbol ("X" or "O"), and the turn switches to the other player.

Win/Draw Checking:
After each move, the program checks for any winning combination of three identical symbols in a row, column, or diagonal. If a player wins, the winning buttons turn green, and a message is displayed.
If all buttons are filled without a winner, the program declares a draw.

Reset and Exit Options:
The program includes "Restart" and "Exit" buttons. The "Restart" button clears the grid and resets the game state, allowing players to start a new game. The "Exit" button closes the program.

Game Loop:
The game continues until a player wins or the grid is full, at which point the players can choose to restart or exit the game.
This program provides a simple yet fully functional Tic-Tac-Toe game with a graphical interface, perfect for two players.

TASK 03 (Random Password Generator)
Explanation:
Password Criteria:
The user can input the desired length of the password.
The user can select the types of characters to include in the password (uppercase letters, lowercase letters, numbers, and special characters) through checkboxes.

Password Generation:
The program checks the user's selections and creates a pool of characters based on the criteria.
It then generates a random password of the desired length using the selected character types.

User Interface:
The GUI includes options for the user to select the password length and the types of characters to include.
The generated password is displayed in an entry widget, allowing the user to easily copy it.

Error Handling:
The program ensures that the user selects a valid length and at least one type of character. If these conditions are not met, an error message is shown.

Customization:
The user can adjust the length of the password and choose which character sets to include, allowing for flexible password generation.
This program provides a simple yet powerful tool for generating secure and customizable passwords.
