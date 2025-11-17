# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes all the consonants from the string.

## 🧠 Algorithm
1.Start the program.

2.Define a function remove that takes a string as input.

3.Read an integer n from the user — this represents the index of the character to remove.

4.Use string slicing to construct a new string without the character at position n:

5.Take all characters before index n: string[:n]

6.Concatenate with all characters after index n: string[n+1:]

7.Store this concatenated result as the new string.

8.Print the final string.

10.End the program.

## 💻 Program
```python 
def remove(a):
    vowels = "aeiouAEIOU"
    result = ''.join(char for char in a if char in vowels)
    print(result)
```

## Output
<img width="521" height="209" alt="image" src="https://github.com/user-attachments/assets/15c2a37d-9b34-4e9d-bb46-eb1db5db6f0b" />


## Result
Thus, To write a Python program that accepts a string and removes all the consonants from the string is verified.
