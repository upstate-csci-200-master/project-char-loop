# Project Char Loop
<img src="hula_loop_octodex03.gif" style="height:200px;">

Write a program (C version) that reads in a string from standard input and determines the following:

```
how many vowels are in the string (FOR THE PURPOSE OF THIS PROGRAM 'Y' is NOT considered a vowel)
how many upper case characters are in the string
how many digits are in the string
how many white space characters are in the string
example input  (read from a text file containing the string using file redirection from the command line)
```

This String has vowels and 12345 digits. 


example output
```
vowels = 8
upper = 2
digits = 5
whitespace = 6
```


**For a grade of B**, modify the C program to indicate which vowel occurs the most (ARRAYS OR ARRAYLISTS ARE NOT NECESSARY TO SOLVE THIS PROBLEM. Points will be deducted if you use them). In the case of a tie, only output the vowel which comes first alphabetically.

example input
```
This String has vowels and 12345 digits. 
```

example output
```
vowels = 8
upper = 2
digits = 5
whitespace = 6
vowel i occurs the most = 4
```
NOTE: if there are no vowels then output "no vowels"


**For a grade of A**, modify the B program to output a list of all consecutively repeated characters. That is any character which repeats consecutively in the string.

example input
'''
Some people raise raccoons for their pelts. A raccoon's home is called a nook. The person who cleans and tidies up the raccoonnooks is called the raccoonnookkeeper. Real word! 
'''


example output
```
vowels = 59
upper = 4
digits = 0
whitespace = 28
vowel o occurs the most = 21
repeated characters: c o c o l o c o n o l c o n o k e
```
NOTE: if there are no repeating characters then output "no repeating characters"
NOTE: by characters I mean ALPHABETIC characters, A - Z; not digits, not whitespace, not punctuation


Here's an example of what your output should look like for the A version if the input has NONE of the characters you are looking for. 
```
vowels = 0
upper = 0
digits = 0
whitespace = 0
no vowels
no repeating characters
```

```
Name your source code file: CharLoop.java
Submit to CodePost.
```

HELPFUL JAVA THINGS TO SOLVE THIS PROBLEM
1. learn methods in Java Character class - https://www.geeksforgeeks.org/character-class-java/
2. you may find these especially helpful for this program - isWhiteSpace, toLowerCase, isDigit, isAlphabetic
3. learn how to use the String class methods length and charAt - https://www.w3schools.com/java/java_ref_string.asp
4. this entire program can be written WITHOUT the use of arrays or arrayLists
5. for the B version consider having an integer counter for each vowel and use a series of if statements
6. for the A version consider going through the characters of the string a 2nd time to find and output repeating characters; you can do this simply with a 2nd while loop after your process the C and B versions in a while loop
7. here is a potential logic to solve all 3 versions
   1. read the string (DO NOT PRINT ANY PROMPTS)
   2. initialize all of your counters to zero, this program will have many counter variables, use integers
   3. use a while loop to loop through each character of the string, convert to lowercase then check for each condition and increment the appropriate counters
   4. output the counter results for vowels, upper, digits, and whitespace
   5. if you do B version output most frequent vowel, don't worry about ties
   6. if you do the A version then loop through the string again, compare each character to the one before it and if the same then output that character
   
 
