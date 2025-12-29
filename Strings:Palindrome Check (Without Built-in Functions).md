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
~~~
s=input()
b=s[::-1]
if (s==b):
    print("The entered string is palindrome")
else:
     print("The entered string is not palindrome")
~~~
## Output
<img width="1056" height="308" alt="image" src="https://github.com/user-attachments/assets/1f291ca7-0f00-48a4-89d1-18278e23145c" />

## Result
Thus,the Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions is created successfully.
