# EX 1D Linear search
## DATE:29/04/2025
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1. Input the number of elements n and the list List[] of n elements.
2. Define search(List, n): Iterate through the list, comparing each element with n.
3. If an element equals n, print "Found" and stop the loop.
4. Else, after completing the loop, print "Not Found".
5. Call the search(List, n) function to search for n in the list.

## Program:
```
/*
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: Lavanya M
Register Number:  212222110021
*/

def search(List,n):
    for i in List:
        if i==n:
            print("Found")
            break
    else:
        print("Not Found");

List=[input() for _ in range(int(input()))]
n=input();
```

## Output:

![image](https://github.com/user-attachments/assets/0436215c-15ed-4a88-8b35-f927cd1f053e)


## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
