# Intermediate List Operations

## 🧮 Example 1: Create a list comprehension that generates a list of the squares of numbers from 1 to 10.

### Solution:
```python
squares = [i**2 for i in range(1, 11)]
print(squares)  # Output: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
```

### Real-Life Example:
Imagine you’re organizing a group of people into teams, and you need to calculate how many combinations are possible if you choose different numbers of members. This code could represent squaring values in such a calculation.

---

## 🔢 Example 2: Filter the even numbers from the list `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]` using list comprehension.

### Solution:
```python
evens = [i for i in range(1, 11) if i % 2 == 0]
print(evens)  # Output: [2, 4, 6, 8, 10]
```

### Real-Life Example:
This code is like finding every other product in a lineup—say, selecting only even-numbered shelves for stocking in a store.

---

## 🔄 Example 3: Create a list comprehension that generates a list of tuples where each tuple contains a number and its square.

### Solution:
```python
tuples = [(i, i**2) for i in range(1, 11)]
print(tuples)  # Output: [(1, 1), (2, 4), (3, 9), ..., (10, 100)]
```

### Real-Life Example:
This is similar to keeping a record of athletes’ jersey numbers and their performance scores in a table.

---

## 📚 Example 4: Flatten a list of lists `[[1, 2], [3, 4], [5, 6]]` using list comprehension.

### Solution:
```python
matrix = [[1, 2], [3, 4], [5, 6]]
flat_list = [item for sublist in matrix for item in sublist]
print(flat_list)  # Output: [1, 2, 3, 4, 5, 6]
```

### Real-Life Example:
This is like unboxing items from multiple packages and placing them all into one container for easier storage.

---

## 🔠 Example 5: Create a list comprehension that extracts the vowels from the string `"hello world"`.

### Solution:
```python
vowels = [char for char in "hello world" if char in "aeiou"]
print(vowels)  # Output: ['e', 'o', 'o']
```

### Real-Life Example:
This could represent filtering out specific items—like only picking apples from a mixed basket of fruits.

---

## 🔗 Example 6: Concatenate two lists `[1, 2, 3]` and `[4, 5, 6]` and print the result.

### Solution:
```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
combined_list = list1 + list2
print(combined_list)  # Output: [1, 2, 3, 4, 5, 6]
```

### Real-Life Example:
This is similar to merging two teams into one big team for a project.

---

## 🔡 Example 7: Create a list comprehension that converts all strings in the list `['a', 'b', 'c', 'd']` to uppercase.

### Solution:
```python
letters = ['a', 'b', 'c', 'd']
upper_letters = [letter.upper() for letter in letters]
print(upper_letters)  # Output: ['A', 'B', 'C', 'D']
```

### Real-Life Example:
Think of this as converting lowercase codes into standardized uppercase codes in a data entry process.

---

## 🚫 Example 8: Remove all occurrences of the value `3` from the list `[1, 3, 5, 3, 7, 3, 9]`.

### Solution:
```python
my_list = [1, 3, 5, 3, 7, 3, 9]
filtered_list = [x for x in my_list if x != 3]
print(filtered_list)  # Output: [1, 5, 7, 9]
```

### Real-Life Example:
Imagine you’re removing defective items from a batch during quality checks.

---

## ❓ Example 9: Check if a list is empty and print `"Empty"` if it is, otherwise print `"Not Empty"`.

### Solution:
```python
my_list = []
if not my_list:
    print("Empty")
else:
    print("Not Empty")  # Output: Empty
```

### Real-Life Example:
This is like checking if there’s any food left in your fridge before going grocery shopping.

---

## 🌟 Example 10: Create a list comprehension that replaces each vowel in a string with an asterisk (`'*'`).

### Solution:
```python
text = "hello world"
replaced_vowels = ''.join(['*' if char in 'aeiou' else char for char in text])
print(replaced_vowels)  # Output: h*ll* w*rld
```

### Real-Life Example:
This is similar to censoring specific words in a document with asterisks for privacy or compliance reasons.

---

