Integer Break

Recursive Definition

For this problem, my recursive definition involved something similar to calculating the fibonacci sequence, except that wehne calcualting the integer break you are constantly overwriting previous colutions with more maximinsed solutions and then proceeding the next index at the end of the loop. Just like in fibonacci, you are solivind this problem using Dynamic Programming with a single array.


Storing Solutions
In this case, the solutions were stored bu first calulating the most maximum solution dependent on the max of the previous solueiotn and difference between the two indices, and then store this solution if and only if the current index doesnt have a larger value. 
