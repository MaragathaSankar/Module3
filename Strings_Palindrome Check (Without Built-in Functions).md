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
```python
text = "google"
rev_text = text[::-1]

if text == rev_text:
    print(text, "is a Palindrome")
else:
    print(text, "is Not a Palindrome")
```
## Output
![Screenshot 2025-04-29 120629](https://github.com/user-attachments/assets/bcfc37d6-f38b-4403-9b41-fcf088fa53ff)

## Result
```
The program successfully checks whether the string "google" is a palindrome or not (without using built-in functions).
