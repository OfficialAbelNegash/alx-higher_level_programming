# 0x03. Python - Data Structures: Lists, Tuples

## Python - Data Structures: Lists, Tuples

### Learning Objectives

- At the end of the project, you are expected to be able to explain to anyone, without the help of Google:

#### General

- Why Python programming is awesome
- What are lists and how to use them
- What are the differences and similarities between strings and lists
- What are the most common methods of lists and how to use them
- How to use lists as stacks and queues
- What are list comprehensions and how to use them
- What are tuples and how to use them
- When to use tuples versus lists
- What is a sequence
- What is tuple packing
- What is sequence unpacking
- What is the del statement and how to use it

## Tasks

0. [Print a list of integers](./0-print_list_integer.py) : A function that prints all integers of a list.
   - Prototype: `def print_list_integer(my_list=[]):`
   - Format: one integer per line.
   - You are not allowed to import any module
   - You can assume that the list only contains integers
   - You are not allowed to cast integers into strings
   - You have to use `str.format()` to print integers
1. [Secure access to an element in a list](./1-element_at.py) : A function that retrieves an element from a list like in C.
   - Prototype: `def element_at(my_list, idx):`
   - If `idx` is negative, the function should return `None`
   - If `idx` is out of range (> of number of element in `my_list`), the function should return `None`
   - You are not allowed to import any module
   - You are not allowed to use `try/except`
2. [Replace element](./2-replace_in_list.py) : A function that replaces an element of a list at a specific position (like in C).
   - Prototype: `def replace_in_list(my_list, idx, element):`
   - If `idx` is negative, the function should not modify anything, and returns the original list
   - If `idx` is out of range (> of number of element in `my_list`), the function should not modify anything, and returns the original list
   - You are not allowed to import any module
   - You are not allowed to use `try/except`
3. [Print a list of integers... in reverse!](./3-print_reversed_list_integer.py) : A function that prints all integers of a list, in reverse order.
   - Prototype: `def print_reversed_list_integer(my_list=[]):`
   - Format: one integer per line.
   - You are not allowed to import any module
   - You can assume that the list only contains integers
   - You are not allowed to cast integers into strings
   - You have to use `str.format()` to print integers
4. [Replace in a copy](4-new_in_list.py) : A function that replaces an element in a list at a specific position without modifying the original list (like in C).
   - Prototype: `def new_in_list(my_list, idx, element):`
   - If `idx` is negative, the function should return a copy of the original `list`
   - If `idx` is out of range (> of number of element in `my_list`), the function should return a copy of the original `list`
   - You are not allowed to import any module
   - You are not allowed to use `try/except`
5. [Can you C me now?](5-no_c.py) : A function that removes all characters `c` and `C` from a string.
   - Prototype: `def no_c(my_string):`
   - The function should return the new string
   - You are not allowed to import any module
   - You are not allowed to use `str.replace()`
6. [Lists of lists = Matrix](6-print_matrix_integer.py) : A function that prints a matrix of integers.
   - Prototype: `def print_matrix_integer(matrix=[[]]):`
   - Format: see example
   - You are not allowed to import any module
   - You can assume that the list only contains integers
   - You are not allowed to cast integers into strings
   - You have to use `str.format()` to print integers

## Resource

- [3.1.3. Lists](https://docs.python.org/3.4/tutorial/introduction.html#lists)
  o [5. Data Structures](https://docs.python.org/3.4/tutorial/datastructures.html) (_until `5.3. Tuples and Sequences included`_)
- [Learn to Program 6 : Lists](https://www.youtube.com/watch?v=A1HUzrvS-Pw)
