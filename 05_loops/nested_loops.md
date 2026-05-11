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
During Assignment 5 when we did the patterns, i was working on pattern 2 when i kept thinking the inner loop should've started at 1, that's because i forgot that the inner loop doesn't have to start at 1, but rather 0 or i. When i changed the number to 0, it felt more like my wheelhouse since it reminded me of the starting point for when i trace.

COMMON MISTAKE:
The steps on how to trace the loop. I often forget that in a loop like this, i have to increment each time LAST instead of the third step. That was a big issue i had when studying for the final.

REFERENCES:
https://www.geeksforgeeks.org/c-sharp/nested-loops-c-sharp/
