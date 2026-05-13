# LOOPS / Do While

A Do-While loop is a kind of loop that must run at least once before checking your condition.
The DO block executes first, and it's strictly AFTER when your program checks whether that loop repeats.
So, when the program reaches a do‑while, it A) runs the body, B) evaluates the condition, and then C) either loop back or stop depending on whether the condition is true.
It's a good way to avoid duplicating code for no reason, because you don't need a trial run like you're on some F1 qualifier before the loop starts.
Overall, this loop gives you a clean enough wat to make sure this code is executed once wjile still having a controlled repetition.

do 
{
  // code to execute
}
while (insert condition);

EUREKA:
On Assignment 4, i tried building up on the example i tried to build up on for practice, the ValidInput one to be specific. I wanted to see at the time if 7 worked out (i was still a little rusty at the time), but then what clicked was the boolean logic later on. And the while turned out to be just assuming i put in something that's strictly false.

COMMON MISTAKE:
The while part of the loop. I kept thinking that even if it's false from the start, i just had to run the loop at least once regardless.

REFERENCES:
https://www.w3schools.com/cs/cs_while_loop.php
