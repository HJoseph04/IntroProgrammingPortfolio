# 2d ARRAYS


A 2D array is basically an array of arrays, which lets you store data in rows and columns instead of just one long line. 
I can picture it like a grid or a spreadsheet where each value has both a row index and a column index, like the ones you would make on Microsoft Excel.
This structure is useful when your data naturally fits into a table, like seating charts, game boards, or matrices in math (like i did this semester believe it or not). 
When the program runs through an array like this, it usually uses nested loops: the outer loop (i) moves through each row, and the inner loop (j) moves across the columns in that row. Sounds familiar? 
At first it can feel confusing because you have to keep track of two indexes instead of one, like we did with tracing, but once you visualize it as a grid, the flow becomes much easier to follow. 
A big advantage of 2D arrays is that they keep related data grouped together in a way that’s easy to access and update. 
Overall, 2D arrays can give you a structured way to organize information that has two dimensions.


INITIALIZATION:
int[] arrayName = new int[];


ITERATING:
int[,] array = new int[values];

for (int i = 0; i < array.Length(size of the array); i++ or i--)
{
    for (int j = 0; j < array.Length(size); j++ or j--)
    {
        // body
    }
    
}


EUREKA:
Part B of the tracing assignment, which was heavily focused on as part of my tutoring leading up to the final. I kept trying to jump ahead too much in my head when tracing that. But then, things clicked when i drew the array and what it was up to, it turns out that i needed to pay attention to the indexes with how they moved during each pass, i would go through by iteration until the numbers in the array are in order from lowest to highest value.

COMMON MISTAKE:
Sometimes i write up [j][i] with [i][j], which ends up mixing the order when i shouldn't. Which meant that my output would be too scrambled.


REFERENCES:
https://www.w3schools.com/cs/cs_arrays_multi.php
