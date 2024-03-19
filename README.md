# Day1-Leetcode75-Merge-Strings
You are given two strings word1 and word2. Merge the strings by adding letters in alternating order, starting with word1. If a string is longer than the other, append the additional letters onto the end of the merged string.  Return the merged string.

Input :
word1=[a,b,c]
word2=[p,q,r]

Output:
result=[a,p,b,q,c,r]

Solution apporach:
1. store the len of word1 in a variable m
2. store the len of word2 in a variable n
3. create an empty list called result=[] to store the result.
4. assign i=0 and j=0 in initial stage of loop
5. Travese the word 1 and word 2 using while loop
   The loop executes untill the while loop gets fails.
   while i<m or j<n: #i=0 m=3 so loop gets executed.
6. create an if statement to check i<m, if it is true and store the value in the empty list "result"
7. increment i
8. same for j<n
9. increment j
10. return"".join(result)-> indicates the space b/w the values.

