# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the given string  is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
``` python
def palindrome(a):
    mid=len(a)//2
    start=0
    last=len(a)-1
    flag=1
    while start<=mid:
        if a[start]!=a[last]:
            flag=0
            break
        start+=1
        last-=1
    if flag:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string=input()
palindrome(string)
```
## Output
![image](https://github.com/user-attachments/assets/9408866b-c870-4c1e-b9a7-f57f9e21b446)

## Result
Thus the  Python program to check whether the given string  is a **palindrome** or not is executed successfully.
