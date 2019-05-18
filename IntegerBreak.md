Integer Break

Recursive Definition

For this problem, my recursive definition would be to see how many twos(for even numbers) and twos and a three(for odd numbers) can be added in order to obtain the input. So you basically check if you can substract 3 from the number until you reach 4, which can only be divisible by 2 twos and then substract 3 if you are able to or 2 in the other case.In a more math way the funcion is f(x) = x(N-x) where n is the input.


Storing Solutions
In this case, the solutions were stored bu first calulating the most maximum solution dependent on the max of the previous solueiotn and difference between the two indices, and then store this solution if and only if the current index doesnt have a larger value. 
