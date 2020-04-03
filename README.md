# COMP2113 Proposal
Proposal for COMP2113 Project
Liang Zhuo  UID:3035608849
Wu Yuxi UID:3035534957
We are going to use C++ to make the “24 Points” game.
Rule:
1.	The computer will ask for player’s name and ask him if he want to keep the score of this trial. If he chooses “yes”, the computer will count his score and store in a file called “Players record”; otherwise, only his name will be recorded while his score replaced by ‘*’.

2.	The computer will randomly generate 4 integer numbers from 1 to 9, these four numbers will be shown on the screen.

3.	The player can choose to use these following numerical operations:
   (i). Add, subtract, multiple, divide
   (ii). Factorial, Permutation, Combination
   (iii). Brackets, e.g. if the player want to do addition before multiple
   (iv). Rounding up

4.   About the counting principle of the score:
   (i). Correctly get 24 as a result: +10
   (ii). Use numerical operation (ii)&(iv) once: +5
   (iii). Use numerical operation (iii) once: -3

5.	After the player enters his response, the computer will generate a file named “all.txt” which listed all the possible answers with their according scores. The computer will ask the player whether he is willing to open it or not.

6.	Each trial will be recorded in a file called “record.txt”, when the player want to quit the game, the records will be shown on the screen.

7.	 Program codes in multiple files
We would write one .cpp file, one .h file for definitions and one Makefile.

8. Proper indentation and naming styles
We would make our code as clear and as easy to read as possible. We would name our variables according to their meaning and use tabs properly.

9. In code documentation
We would add useful and detailed comments in our code.

Functions we will use:
1. double factorial (double n)
2. double P (double m, double n)
3. double C (double m, double n)
4. double R (double n)
5. void generatenumber (int n)
