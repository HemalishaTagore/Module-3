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
s = "google"
rev = s[::-1]

if s == rev:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output
<img width="452" height="172" alt="Screenshot 2025-10-20 125021" src="https://github.com/user-attachments/assets/ff9a3f4f-0b12-4f55-bdd2-43c68bc28436" />

## Result
Thus, to write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is executed successfully.
