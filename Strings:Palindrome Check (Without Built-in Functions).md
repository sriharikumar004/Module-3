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
a=input()
b=""
for i in range(len(a)-1,-1,-1):
    b=b+a[i]
if a==b:
    print("palindrome")
else:
    print("Not a palindrome")
```
## Output
<img width="373" height="192" alt="image" src="https://github.com/user-attachments/assets/3b634dd0-73fe-4a00-89d4-1ba03505f1d2" />
## Result
The program for string palindrome is executed successfully.
