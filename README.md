# GTK Graphical Calculator

## Overview

Project Description The Calculator Method is a simple, user-friendly application that features a graphical user interface (GUI) to allow users to interact with the various operations it offers. It is designed for those who require a simple and accessible tool to quickly perform basic calculations. Users are able to perform basic arithmetic operations such as addition, subtraction, multiplication, and division, and are able to use a set of parentheses to offer control over which order the operations are performed. Designed with simplicity in mind, the app offers a simple GUI which provides a straightforward and efficient way to perform calculations, without any complex features.

This project was developed as a collaborative effort by a team, leveraging the use of Git and GitHub for version control. The project highlights teamwork and collaboration in a shared repository, allowing for modular and scalable development.

## Team Collaboration and Learning Experience

This project was developed as part of a team-based assignment, using a shared GitHub repository to manage the codebase collaboratively. This process provided valuable insights into:
	1. Version Control:
	    - Learned to effectively use Git for managing commits, branches, pull requests, and resolving merge conflicts.
	2. Collaboration in a Shared Repository:
	    - Leveraged GitHub to coordinate teamwork and ensure seamless integration of contributions from all members.
	3. Teamwork:
	    - Collaborated to divide responsibilities, review code, and merge changes efficiently.
	4. Code Modularity:
	    - Maintained clear division of tasks, ensuring the project remained modular and scalable for future enhancements.

This experience enhanced my understanding of Git workflows, collaborative development practices, and the importance of clear communication and documentation.

## Features

Basic arithmetic operations: addition, subtraction, multiplication, and division.
Includes parentheses to allow the user to order their operations in a specific way.
Includes a negative toggle to allow input for negative numbers.
A user-friendly GUI that includes buttons 0-9, arithmetic operations, negative toggle, parentheses, clear, and equals.
Includes a help button to guide users on how to use the calculator.

## Getting Started

This calculator is a command-line utility, which requires access to the various file that were used to develop the program. The following steps can guide you on how to set up the calculator for your own usage.

1. Clone the repository: git clone https://github.com/Behzad-J/GraphicalCalculator-C
2. To use the GUI you will need to install the required libraries, which involves downloading and setting up the GTK toolkit sudo apt install libgtk-4-dev
3. Compile the program using the Makefile: make main-calculator
4. Run the application: ./calculator

## How to Use

Launch the app in the command-line to open the calculator interface.
Use the buttons on the GUI to perform operations of your choosing. a) Enter numbers using the digit buttons (0-9) b) Select an operation (+, -, , /) to apply to the numbers. c) Use parentheses to prioritize parts of the calculation.
Click the equals button when you would like to perform the calculation.
Select the clear button, to clear all input numbers and operations.
Press the help button to view the guide in the terminal.

## Usage Examples

Basic Arithmetic: Press 14 / 2 --> Click = --> Result: 7 Press 17 - 5 + 9 --> Click = --> Result: 21
Using Parentheses: Press 2 * (4 + 1) --> Click = --> Result: 10 Press 8 / (6 - 2) --> Click = --> Result: 2
Clear Input: Enter any calculation --> Click Clear --> Resets all input
FAQ Q: Is this app cross-platform? A: It is designed for systems with C compilers and compatible GUI libraries. Read the Getting Started page! Q: Does the app offer more complex operations? A: No! We wanted to focus on designing a user-friendly calculator that allows users to perform quick and basic calculations.
