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
def check_elements_in_tuple(t):
    return 'n' in t and 8 in t
my_tuple = ('a', 'n', 3, 8, 'z')
if check_elements_in_tuple(my_tuple):
    print("Both 'n' and 8 exist in the tuple.")
else:
    print("Either 'n' or 8 (or both) do not exist in the tuple.")
~~~

## Output
<img width="457" height="111" alt="image" src="https://github.com/user-attachments/assets/585ec5dd-77f5-41ab-aa20-273dfe19f5e3" />

## Result
Thus the program has been executed successfully.
