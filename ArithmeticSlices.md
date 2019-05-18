Arithmetic Slices

Recursive Defintion

The recursive definition for this problem is finding if the next item  in an array shares a common difference with the curent and past consecutive element. The smallest valid case  you can have  must contain three elements so starting the solutions at i=2 seems very appropiate. What it basically is to check the difference between the current number and the past one matches the difference between the last one and the one before the last one.

Storing Solutions

My intention is to store the solutions for this problem by counting the length of my array and starting on index 2 as its you need to at least 3 elements to check if there is an arithmetic, you start checking and add 1 to the dp array if there is an arithmethic slice at that point thus counting the number of all valid slices possible.
