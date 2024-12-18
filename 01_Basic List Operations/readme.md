

### 🌟 Python List Practice Solutions

---

## **Overview**  
This section covers various Python list operations with real-life examples for better understanding. Each example is explained with its respective code and emoji representation for quick reference.

---

### **Table of Contents**  
- [Basic List Operations](#basic-list-operations)  
- [Intermediate List Operations](#intermediate-list-operations)  
- [Advanced List Operations](#advanced-list-operations)

---

### **Basic List Operations**

1. **Create a list of the first 10 natural numbers and print it.**  
   [Example 1](#create-a-ist-of-the-first-10-natural-numbers-and-print-it.)

2. **📥 Access and print the first, last, and middle elements of the list [10, 20, 30, 40, 50].**  
   [Example 2](#access-and-print-the-first-last-and-middle-elements-of-the-list-1020-3035-50)

3. **➕ Append the number 60 to the list [10, 20, 30, 40, 50] and print the updated list.**  
   [Example 3](#append-the-number-60-to-the-list-1020-3035-50-and-print-the-updated-list)

4. **📌 Insert the number 25 at the 3rd position in the list [10, 20, 30, 40, 50] and print the updated list.**  
   [Example 4](#insert-the-number-25-at-the-3rd-position-in-the-list-1020-3035-50-and-print-the-updated-list)

5. **🗑️ Remove the number 30 from the list [10, 20, 30, 40, 50] and print the updated list.**  
   [Example 5](#remove-the-number-30-from-the-list-1020-3035-50-and-print-the-updated-list)

6. **🚮 Pop the last element from the list [10, 20, 30, 40, 50] and print the updated list.**  
   [Example 6](#pop-the-last-element-from-the-list-1020-3035-50-and-print-the-updated-list)

7. **🔍 Count the occurrences of the number 2 in the list [2, 3, 2, 5, 2, 7, 8].**  
   [Example 7](#count-the-occurrences-of-the-number-2-in-the-list-232-525-27-8)

8. **📍 Find the index of the number 40 in the list [10, 20, 30, 40, 50].**  
   [Example 8](#find-the-index-of-the-number-40-in-the-list-1020-3035-50)

9. **🔄 Sort the list [5, 3, 8, 6, 7, 2] in ascending order and print the result.**  
   [Example 9](#sort-the-list-5386762-in-ascending-order-and-print-the-result)

10. **🔄 Reverse the list [10, 20, 30, 40, 50] and print the result.**  
    [Example 10](#reverse-the-list-1020-3035-50-and-print-the-result)

---

### **Intermediate List Operations**

11. **🧮 Create a list comprehension that generates a list of the squares of numbers from 1 to 10.**  
    [Example 11](#create-a-list-comprehension-that-generates-a-list-of-the-squares-of-numbers-from-1-to-10)

12. **🔢 Filter the even numbers from the list [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] using list comprehension.**  
    [Example 12](#filter-the-even-numbers-from-the-list-123456789-10-using-list-comprehension)

13. **🔄 Create a list comprehension that generates a list of tuples where each tuple contains a number and its square.**  
    [Example 13](#create-a-list-comprehension-that-generates-a-list-of-tuples-where-each-tuple-contains-a-number-and-its-square)

14. **📚 Flatten a list of lists [[1, 2], [3, 4], [5, 6]] using list comprehension.**  
    [Example 14](#flatten-a-list-of-lists-1234-56-using-list-comprehension)

---

### **Advanced List Operations**

15. **🛠️ Create a list of unique elements from multiple lists using set operations.**  
    [Example 15](#create-a-list-of-unique-elements-from-multiple-lists-using-set-operations)

16. **🔄 Perform a deep copy of a nested list using recursion.**  
    [Example 16](#perform-a-deep-copy-of-a-nested-list-using-recursion)

17. **🔍 Perform a linear search for multiple elements in a large list.**  
    [Example 17](#perform-a-linear-search-for-multiple-elements-in-a-large-list)

18. **💾 Serialize and deserialize a complex list object using JSON.**  
    [Example 18](#serialize-and-deserialize-a-complex-list-object-using-json)

19. **💻 Implement a custom sorting algorithm for a list of dictionaries based on specific key values.**  
    [Example 19](#implement-a-custom-sorting-algorithm-for-a-list-of-dictionaries-based-on-specific-key-values)

20. **⏪️ Implement a custom reverse function for a list while maintaining its original structure.**  
    [Example 20](#implement-a-custom-reverse-function-for-a-list-while-maintaining-its-original-structure)

---

Clicking on each example will take you directly to the specific section on the same page.

### 📝 Basic List Operations  

1. **🔢 Create a list of the first 10 natural numbers and print it.**  
   ```python  
   numbers = list(range(1, 11))  
   print(numbers)  # Output: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]  
   ```  
   **Explanation:**  
   This code creates a list of numbers from 1 to 10 using the `range()` function. `list(range(1, 11))` converts the sequence into a list.  
   
   **Real-Life Example:**  
   Imagine you are organizing a set of items (e.g., numbers or steps) for a project or event, where you need to count or list them systematically. This method helps create a sequential list of numbers from 1 to 10.

---

2. **📥 Access and print the first, last, and middle elements of the list [10, 20, 30, 40, 50].**  
   ```python  
   my_list = [10, 20, 30, 40, 50]  
   first_element = my_list[0]  
   last_element = my_list[-1]  
   middle_element = my_list[len(my_list) // 2]  

   print(first_element)  # Output: 10  
   print(last_element)   # Output: 50  
   print(middle_element) # Output: 30  
   ```  
   **Explanation:**  
   This code accesses elements from the list using positive and negative indexing. `my_list[0]` retrieves the first element, `my_list[-1]` retrieves the last element, and `my_list[len(my_list) // 2]` retrieves the middle element.  

   **Real-Life Example:**  
   When managing a list of tasks or items (e.g., groceries), you might want to access specific elements, such as the first task, last item, or a central task, similar to how you navigate a list.

---

3. **➕ Append the number 60 to the list [10, 20, 30, 40, 50] and print the updated list.**  
   ```python  
   my_list = [10, 20, 30, 40, 50]  
   my_list.append(60)  
   print(my_list)  # Output: [10, 20, 30, 40, 50, 60]  
   ```  
   **Explanation:**  
   This code adds the number 60 to the end of the list using the `append()` method.  

   **Real-Life Example:**  
   Imagine adding a new item to a shopping cart or a list of contacts in a phonebook, where `append()` simply adds a new element to the end of the existing list.  

---

4. **📌 Insert the number 25 at the 3rd position in the list [10, 20, 30, 40, 50] and print the updated list.**  
   ```python  
   my_list = [10, 20, 30, 40, 50]  
   my_list.insert(2, 25)  
   print(my_list)  # Output: [10, 20, 25, 30, 40, 50]  
   ```  
   **Explanation:**  
   The `insert(index, value)` method adds a new element at a specific index without affecting the existing elements.  

   **Real-Life Example:**  
   Consider inserting a new ingredient in the middle of a recipe, like adding garlic into a dish at a particular step. This is similar to inserting a new item at a specific position in a list.

---

5. **🗑️ Remove the number 30 from the list [10, 20, 30, 40, 50] and print the updated list.**  
   ```python  
   my_list = [10, 20, 30, 40, 50]  
   my_list.remove(30)  
   print(my_list)  # Output: [10, 20, 40, 50]  
   ```  
   **Explanation:**  
   The `remove(value)` method removes the first occurrence of a specified value from the list.  

   **Real-Life Example:**  
   Imagine decluttering a list of items, such as removing a product that is no longer available from an inventory system, leaving only relevant products behind.  

---

6. **🚮 Pop the last element from the list [10, 20, 30, 40, 50] and print the updated list.**  
   ```python  
   my_list = [10, 20, 30, 40, 50]  
   my_list.pop()  
   print(my_list)  # Output: [10, 20, 30, 40]  
   ```  
   **Explanation:**  
   The `pop()` method removes and returns the last element of the list.  

   **Real-Life Example:**  
   This is like removing the last item from a playlist or removing a student from the class roster at the end of a semester, keeping the relevant list of remaining items.  

---

7. **🔍 Count the occurrences of the number 2 in the list [2, 3, 2, 5, 2, 7, 8].**  
   ```python  
   my_list = [2, 3, 2, 5, 2, 7, 8]  
   count_2 = my_list.count(2)  
   print(count_2)  # Output: 3  
   ```  
   **Explanation:**  
   The `count(value)` method counts how many times a specified value appears in the list.  

   **Real-Life Example:**  
   For instance, if you are tracking how often a particular product appears in inventory, `count(2)` counts how many times the number 2 appears in the list of item IDs.  

---

8. **📍 Find the index of the number 40 in the list [10, 20, 30, 40, 50].**  
   ```python  
   my_list = [10, 20, 30, 40, 50]  
   index_40 = my_list.index(40)  
   print(index_40)  # Output: 3  
   ```  
   **Explanation:**  
   The `index(value)` method returns the index of the first occurrence of a specified value.  

   **Real-Life Example:**  
   Similar to searching for the location of a specific file in a folder system, where `index(40)` tells you exactly where the number 40 is located in the list.  

---

9. **🔄 Sort the list [5, 3, 8, 6, 7, 2] in ascending order and print the result.**  
   ```python  
   my_list = [5, 3, 8, 6, 7, 2]  
   my_list.sort()  
   print(my_list)  # Output: [2, 3, 5, 6, 7, 8]  
   ```  
   **Explanation:**  
   The `sort()` method rearranges the list in ascending order.  

   **Real-Life Example:**  
   Think of organizing a box of books in alphabetical order, or sorting items on a to-do list from earliest to latest. The `sort()` method works similarly by arranging items systematically.  

---

10. **🔄 Reverse the list [10, 20, 30, 40, 50] and print the result.**  
    ```python  
    my_list = [10, 20, 30, 40, 50]  
    my_list.reverse()  
    print(my_list)  # Output: [50, 40, 30, 20, 10]  
    ```  
    **Explanation:**  
    The `reverse()` method rearranges the list in reverse order.  

    **Real-Life Example:**  
    Consider flipping through the pages of a book backward, or reversing a sequence of numbers for a countdown. `reverse()` works similarly by reversing the order of items in a list.  

---

