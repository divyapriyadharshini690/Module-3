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
```python
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

lst=[]

for i in range(len(items)):

res=re.match('.e.',items[i])

if res:

pass
else:

lst.append(items[i])
print(lst)
```

## Output
<img width="531" height="177" alt="488745369-4829068f-edab-4155-9389-e358159663cf" src="https://github.com/user-attachments/assets/916e855b-bdf7-4c6d-9584-2780c87dda35" />


## Result
Thus, To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is verified.
