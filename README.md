## TITLE: Simple Streamlit Calculator (or Streamlit Basic Calculator)

### Description:-
This Streamlit web application provides a user-friendly interface for performing basic arithmetic operations (addition, subtraction, multiplication, and division). Users can input two numerical values and select an operation from a dropdown menu. The application then calculates and displays the result. It also includes error handling for division by zero and other potential exceptions.

### Responsibilities (Modules/Components and their Functions):-

#### * User Input Module (st.number_input):
* Responsible for collecting numerical input from the user for the two operands.
* Ensures that the input is treated as a number.
* Provides a default value (0.0) for convenience.
#### * Operation Selection Module (st.selectbox):
* Presents the user with a dropdown menu to choose the desired arithmetic operation (Add, Subtract, Multiply, Divide).
* Stores the selected operation as a string.
#### * Calculation Module (Logic using eval() and operations dictionary):
* Takes the two numerical inputs and the selected operation.
* Uses a dictionary to map operation names to symbols.
* Constructs a string expression (e.g., "5 + 3").
* Uses eval() to evaluate the expression and perform the calculation.
* Handles division by zero errors using a conditional check.
* Handles other potential errors during evaluation using a try...except block.
#### * Output Display Module (st.write, st.error):
* Displays the result of the calculation to the user.
* Uses st.write for normal output and st.error for displaying error messages in a visually distinct way.
#### * User Interaction Module (st.button):
* Triggers the calculation when the user clicks the "Calculate" button.
* Controls the flow of the application.

### Libraries Used:
Streamlit (streamlit as st): This is the core library for creating the web application interface. It provides all the necessary components for input, output, and layout.

### Summary:
This project demonstrates the creation of a simple interactive web calculator using Streamlit. The application is structured into distinct modules responsible for handling user input, operation selection, performing the calculation, displaying the output, and managing user interaction. The use of Streamlit simplifies the process of building the user interface and handling user interactions. The inclusion of error handling makes the application more robust. The structure of the code, especially using the operations dictionary, improves readability and maintainability. This project is a valuable exercise for understanding the basics of Streamlit and building simple web applications.




