# Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

##  Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

##  Program
~~~
import re
l1=[] 
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items: 
   if not re.search(r"e",i): 
      l1.append(i) 
print(l1)
~~~
## Output
![438864772-7a80a7bd-84d6-4231-881d-6fb00d4e43ff](https://github.com/user-attachments/assets/d4f16d15-74d4-4fe5-9157-6b8a78141ce5)

## Result
Thus, the program has been successfully executed.
