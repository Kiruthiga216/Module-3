# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
items=[150,140,120,100]
print(sum(items))

```

## Output

<img width="371" height="152" alt="image" src="https://github.com/user-attachments/assets/318c3de2-0cfd-4a45-bb71-d8d82bab37eb" />

## Result

Thus, the Python program that calculates the sum of all elements in a list.


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
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)

```
## Output

<img width="410" height="142" alt="image" src="https://github.com/user-attachments/assets/535ca79a-a5c1-4bbe-8b06-9cdd9aa0982e" />


## Result

Thus the program executed successfully.



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
def remove(a, b):
    c = ''
    for i in range(len(a)):
        if i != b:
            c += a[i]
    return c
a = input("Enter a string: ")
b = int(input("Enter the index to remove: "))

if 0 <= b < len(a):
    d = remove(a, b)
    print("Result:", d)
else:
    print("Invalid index")

```

## Output

<img width="372" height="206" alt="image" src="https://github.com/user-attachments/assets/ca9d5aea-7f03-476b-89e8-1d05ea867adb" />


## Result

Thus ,the program has been executed successfully.



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
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output

<img width="391" height="174" alt="image" src="https://github.com/user-attachments/assets/8b48ad93-849d-4cb9-9cdb-38e94eb31036" />


## Result
Thus the program executed successfully.



# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

```
x = input()
print("n" in x)
print("8" in x)
```

## Output

<img width="400" height="193" alt="image" src="https://github.com/user-attachments/assets/94a07bc3-9f6b-4758-b41f-b0c501f6a4b5" />


## Result

Thus the program executed successfully.
