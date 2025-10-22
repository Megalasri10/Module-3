# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
string = "google"
reversed_string = string[::-1]
if string == reversed_string:
    print(f'"{string}" is a palindrome.')
else:
    print(f'"{string}" is not a palindrome.')
```

## Output
<img width="1682" height="472" alt="image" src="https://github.com/user-attachments/assets/2cf2728a-e865-4ce6-8c3a-4db2e7197f91" />

## Result
The code is executed successfully.
