# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all even elements** in a list.

## 🧠 Algorithm
1.Start

2.Define a function createlist(n)

3.Initialize an empty list l

4.Loop i from 1 to n-1

5.If i is divisible by 2 (i.e., even), append it to l

6.Print the list l

7.Calculate and print the sum of elements in l using sum(l)

8.End
## 🧾 Program
``` python
def createlist(n):
    l=[]
    for i in range(1,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list = ",sum(l))
```
## Output
![image](https://github.com/user-attachments/assets/3debe4f4-64f8-4bdb-b8cf-c2d7081e26a2)

## Result
Thus Python program to calculate the **sum of all even elements** in a list is executed successfully.
