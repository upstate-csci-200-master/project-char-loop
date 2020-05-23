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


For a grade of B, modify the C program to indicate which vowel occurs the most. In the case of a tie, only output the vowel which comes first alphabetically.

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


For a grade of A, modify the B program to output a list of all consecutively repeated characters. That is any character which repeats consecutively in the string.

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
Complete this form - https://form.jotform.com/200302477347046
```

