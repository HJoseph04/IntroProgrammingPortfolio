# SWITCH
A Switch statement is another way that makes decisions in a program, but it's used for situations where you're checking a value between several options.
A switch lets you list each case so that the code is easier to handle ad read, unlike using a long chain of IF and ELSE IF statements.
When we reach a switch, it looks at our value once, and then jumps directly into the matching case, which organizes our code flow.
Each case for example acts like its own side on a fork in the road, and you can decide exactly what happens for each specific value. One key word to note is how you would use Break for each case. As seen below, because without it, the program will just keep running over to the next case without anything to stop it, even if you don't want that. You should be able to use it for something like menu items, days, months, zodiac signs etc.
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
