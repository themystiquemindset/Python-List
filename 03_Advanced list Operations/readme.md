# 🌟 Advanced List Operations 🌟

## Overview 
This section provides examples of Advanced List Operations, each explained with real-life examples to ensure a clear and practical understanding.

##  🔢 Example 1: Generate a list of the first 10 Fibonacci numbers.  

## Solution:  
```python
fib = [0, 1]
for i in range(8):
    fib.append(fib[-1] + fib[-2])
print(fib)  # Output: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

### Real-life Example:  
Consider planning a trip with various destinations. Similar to generating Fibonacci numbers, each step (destination) builds upon the previous one, ensuring a structured sequence of places.

---

###  📄 Example 2: Split a list [1, 2, 3, 4, 5, 6, 7, 8] into two halves and print both halves.

## Solution:  
```python
my_list = [1, 2, 3, 4, 5, 6, 7, 8]
half = len(my_list) // 2
first_half = my_list[:half]
second_half = my_list[half:]
print(first_half)  # Output: [1, 2, 3, 4]
print(second_half)  # Output: [5, 6, 7, 8]
```

### Real-life Example:  
Consider dividing a task into two stages, like breaking down a large project into manageable phases, ensuring smooth progress and completion.

---

###  🥈 Example 3: Find the second largest number in the list [10, 20, 4, 45, 99, 4, 28].  
## Solution:  
```python
my_list = [10, 20, 4, 45, 99, 4, 28]
unique_sorted_list = sorted(set(my_list))
second_largest = unique_sorted_list[-2]
print(second_largest)  # Output: 45
```

### Real-life Example:  
Imagine ranking employees based on performance scores, and finding the second highest score helps identify the runner-up or next best performer.

---

###  🌟 Example 4: Create a list comprehension that generates a list of numbers from 1 to 100 that are divisible by both 3 and 5.  
## Solution:  
```python
divisible_by_3_and_5 = [i for i in range(1, 101) if i % 3 == 0 and i % 5 == 0]
print(divisible_by_3_and_5)  # Output: [15, 30, 45, 60, 75, 90]
```

### Real-life Example:  
Consider scheduling events at regular intervals, such as a reminder system that triggers notifications only at multiples of a set time, like every 15 minutes.

---

###  🔢 Example 5: Create a list comprehension that generates a list of all the prime numbers less than 50.  
**Solution**:  
```python
primes = [x for x in range(2, 50) if all(x % i != 0 for i in range(2, int(x**0.5) + 1))]
print(primes)  # Output: [2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47]
```

## Real-life Example:  
In quality control processes, identifying prime numbers can be used to check unique, error-free data sequences, ensuring the integrity of information.

---

###  🔗 Example 6: Zip two lists [1, 2, 3] and ['a', 'b', 'c'] into a list of tuples and print the result.  
## Solution:  
```python
list1 = [1, 2, 3]
list2 = ['a', 'b', 'c']
zipped_list = list(zip(list1, list2))
print(zipped_list)  # Output: [(1, 'a'), (2, 'b'), (3, 'c')]
```

## Real-life Example:  
In inventory management, pairing product IDs with their names (using zip) can help streamline data retrieval and organization.

---

###  📤 Example 7: Unzip a list of tuples [(1, 'a'), (2, 'b'), (3, 'c')] into two separate lists.  
## Solution:  
```python
zipped_list = [(1, 'a'), (2, 'b'), (3, 'c')]
list1, list2 = zip(*zipped_list)
print(list(list1))  # Output: [1, 2, 3]
print(list(list2))  # Output: ['a', 'b', 'c']
```
## Real-life Example:  
Consider breaking down student data from a combined list of IDs and names into two distinct lists for easier data management and analysis.

---

###  🔄 Example 8: Rotate a list [1, 2, 3, 4, 5] to the right by 2 positions.  
## Solution:  
```python
my_list = [1, 2, 3, 4, 5]
n = 2
rotated_list = my_list[-n:] + my_list[:-n]
print(rotated_list)  # Output: [4, 5, 1, 2, 3]
```

## Real-life Example:  
Imagine rearranging a playlist of songs, where rotating the list of tracks ensures a fresh order and a new listening experience.

---

###  🔍 Example 9: Find the common elements between two lists [1, 2, 3, 4] and [3, 4, 5, 6] and print the result.  
## Solution:  
```python
list1 = [1, 2, 3, 4]
list2 = [3, 4, 5, 6]
common_elements = list(set(list1) & set(list2))
print(common_elements)  # Output: [3, 4]
```

## Real-life Example:  
In customer service, identifying common issues reported by customers from two different feedback channels helps in creating targeted solutions.

---

###  🔄 Create a list comprehension that generates a list of strings where each string is the reverse of the corresponding string in the list ['abc', 'def', 'ghi'].  
**Solution**:  
```python
strings = ['abc', 'def', 'ghi']
reversed_strings = [s[::-1] for s in strings]
print(reversed_strings)  # Output: ['cba', 'fed', 'ihg']
```

**Real-life Example**:  
Consider reversing product descriptions for SEO purposes, ensuring better readability and relevance in search engine results.

---

