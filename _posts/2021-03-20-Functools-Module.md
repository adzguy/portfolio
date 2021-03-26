---
title: functools Module
tags: [Python's Standard Library]
style: fill
color: primary
description: What is functools module in Python? Today, I will go over some useful higher order functions of functools module..
---

<br>
Functools module provides tools for working with functions and other callable objects, to adapt or extend them from new purposes without completely rewriting them. In other words, it gives me the tools for manipulating functions such as cached_property decorators. This module is available in python version 2.5 and later. Now, let's look at some tools that it provides.
<br>
<br>
#### cached_property
<br>
Useful for expensive computed properties of instances that are otherwise effectively immutable. Available in Python 3.8 and above and allows to cache class properties. For versions before 3.8, you can use cache and property decorators. Example:

```python
from functools import cached_property

class Data:
    def __init__(self, n):
        self.n = n

    @cached_property
    def f(self):
        total = 0
        for i in range(self.n):
            for j in range(self.n):
                total += i + j
        return total
```

When we instantiate an object and call it, it returns instantly.

```python
>>> data = Data(500)
>>> data.f
124750000
```

The cached value can be cleared by deleting the attribute.
<br>
<br>

#### lru_cache

<br>
Another useful functool is **lru_cache** which allows you to cache recursive function calls in a least recently used cache such as functions with multiple recursive calls like the [Fibonnacci sequence](https://en.wikipedia.org/wiki/Fibonacci_number). In code:

```python
from functools import lru_cache

@lru_cache
def fib(n):
    if n <= 1:
        return n
    return fib(n - 1) + fib(n - 2)
```

<br>
#### reduce()
<br>
functools.reduce() is useful to apply a function over and over on an iterable to reduce it to one single value. For instance:

```python
>>> from functools import reduce
>>> reduce(lambda x, y: x + y, [2, 4, 6, 8]) # (((2 + 4) + 6) + 8)
20
```

For more, you can check out the Python documentation on the [functools module](https://docs.python.org/3/library/functools.html).
