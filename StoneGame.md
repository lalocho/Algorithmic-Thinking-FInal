
Stone Game
Recursive Definition
The Recursive Defition of this problem is to decide whether or not Alex would net the biggest pile of stones more than lee of they were to select optiomally, would be picking the biggst integer in the array until the array is empty. The recursive solutions would be storing the intial values of the array into a matrix, and accumulate the selected value.(The maximum).
Storing Solutions
The solutions we are storing are the accumulative value depended on the max of the previous stored values, which in the beggining case would be the initial valiues of the pules array. The solutions that are being stored will always be the maximum solutions of piles[i] - dp[i+1][i+d], and piles[i+d] - dp[i][i+d-1].If we are assuming that Alex and lee always chose optimally. Understading this also make the probelm unusual because if there are an even number of pules with an odd number of stones then the solkutions tore will always favor Alex. Howerever, if the linght of th e piles hwere odd then it can change the solution in which Dynamic Programming would be a perpect for.
