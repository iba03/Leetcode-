#Valid Anagram Problem Explained:
  *In this problem we will be given 2 strings s and t.If the string 't' can be formed from the letters of the word 's',it is a valid anagram.
  *Here we use C language to check this
  *We will have an array of 26 integers each initialized to 0
  *And we will traverse the the string s and increment the index for each letter
  *if the string has letter 'a' it will be incremented for each of its occurance
  *Similarly traverse through string t but we will decrement for each the index value for each letter occurance
  *we will agian traverse through the arrray to check if each element has a value 0
  *if each value of the index is 0,it is valid anagram
  *else return false as it is not a anagram
