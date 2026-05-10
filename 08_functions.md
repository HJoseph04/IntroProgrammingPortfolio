# FUNCTIONS

A function is a reusable block of code that performs a specific task, almost like giving your program its own mini‑robot helper that you can call whenever you need it. 
Instead of rewriting the same logic over and over, you can just put it into a function once and then “use” it by calling its name. 
When the program runs, it jumps into the function, executes the code inside, and then returns back to where it was originally. 
Functions can also take parameters, which are like inputs that let you customize what the function does each time you call it. 
This makes the code clean, easy to read, and much easier to debug because each function handles one job, just make your functions specific and don't make so much unless it's absolutely necessary. Imagine it like a checklist if you're into To-Do lists.
At first it feels odd to break your program into pieces like it's some puzzle, but once you see how much simpler your main code becomes, these functions start to feel important. 
Overall, functions help you organize your logic and avoid repeating yourself, which makes your programs more efficient and easier to manage. By the way, if a function is made not to return anything, it's a void.

functiontype returntype FunctionName (insert parameters)
{
    // function body: code 
    return (); // assuming the function isn't void
}

REFERENCES:
https://www.w3schools.com/cs/cs_methods.php
