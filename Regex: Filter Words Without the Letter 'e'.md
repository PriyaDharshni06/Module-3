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
