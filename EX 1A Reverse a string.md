# EX 1A Reverse a String
## DATE: 29/04/2025
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1. Input the string s.
2. Define a recursive function reverse(s):
   
     i) If len(s) == 1, return s.
   
     ii) Otherwise, return s[-1] + reverse(s[:-1]).
   
4. Call reverse(s) to reverse the string.
5. The function recursively reverses the string by appending characters from the end.
6. Print the reversed string.

## Program:
```

Program to implement Reverse a String
Developed by: Lavanya M
Register Number:  212222110021



def reverse(s):
    if len(s)==1:
        return s[0]
    else:
        
        return s[-1]+reverse(s[:-1])
s=input()
print(reverse(s))
```
## Output:
![image](https://github.com/user-attachments/assets/e71a969a-aaf9-43bd-be96-2f0325f7ad94)



## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
