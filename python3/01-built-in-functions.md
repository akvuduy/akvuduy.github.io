---
Title: 69 Built-in Functions of Python
Date: 11-12-2020
Resource: https://docs.python.org/3/library/functions.html
Layout: post
---

# 01. `abs(number)`
- Return the absolute value of a number.
- Take 1 *argument*: an integer, a floating point number, a complex number, or an object implementing `__abs__()`.
- Give 1 *return*: a positive integer, a positive floating point number, a magnitude of complex number, or ... [to be added]

~~~python
integer_number = -1                -> 1
bin_integer_number = -0b1          -> 1
octo_integer_number = -0o1         -> 1
hexa_integer_number = -0x1         -> 1
float_number = -1.2                -> 1.2
complex_number = complex(1,2)      -> 2.23606797749979 (= √(1^2 + 2^2))
~~~

# 02. `all(iterable)`
- Return True if all elements of the iterable are true | if the iterable is empty return False.
    - Ex: `[False, True, Flase] -> True`
- Take 1 *argument*: a sequence, a set, a mapping, or an iterable object.
- Give 1 *return*: a bool.
- When used on a dictionary, the `all()` function checks if all the *keys* are true, not the values.

# 03. `any(iterable)`
- Return True if any element of the iterable is true | If the iterable is empty, return False.
    - Ex: `[False, True, Flase] -> False`
- Take 1 *argument*: a sequence, a set, a mapping, or an iterable object.
- Give 1 *return*: a bool.
- When used on a dictionary, the `any()` function checks if all the *keys* are true, not the values.

