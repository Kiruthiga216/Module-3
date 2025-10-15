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
