# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
~~~
items=[153,147,124,102]
print(sum(items))
~~~

## Output
![446131752-6fc78cda-88a2-4888-8afe-aee8fba47903](https://github.com/user-attachments/assets/a1411adc-e797-437a-b980-dac875eea678)

## Result
Thus the program executed successfully.

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
~~~
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)


~~~
## Output
![446205031-3f1caae4-a7ff-4b23-85b5-5b3146c00c64](https://github.com/user-attachments/assets/2c27739b-04d7-4a84-a63e-0e6dc0039d38)

## Result
Thus the program executed successfully.

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
~~~
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
~~~

## Output
![438315354-9cc8e6ce-fca0-4946-a708-a86d031d4503](https://github.com/user-attachments/assets/f197975a-fcf2-4c14-ba36-a4a2832c4624)

## Result
Thus the program executed successfully.

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
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
~~~
## Output
![446205586-1c590747-4d96-496d-b3c3-dc158ee0d6f8](https://github.com/user-attachments/assets/451b84f1-7481-4bd3-9bae-697c4d220fed)

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
~~~
tuplex = input()
print("n" in tuplex)
print("8" in tuplex)
~~~
## Output
![438321662-73c01d06-35b4-428d-911e-0edc4b8b7390](https://github.com/user-attachments/assets/68473f0d-c23a-4c94-8304-b371400594ce)

## Result
Thus the program executed successfully
