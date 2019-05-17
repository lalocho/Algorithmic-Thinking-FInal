
Stone Game


Recursive Definition

The Recursive Defition of this problem is to decide whether or not Alex would net the biggest pile of stones possible in order to have more than lee if they were to select optimally, would be picking the biggst integer in the array until the array is empty. There is on ly two choices at a time, the first and last item in the array, and thus we are comparing both and finding the maximum possible.The recursive solutions would be storing the intial values of the array into a matrix, and accumulate the selected value.However when lee picks a pile, we substract the number from alex pile so as to not have to track two variables.


Storing Solutions


The solutions we are storing are the accumulative value depended on the max of the previous stored values, which in the beggining case would be the initial valiues of the pules array. The solutions that are being stored will always be the maximum solutions of piles[i] - dp[i+1][i+d], and piles[i+d] - dp[i][i+d-1].If we are assuming that Alex and lee always chose optimally. Understading this also make the probelm unusual because if there are an even number of pules with an odd number of stones then the solutions that are stored will always favor Alex. Howerever, if the length of the piles were odd then it can change the solution in which Dynamic Programming is perfect  for.
