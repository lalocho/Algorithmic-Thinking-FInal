Minimum Falling Path Sum

Recursive Definition

The recursive definiton of this problem is to find the smallest summation on indices going down a grid. Starting from the top of a grid the path only allows you to go down left, down , or down right. Finding th correct path is very simple, all you have to do i find the minimum of the previously stored solutions, which in the begginging case is going to be the first row of the matrix given. For instance, in the example the first tow is [1,2,3] so the first row of my solutions matrix is [1,2,3]

Storing Solution

The solutions to the index that you are currentlky at will be the minimum value of the top left, top middle, and top right plus the value you are currently at. For Example[[1,2,3].[x1,x2,x3]]. x1= minimum of (1,2) + x1, x2 = minimum of (1,2,3) + x2, x3 = minimum of (2,3) + 3. This is how you can store the solutions to the problem. You can also have a variable that keeps track of the smalles element as you are storing solutions to solve this probel in O(n) time.
