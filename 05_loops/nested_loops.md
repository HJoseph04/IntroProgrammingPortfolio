# LOOPS / Nested Loops

A Nested loop is something that occurs when you place one loop inside another, it can also be associated when you're doing arrays.
When executing these kinds of loops, it always completes every cycle of the inner loop before moving the outer loop forward by one step, also known as incrementing (or decrementing if you want to go backwards).
It can feel confusing trying to keep track what's which and which, but once you are able to trace this loop, you will start to feel a certain pattern as you reach the end.
It's the perfect thing to use for patterns, grids, and is something you should definitely stufy for come an exam.
Overall, nested loops give you a grat way to use logic in multiple layers and repeat actions across 2 dimensions.

for (int i = [initial value]; i [boolean operator] [length of array]; i++ OR i-- [increment]) // Outer loop 
{
    for (Same Thing For J) // Inner loop 
    {
        (output code)
    }
    // additional code if needed
}

EUREKA:
During the final, i wasn't sure about the decrement part at first on one of the loops, can't exactly remember where it was. But it was when it was explained before it was officially time when i was tracing the loop that this means iterations for i are going backwards from 6 to 0

COMMON MISTAKE:
The steps on how to trace the loop. I often forget that in a loop like this, i have to increment each time LAST instead of the third step. That was a big issue i had when studying for the final.

REFERENCES:
https://www.geeksforgeeks.org/c-sharp/nested-loops-c-sharp/
