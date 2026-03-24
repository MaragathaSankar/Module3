# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
items=[153,147,124,102]
print(sum(items))
```
## Output
![Screenshot 2025-04-29 120233](https://github.com/user-attachments/assets/c459f7ba-80e3-4ba0-8dfc-fe6e998a5a2b)
## Result
Thus, the python program was executed successfully.

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

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print("Words without 'e':", l1)
```
## Output
![Screenshot 2025-04-29 120555](https://github.com/user-attachments/assets/441f2da3-ba81-472e-b7ce-d719b858935d)

## Result

The program successfully filters and returns all words from the
list that do not contain the letter 'e' using regular expressions in Python.

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
```python
def remove(string, n):
    a = ""
    for i in range(len(string)):
        if i != n:
            a = a + string[i]
    return a

text = input("Enter a string: ")
n = int(input("Enter the index to remove: "))

print("Modified string:", remove(text, n))

```
## Output
![Screenshot 2025-04-29 120612](https://github.com/user-attachments/assets/10d4dd2a-204e-4494-b8ca-393f8471fbfd)

## Result

The program successfully removes the character at the specified index from the given string using loops in Python.

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

The program successfully checks whether the string "google" is a palindrome or not (without using built-in functions).

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
x = ('a', 'n', 'g', '8', 8, 10, 'z')

print("'n' exists in tuple:", 'n' in x)
print("8 exists in tuple:", 8 in x)
```
## Output
![Screenshot 2025-04-29 120641](https://github.com/user-attachments/assets/00607186-cdf8-48f2-b001-63a9f87de3be)

## Result

The program successfully checks whether the elements 'n' and 8 exist within the given tuple using the in operator.
