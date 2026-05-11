# SWITCH
A Switch statement is another way that makes decisions in a program, but it's used for situations where you're checking a value between several options. Sorta like the Monty Hall Problem if you watch Let's Make A Deal. Is it Door number 1? 2? 3? Either of them?
Anyway, a switch lets you list each case so that the code is easier to handle and read, unlike using a long chain of IF and ELSE IF statements.
When we reach a switch, it looks at our value once, and then jumps directly into the matching case, which organizes our flow.
Each case for example acts like its own side on a fork in the road, and you can decide exactly what happens for each specific value. One key word to note is how you would use Break for each case. As seen below, because without it, the program will just keep running over to the next case without anything to stop it, even if you don't want that. You should be able to use it for something like menu items, days, months, zodiac signs and what not.
Overall, the switch gives a clean and structured way to handle multiple outputs without cluttering your code.


SYNTAX:
switch (insert expression here)
{
case 1:
// insert code here
break;

// Continue from here

case default:
// insert code here
break;

}

EUREKA:
The Wind Chill part on Assignment 4. Had to look closely at the ranges. though i initially had trouble trying to mix in the wind speed with the air temperature. But it turns out all i do was just use the charts numbers based on the color of the ranges and just use them for simple boolean logic in each case.

COMMON MISTAKE:
A little silly one, but i sometimes forget that i have to end every case with a break; 

REFERENCES:
https://www.w3schools.com/cs/cs_switch.php
