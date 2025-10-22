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
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for word in items:
    if not re.search(r"e", word):
        l1.append(word)
print("Words without the letter 'e':", l1)
```
## Output
<img width="1676" height="387" alt="image" src="https://github.com/user-attachments/assets/2c1ca74b-cbd0-4c7b-a8be-e52c5af901e7" />


## Result
The code is executed successfully.
