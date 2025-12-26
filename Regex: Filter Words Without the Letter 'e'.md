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
def filter_without_e(words):
    pattern = re.compile(r'^[^eE]*$')
    return [word for word in words if pattern.match(word)]
word_list = ['apple', 'banana', 'cherry', 'fig', 'grape', 'kiwi']
filtered_words = filter_without_e(word_list)
print("Words without the letter 'e':", filtered_words)
~~~
## Output
<img width="632" height="117" alt="image" src="https://github.com/user-attachments/assets/05c56113-34bc-49fa-b384-87fdb12a6964" />

## Result
Thus,the program has been executed successfully.
