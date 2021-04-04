---
title: doctest
tags: [Python, Testing]
style: fill
color: primary
description: Useful doctest module to test code in a quick manner..
---

<br>
**Doctest** is a module from Python language's standard library that allows to generate tests based on output from the standard Python interpreter shell. This module finds patterns in the **docstring** that looks like interactive shell commands. Docstring usually are used for the description of a class or a function to better understand of the code and its purposes.

Let's look at the use case of doctest in an example:

```python
def factorial(n):
    '''
    This function calculates recursively and returns
    the factorial of a positive number.
    >>> factorial(2)
    2
    >>> factorial(4)
    24
    '''
    if n <= 1:
        return 1
    return n * factorial(n-1)
```

To run the test, I use _doctest_ as the main program via the -m option to the interpreter. Usually no output is produced while the tests are running. To make output more verbose, include the _-v_ option.

```python
$ python -m doctest -v file_name.py

Trying:
    factorial(2)
Expecting:
    2
ok
Trying:
    factorial(4)
Expecting:
    24
ok
1 items had no tests:
    file_name
1 items passed all tests:
   2 tests in file_name.factorial
2 tests in 2 items.
2 passed and 0 failed.
Test passed.
```

<br>
**See also:**

- [doctest](https://docs.python.org/3/library/doctest.html)
  official documentation to learn more.
