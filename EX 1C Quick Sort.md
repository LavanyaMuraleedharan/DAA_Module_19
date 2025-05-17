# EX 1C Quick Sort
## DATE: 29/04/2025
## AIM:
To write a python program to implement quick sort using tha last element as pivot on the list of float values.

## Algorithm
1. Input the number of elements n and the array arr[].
2. Define quickSort(a, st, en): If st < en, partition the array and recursively sort the left and right sub-arrays.
3. Define partition(a, st, en): Choose a pivot, then rearrange elements so that those smaller than the pivot are on the left and those larger are on the right.
4. Call partition(a, st, en) to find the pivot index and recursively apply quickSort to sub-arrays.
5. Print the sorted array after sorting is completed.
   

## Program:
```
/*
Program to implement implement quick sort using the last element as pivot on the list of float values.
Developed by: Lavanya M
Register Number:  212222110021

def quickSort(a,st,en):
    if st<en:
        p=partition(a,st,en)
        quickSort(a,st,p-1)
        quickSort(a,p+1,en)
def partition(a,st,en):
    pivot=a[st]
    i=st
    j=en
    while True:
        while(i<=j and a[i]<=pivot):
            i=i+1
        while(i<=j and a[j]>=pivot):
            j=j-1
        if i<=j:
            a[i],a[j]=a[j],a[i]
        else:
            a[st],a[j]=a[j],a[st]
            return j


arr=[]
n=int(input())
for i in range(n):
    arr.append(eval(input()))
quickSort(arr,0,n-1)
print("Sorted array is:")
for i in range(n):
    print(arr[i])
*/
```

## Output:
![image](https://github.com/user-attachments/assets/e681c2eb-953a-46f5-9828-274e922fabcc)



## Result:
The program successfully sorts the input array using the QuickSort algorithm, arranging the elements in ascending order.
