
Stone Game


Recursive Definition

The Recursive Defition of this problem is to decide which of the two piles available would give Alex  the biggest pile of stones possible in order to have more than lee. If they were to select optimally or rationally, which would be picking the biggst integer in the array until the array is empty. There is only two choices available at a time, the first and last item in the array, and thus we are comparing both and finding the maximum possible.The recursive solutions would be storing the intial values of the array into a matrix that is nXn where n is the size of the array, and accumulate the selected value. However when lee picks a pile, we substract the number from alex pile so as to not have to track two variables.


Storing Solutions


The solutions we are storing are the accumulative value depended on the max of the previous stored values, which in the beggining case would be the initial valiues of the piles array. The solutions that are being stored will always be the maximum solutions of piles[i] - dp[i+1][i+d], and piles[i+d] - dp[i][i+d-1].Assuming that Alex and lee always chose optimally. Understading this also make the probelm pefect for Dynamic Programming.
