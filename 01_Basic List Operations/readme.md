
## **Overview**  
This section covers various Python list operations with real-life examples for better understanding. Each example is explained with its respective code and emoji representation for quick reference.

---
# Basic List Operations

## 🔢 Question 1: Create a list of the first 10 natural numbers and print it.

### Solution:
```python
numbers = list(range(1, 11))
print(numbers)  # Output: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```

### Real-Life Example:
This can be used for tasks like generating a list of steps for a process, such as instructions in a guide or checklist.

---

## 💔 Question 2: Access and print the first, last, and middle elements of the list `[10, 20, 30, 40, 50]`.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
first_element = my_list[0]
last_element = my_list[-1]
middle_element = my_list[len(my_list) // 2]

print(first_element)  # Output: 10
print(last_element)   # Output: 50
print(middle_element) # Output: 30
```

### Real-Life Example:
Useful for analyzing data where you need to extract key points, like the first, last, or median value in a dataset.

---

## ➕ Question 3: Append the number `60` to the list `[10, 20, 30, 40, 50]` and print the updated list.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
my_list.append(60)
print(my_list)  # Output: [10, 20, 30, 40, 50, 60]
```

### Real-Life Example:
Think of adding a new product to an inventory list, ensuring it’s updated in real time.

---

## 🔗 Question 4: Insert the number `25` at the 3rd position in the list `[10, 20, 30, 40, 50]` and print the updated list.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
my_list.insert(2, 25)
print(my_list)  # Output: [10, 20, 25, 30, 40, 50]
```

### Real-Life Example:
This can represent inserting a new task into a prioritized to-do list without reordering everything.

---

## 🚿 Question 5: Remove the number `30` from the list `[10, 20, 30, 40, 50]` and print the updated list.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
my_list.remove(30)
print(my_list)  # Output: [10, 20, 40, 50]
```

### Real-Life Example:
Removing discontinued products from a stock list to maintain accuracy.

---

## ♻️ Question 6: Pop the last element from the list `[10, 20, 30, 40, 50]` and print the updated list.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
my_list.pop()
print(my_list)  # Output: [10, 20, 30, 40]
```

### Real-Life Example:
This is like finalizing the last task in a list and removing it once completed.

---

## 🔄 Question 7: Reverse the list `[10, 20, 30, 40, 50]` and print it.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
my_list.reverse()
print(my_list)  # Output: [50, 40, 30, 20, 10]
```

### Real-Life Example:
This is like reversing a sequence of instructions for retracing your steps.

---

## 🔍 Question 8: Sort the list `[50, 10, 30, 40, 20]` in ascending order and print it.

### Solution:
```python
my_list = [50, 10, 30, 40, 20]
my_list.sort()
print(my_list)  # Output: [10, 20, 30, 40, 50]
```

### Real-Life Example:
This can be used to sort a list of scores, prices, or any other numeric data.

---

## ❌ Question 9: Clear all elements from the list `[10, 20, 30, 40, 50]` and print it.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
my_list.clear()
print(my_list)  # Output: []
```

### Real-Life Example:
Clearing a list of temporary items after processing them, like emptying a shopping cart post-purchase.

---

## 🌟 Question 10: Check if a value exists in the list `[10, 20, 30, 40, 50]` and print the result.

### Solution:
```python
my_list = [10, 20, 30, 40, 50]
value = 30
if value in my_list:
    print("Found")  # Output: Found
else:
    print("Not Found")
```

### Real-Life Example:
This can be used to verify if a specific product is available in an inventory list.

---

