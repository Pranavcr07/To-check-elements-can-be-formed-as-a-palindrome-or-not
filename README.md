# To-check-elements-can-be-formed-as-a-palindrome-or-not
     This is a python code where we check if characters of a given string can be rearranged to form a palindrome by using functions.
     A set of characters can form a palindrome if at most one character occurs odd number of times and all characters occur even number of times.
     Operations in the program as follows:
     1)Create a count array of alphabet size which is typically 256. Initialize all values of count array as 0.
     2)Traverse the given string and increment count of every character.
     3)Traverse the count array and if the count array has more than one odd values, return false. Otherwise, return true.
