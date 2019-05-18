Minimum ASCII Delete Sum for Two Strings.

Recursive Definition

The recursive defintion of this problem is very similar to the edit distance problem except when you are calculating the solution to you current index this is what you would  do instead: If the letters are the same you take formt he upper diagonal and add to the current ascii caluyes letter. Otherwise you are taking the maxiumum from the top index and left index. So the way you are breaking down the problem is  a letter comparinson in a matrix. If you are deleting the letter, don't calculate it, instead take the max from the different indices. Otherwise, if you are keeing the letter accumulate the ascii valule.

Storing Solutions

The solutions you are storing is buy first calculating whether or not this letter needs to be deleted just like the edit distance problem, if the letter needs to be deleted, it is unnecessary to calculate its value, because the ideal solution is getting the total ascii value of the letter you didn't delete and substract it by the accunulative ascii values fo the two strings. This will net you the answer. In a more specific answer to this is: The solutions you are storing are dependent on an if else condition. If the letters are the same in the matrix then  you accumulate the top left diagonal with you letters ascii value. Else, You take the max from the top index and the left index and sotre that solution. You do this because you want to calcualte the toal letters they have in common and substract if by the tw o initials strings, the result is the minimum ascii delete.
