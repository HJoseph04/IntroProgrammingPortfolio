# LOOPS / For vs While

In this area of loops, a for and while loop generally both repeat the same code, but they're used in different situations.
For the FOR, use this loop for when you already know how many times you want your program to run, like using iterations and incrementing for tracing.
For the WHILE however, it's flexible and is better when you know the condition only, not the amount of iterations, so that the loop keeps running something until something in the code changes that condition.
They seem interchangable at first until when you get to readability and intention, FOR is for counting and WHILE just continues on repeat until something is no longer true.
Overall, understanding when to choose each one makes the program cleaner and helps avoid any infinite loop and/or override.

FOR
for (insert statements) 
{
  // code 
}

WHILE
while (insert condition) 
{
  // code 
}

EUREKA:
8th question on the For While assignment. I initially had trouble figuring out how to succesfully implement N, but then i realized that it sort of feels like simplified backwards iterations similar to the one on the final, decrementing.

COMMON MISTAKE:
I sometimes forget to update the variable to update the condition. It just gives me an infinite loop that goes on and on without stopping.

REFERENCES:
https://www.w3schools.com/cs/cs_for_loop.php
https://www.w3schools.com/cs/cs_while_loop.php
