
This program simpulates a rock paper scissors game with the user and the computer. A simple practice program utilzing input, if else statements, annd random.

Significant changes were made to the program. 

First the random and IntEnum module are imported at the start of the program.
The Action class is defined which defines symbolic names bound to unique constant values. This way the user inputs either 0 1 2 for 
paper scissor respectivly and removes the issues in inputing string. Random capitiliztion, accidental misspelling of the words etc.
Inputting a number to represent the choices is much simpler.

First function in the program is the get user selection function, which as the name suggests gets the user choice of either rock, 
paper, or scissors. After the user inputs a number between 0 and 2 for their choice the function returns the choice and stores it into
the user action variable.

The second function in the program is the get computer selection which is similiar to the get user selection function, but utilizes
random to get either rock, paper, or scissors. That random choice is stored in the computer action variable.

The Third fucntion is the determine winner function which takes as input the user action and computer action variables. A series of if 
else statements determines the winner based on the rules of rock paper scissors.

The body of the program is a while loop which allows the user to play as many games as they desire.

