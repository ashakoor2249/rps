11/02/2021
This program simpulates a rock paper scissors game with the user and the computer. A simple practice program utilzing input, if else statements, annd random.

11/03/2021

Significant changes were made to the program. 

First IntEnum was imported from enum, so that each choice is associated with a number. 

A class called Action was created to reference the different choices by assigning each one a value. This way comparisons 
are more efficant straightforward and have a class name assoiciated with them. 

Defined a get user selection fucntion that asks the user to input their choice among rock paper and scissors. Each chocie is associated with a number for comparison purposes thanks to the Action class. The choice is kid proofed to ensure that the user puts in correct input which is a number between 0 and 2 inclusive.

Defined get computer selection which randomly assigns the computer either rock paper or scissors. Again each choice is associated
with a number for comparison purposes.

Defined determine winner function that takes the user choice and computer choice as parameters, compares the two, and determines the 
winner based on the rules of rock paper scissors.


