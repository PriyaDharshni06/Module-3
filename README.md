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

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
``` python
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
fg= [word for word in items if not re.search('e', word)]
print(fg)

```
## Output
![image](https://github.com/user-attachments/assets/7382bf3a-3393-45cb-8ccd-70c543f0b401)

## Result
Thus Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is executed successfully.

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and joins the character after a each character.

## 🧠 Algorithm
1.Start

2.Define a function joinstring(text)

3.Use "-".join(text) to insert hyphens between characters of the string text

4.Store the result in a variable result

5.Print result

6.End

## 💻 Program
``` python
def joinstring(text):
    result = "-".join(text)
    print(result)
```

## Output
![image](https://github.com/user-attachments/assets/7f42a660-e147-424c-b6b3-1eff73eed1fc)

## Result
Thus the Python program that accepts a string and joins the character after a each character is executed successsfully.


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

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `52 and 12` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `52 and 12` exists within the tuple.
4. Print the results.

## 🧾 Program
``` python
a=eval(input())
print(True if '52' in a else False)
print(True if '12' in a else False)
```

## Output
![image](https://github.com/user-attachments/assets/5b8336a6-6377-46fa-909b-84ca2cb48022)

## Result
Thus  Python program that checks if the element `'n'` and the element `52 and 12` exist within a given tuple is executed successfully.
