# STRUCTURES

A structure (or use struct in the code) is a custom data type that lets you bundle several related pieces of information together under one name. 
I think of it like creating your own mini‑blueprint for an object, where each variable inside the struct represents one detail you want to store. 
This is useful when a single value isn’t enough to describe something, like a student needing a name, an ID, the program they're in, and a grade all grouped together. 
When the program runs, a struct acts like a container that keeps all those fields organized so you can pass them around as one unit. 
Structs are value types, which means they get copied instead of referenced, and that can affect how they behave in memory. 
At first it feels strange to design your own data type, but once you see how much clearer your code becomes, it starts to feel natural. 
Overall, structures help you model real‑world things in a way that keeps your data organized and easy to work with.

struct MyStruct {  

  // insert variables
  
}; 

EUREKA:
When we redid a previous semester's final exam, i looked at Count and wondered if it's an int or float since it implies that it must store something like numbers or characters. But when i looked at it closer, i realized that Count can be a whole number (int), and for something like HealthScore, it can be either a float or double since it's a rating.

COMMON MISTAKE:
I sometimes made all the fields the same type just to make things simpler, except that data needed different types in order to make it work better.

REFERENCES:
https://www.w3schools.com/c/c_structs.php
