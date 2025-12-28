# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(a,n):
    l = len(a)
    for i in range(0,l):
        if(i!=n):
            print(a[i],end='')
a=input()
n=int(input())
remove(a,n)

```
## Output
<img width="1419" height="84" alt="image" src="https://github.com/user-attachments/assets/155de0c3-d306-4c79-82e7-e4903b7f456c" />

## Result
Thus, we were successfully able to write a Python program that accepts a string and removes the character at a specified index.
