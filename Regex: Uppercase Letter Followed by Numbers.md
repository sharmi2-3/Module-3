## Python Program to Find a Sequence of One Uppercase Letter Followed by Numbers

##  Aim
To write a Python program using regular expressions to check whether a string contains a sequence of one uppercase letter followed by one or more digits.

##  Algorithm
1.Start the program.

2.Import the re (regular expression) module.

3.Read a string input from the user.

4.Define the pattern [A-Z]\d+, which represents:

      One uppercase letter ([A-Z])
     
      Followed by one or more digits (\d+)

5.Use re.search() to check whether the pattern exists in the input string.

6.If a match is found, print "Found a match!"

7.Otherwise, print "Not matched!"

8.End the program

##  Program
```
import re
text=input()
pattern=r"[A-Z]\d+"
match=re.search(pattern, text)
if match:
    print("Found a match!")
else:
    print("Not matched!")
```
## Output

<img width="446" height="116" alt="image" src="https://github.com/user-attachments/assets/f138fd09-ba70-49d5-8208-fb4f476151b2" />

## Result
The program successfully checks whether the user’s input contains one uppercase letter followed by numbers.
