# 3A.List Operations in Python: Sum of List Items

##  Aim
To write a Python program that calculates the **sum of all elements** in a list.

##  Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

##  Program
```
items=[33,12,92,99,3,12]
print(sum(items))

```
## Output
<img width="443" height="120" alt="image" src="https://github.com/user-attachments/assets/6c170e61-028a-40bb-bade-f5e81444d4c1" />


## Result
Thus the program executed successfully.

## 3B.Python Program to Find a Sequence of One Uppercase Letter Followed by Numbers

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


#  3C.Strings-Remove Nth Index Character from a String

##  Aim
To write a Python program that accepts a string and removes the character at a specified index.

##  Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

##  Program
```
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
```

## Output

<img width="574" height="141" alt="image" src="https://github.com/user-attachments/assets/da208613-9379-443b-93fe-6a2065de385c" />


## Result
Thus the program executed successfully.

# 3D.Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program
```
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output

<img width="446" height="126" alt="image" src="https://github.com/user-attachments/assets/31424d8a-173b-46ab-9d86-f1ae7c5f23a8" />


## Result
Thus the program executed successfully.

# 3E.Tuple in Python: Check Element Existence

##  Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

##  Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

##  Program
```
t = eval(input())
n_not_exists = 'n' not in t
eight_exists = '8' in t
print(n_not_exists)
print(eight_exists)

```

## Output

<img width="425" height="149" alt="image" src="https://github.com/user-attachments/assets/a4e71807-d638-4f76-b46d-011c0b829d1a" />


## Result
Thus the program executed successfully.
