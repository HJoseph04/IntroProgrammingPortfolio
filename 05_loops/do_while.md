# LOOPS / Do While

A Do-While loop that must run at least once before checking your condition.
The DO block executes first, and it's strictly AFTER that when does your program check whether that loop repeats.
So, when the program reaches a do‑while, it A) runs the body, B) evaluates the condition, and then C) either loop back or stop depending on whether the condition is true.
It's a good way to avoid duplicating code for no reason, because you don't need a trial run like you're on some F1 qualifier before the loop starts.
Overall, this loop gives you a clean enough wat to make sure this code is executed once wjile still having a controlled repetition.

do 
{
  // code to execute
}
while (insert condition);

REFERENCES:
https://www.w3schools.com/cs/cs_while_loop.php
