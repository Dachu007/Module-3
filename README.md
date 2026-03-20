# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
match_words=['abd', '1221', 'abx', 'abd','xyz','abd']
ctr = 0
for word in match_words:
    if len(word) > 1 and word[0] == word[-1]:
        ctr += 1
print(ctr)
```

## Output

<img width="922" height="161" alt="image" src="https://github.com/user-attachments/assets/059faa2a-ba93-4656-929e-c594731547c2" />


## Result

Thus,the program is executed suucessfully.


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
<img width="657" height="199" alt="image" src="https://github.com/user-attachments/assets/6213e40e-597b-4748-9edc-a8b22f230af3" />


## Result
Thus,the program is executed suucessfully.


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
def remove(s):
    if len(s)>3:
        result=s[:3]+s[4:]
    else:
        result=s
    print(result)
```

## Output
<img width="1135" height="203" alt="image" src="https://github.com/user-attachments/assets/d7e5aa8c-be1f-409e-b16c-d99435963885" />


## Result
Thus ,the program is executed successfully.


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
def palindrome(a):
    if a==a[::-1]:
        print(f"The entered string is palindrome")
    else:
        print("The entered string is not palindrome")  
        
string =input()
palindrome(string)
```

## Output
<img width="1050" height="192" alt="image" src="https://github.com/user-attachments/assets/a6928958-8937-4568-a510-f412e3fa8a1b" />



## Result
Thus ,the program is executed successfully.


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
t = eval(input())

print('n' not in t)
print('8' in t)

```

## Output
<img width="1121" height="250" alt="image" src="https://github.com/user-attachments/assets/ea0937c1-e9d9-402c-b68b-c9eebd51a0e2" />


## Result
Thus,the program is executed suucessfully.
