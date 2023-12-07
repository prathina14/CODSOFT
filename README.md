# CODSOFT

CALCULATOR:
The provided Python code uses the Tkinter library to create a graphical user interface (GUI) for a basic calculator. The calculator GUI allows users to perform arithmetic operations such as addition, subtraction, multiplication, and division through a user-friendly interface.

The code defines three functions:

btnClick(number):

This function is called when a numeric button or an operator button (+, -, *, /) is clicked.
It updates a global variable val by appending the clicked number or operator.
The updated value is then displayed on the calculator screen.
btnClear():

This function is triggered when the "C" button is clicked.
It resets the global variable val and clears the display on the calculator screen.
btnEquals():

This function is called when the "=" button is clicked.
It evaluates the expression stored in the global variable val using the eval() function.
The result is converted to a string and displayed on the calculator screen.
The graphical user interface is set up using Tkinter:

The main window is created with the title "My calci" and specific dimensions.
An Entry widget (display) is used to show the input and output of the calculator.
Numeric buttons (0-9) and operator buttons (+, -, *, /) are created with specific configurations such as font, border, height, width, and command functions.
Additional buttons for "C" (clear), "0" (zero), "/" (division), and "=" (equals) are also included.
The code then enters the main event loop (root.mainloop()), allowing users to interact with the calculator GUI by clicking the buttons and performing calculations. Overall, the code provides a simple and functional calculator with a graphical interface for ease of use.


ROCK PAPER SCISSORS:
The provided Python code implements a simple Rock, Paper, Scissors game with a graphical user interface (GUI) using the Tkinter library. Here's a description of the code:
Importing Libraries:

The code brings in some tools it needs to work with, like Tkinter for making the game visually and "random" for generating computer choices.
Creating the Game Window:

It makes a window for the game to happen in. The window has a size of 300x300 pixels and a title that says "Rock Paper Scissor Game."
Computer's Choices:

The computer can choose Rock, Paper, or Scissors randomly, and these choices are stored in a dictionary.
Game Functions:

There are functions that handle resetting the game and disabling player input.
Player's Choices:

There are functions for when the player picks Rock, Paper, or Scissors. The computer then makes its choice, and the game decides who wins based on the rules.
Display Labels and Frames:

Labels are used to show what the player and computer chose, and another label displays the game result. These labels are organized in a frame.
Buttons for Player Choices:

There are buttons for the player to pick Rock, Paper, or Scissors.
Reset Button:

There's a button to reset the game if the player wants to play again.
Running the Game:

The code starts the game and keeps it running so that players can interact with the buttons and play Rock, Paper, Scissors.
In summary, the code creates a simple game where the player can pick Rock, Paper, or Scissors, and the computer makes a random choice. The outcome is displayed on the screen using Tkinter.
