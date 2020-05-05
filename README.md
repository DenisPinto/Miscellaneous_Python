# Miscellaneous_Python
Other Resources all internet


Contents
--------
**Python Articles:** **[`Modules`](#modules)__,__[`Exam`](#exam)__,__[`Comments`](#comments)__,__**

**Py Tricks:** **[`Mergin`](#mergin)__,__[`Sort`](#sort)__,__**

Modules
--------
**In this article, you will learn to create and import custom modules in Python. Also, you will find different techniques to import and use custom and built-in modules in Python.**

```python
# Python Module example

def add(a, b):
   """This program adds two
   numbers and return the result"""

   result = a + b
   reNoturn result
   
   # for more example visit url bellow :
   # https://www.programiz.com/python-programming/modules
```
Exam
--------
**Website with resource for Certificate Python

```python
# visit url : https://www.w3schools.com/python/python_exercises.asp
```
Comments
--------
**Website: Writing comments Python (Guide)

```python
# visit url : https://realpython.com/python-comments-guide/
```
Mergin
--------
**Merging two dicts in Python 3.5+ with a single expression.**

```python
# How to merge two dictionaries
# in Python 3.5+

>>> x = {'a': 1, 'b': 2}
>>> y = {'b': 3, 'c': 4}

>>> z = {**x, **y}

>>> z
{'c': 4, 'a': 1, 'b': 3}

# In Python 2.x you could
# use this:
>>> z = dict(x, **y)
>>> z
{'a': 1, 'c': 4, 'b': 3}

# In these examples, Python merges dictionary keys
# in the order listed in the expression, overwriting 
# duplicates from left to right.
#
# See: https://www.youtube.com/watch?v=Duexw08KaC8
```
Sort
--------
**How to sort a Python dict by value.**

```python
# How to sort a Python dict by value
# (== get a representation sorted by value)

>>> xs = {'a': 4, 'b': 3, 'c': 2, 'd': 1}

>>> sorted(xs.items(), key=lambda x: x[1])
[('d', 1), ('c', 2), ('b', 3), ('a', 4)]

# Or:

>>> import operator
>>> sorted(xs.items(), key=operator.itemgetter(1))
[('d', 1), ('c', 2), ('b', 3), ('a', 4)]
```
