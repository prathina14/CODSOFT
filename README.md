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
