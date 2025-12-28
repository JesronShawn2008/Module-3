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
word = input()
if word[::-1] == word:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
## Output
<img width="911" height="220" alt="image" src="https://github.com/user-attachments/assets/b08ec50a-bf62-40e6-a3bf-eb0baf01217a" />

## Result
Thus, we were successfully able to write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.
