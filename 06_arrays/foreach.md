# ARRAYS / For Each

A FOR EACH loop meanwhile is a simple way to go through every element inside an array without worrying about an index.
For Each automatically gives you one value at a time in order by appearance instead of manually controlling one like a For loop.
In this loop, it starts at the first value, processes it, then moves to the next one until we're at the end of an array, it's a bit like housekeeping going from room to room on a floor in a hotel.
Does it feel a little too easy? That's the whole point. That loop actually removes the chances of making mistakes like going out of bounds or forgetting to update the index.
Overall, foreach is a clean way to loop through arrays when you just got to read the data only.

foreach (datatype variableName in arrayName) 
{
  // code 
}

EUREKA:
When i did a little practice thing on W3schools, i wasn't quite sure what "i" meant in for that whole array as i thought that variable was just a placeholder gor the whole thing. But then when i tested it, it turns out "i" meant for every specific something in the array. 

COMMON MISTAKE:
I often forgot that Foreach only moves forward and can't skip around a value in an array. Whatever's on there must be checked regardless.


REFERENCES:
https://www.w3schools.com/cs/cs_foreach_loop.php
