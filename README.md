***The above problem can be solved in two ways:

**Naive Approach: In this approach, we will generate all possible configurations of numbers from 1 to 9 to fill the empty cells. Then we will try every configuration one by one until the correct configuration is found. Once all the unassigned positions are filled, we will check if the matrix is valid or not. If valid then we will print the matrix else repeat the same process for different cases.


**BackTracking Approach: In this approach, we will assign the numbers one by one to the empty cells but before assigning we will check whether it is valid or not. After checking we will assign the number, and recursively check whether this assignment leads to a solution or not. If the assignment leads to a solution then print the matrix and if it doesn’t lead to a solution, then try the next number for the current empty cell.
