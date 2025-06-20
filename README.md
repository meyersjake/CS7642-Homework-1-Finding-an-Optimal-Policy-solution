# CS7642-Homework-1-Finding-an-Optimal-Policy-solution

Download Here: [CS7642 Homework #1 Finding an Optimal Policy solution](https://jarviscodinghub.com/assignment/homework-1-finding-an-optimal-policy-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

The game DieN is played in the following way.
Consider a die with N sides (where N is an integer greater than 1) and a nonempty set B of
integers. The rules of the game are:
1. You start with 0 dollars.
2. Roll an N-sided die with a different number from 1 to N printed on each side.
a. If you roll a number not in B, you receive that many dollars. (eg. if you roll the
number 2 and 2 is not in B, then you receive 2 dollars.)
b. If you roll a number in B, then you lose all of your obtained money and the game
ends.
3. After you roll the die (and don’t roll a number in B), you have the option to quit the game.
If you quit, you keep all the money you’ve earned to that point. If you continue to roll, go
back to step 2.
Procedure
● For this problem, determine an optimal policy for playing the game DieN with N sides. You
will be given N and an array B (isBadSide) which indicates which sides are bad. The policy
should depend on your current bankroll.
● What is the expected value of this game if you follow an optimal policy? Answer for the
problems you are given in the Solve for Code tab.
Examples
The following examples can be used to verify your calculation is correct.
● Input: N = 21, isBadSide = {1,1,1,1,0,0,0,0,1,0,1,0,1,1,0,1,0,0,0,1,0}, Output: 7.3799
● Input: N = 22, isBadSide = {1,1,1,1,1,1,0,1,0,1,1,0,1,0,1,0,0,1,0,0,1,0}, Output: 6.314
1
● Input: N = 6, isBadSide = {1,1,1,0,0,0}, Output: 2.5833
Resources
The concepts explored in this homework are covered by:
● Lectures
○ Lesson 1: Smoov & Curly’s Bogus Journey
● Readings
○ Littman (1996)(chapters 1-2)
Submission Details
Due Date: January 28, 2018 (AOE)
To complete the assignment calculate answers to the specific problems given, and submit
results, at
https://rldm.herokuapp.com

