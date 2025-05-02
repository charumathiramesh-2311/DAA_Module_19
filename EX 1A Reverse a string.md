# EX 1A Reverse a String
## DATE:18.02.2025
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1. Define a function reverse(reverseme)
2. If the length of reverseme is 0, then return reverseme (base case).
3.  Else, return reverse(reverseme[1:]) + reverseme[0] (recursive case)
4. Read a string input from the user and store it in the variable reverseme
5. Call the function reverse(reverseme) and print the result,Stop.    

## Program:
```
/*
Program to implement Reverse a String
Developed by: charumathi R
Register Number:  212222240021
*/

def reverse(reverseme):
    if len(reverseme)==0:
        return reverseme
    else:
        return reverse(reverseme[1:])+reverseme[0]
reverseme=input()
print(reverse(reverseme))
```

## Output:
![image](https://github.com/user-attachments/assets/ec8b1261-518b-40fc-9456-6c4bc085ee9f)



## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
