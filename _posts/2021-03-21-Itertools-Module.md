---
title: itertools Module
tags: [Python]
style: fill
color: primary
description: What is itertools module for? Today, I will go over itertools module..
---

{% include elements/figure.html url="/assets/img/posts/loop.jpg"%}

<figcaption class="figure-caption text-center">Photo by <a href="https://unsplash.com/@tine999?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tine Ivanič</a> on <a href="https://unsplash.com/s/photos/loop?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a></figcaption>
<br>
This itertools module utilize computational resources efficiently. Using this module also tends to enhance the readability and maintainability of the code.

A little recap!

- An **Iterable** is something you can loop over.
- An **Iterator** is an object representing a stream of data. It does the iterating over an iterable. It consists of two dunder methods iter() and next() which is known as iterators protocols.

Python provides an excellent module to handle the iterators and that is called itertools. Here are some of the examples on how to use itertools module functions in your code:<br>

> To find out all the functions in the specific module, type dir(module_name) into the Python interactive session in terminal.

```python
>>> dir(itertools)
['__doc__', '__loader__', '__name__', '__package__', '__spec__', '_grouper', '_tee', '_tee_dataobject', 'accumulate', 'chain', 'combinations', 'combinations_with_replacement', 'compress', 'count', 'cycle', 'dropwhile', 'filterfalse', 'groupby', 'islice', 'permutations', 'product', 'repeat', 'starmap', 'takewhile', 'tee', 'zip_longest']
```

<br>

### product()

To find Cartesian Product of three lists:

```python
>>> import itertools
>>> A = ['a', 'b']
>>> B = [1, 2]
>>> C = ['p', 'q']
>>> for item in itertools.product(A, B, C, repeat=1):
...     print(item)
...
('a', 1, 'p')
('a', 1, 'q')
('a', 2, 'p')
('a', 2, 'q')
('b', 1, 'p')
('b', 1, 'q')
('b', 2, 'p')
('b', 2, 'q')
```

<br>

### groupby()

Find length of each items in the String:

```python
>>> import itertools
>>>[(k,len(list(v))) for k, v in itertools.groupby('AAAABBBCCDAABBB')]
[('A', 4), ('B', 3), ('C', 2), ('D', 1), ('A', 2), ('B', 3)]
```

<br>

### permutations()

Permutations function finds all the permutations (order matters) and returns iterator yielding tuples.

Find all permutations of the items in the list:

```python
>>> import itertools
>>> lst = [0, 1, 2]
>>> per = itertools.permutations(lst)
>>> print(per)
<itertools.permutations object at 0x1010a9890>  # location in memory
>>> print(list(per))
[(0, 1, 2), (0, 2, 1), (1, 0, 2), (1, 2, 0), (2, 0, 1), (2, 1, 0)]
```

<br>

### combinations()

Combinations function finds all the combinations (order does not matter) and returns iterator yielding tuples.

Find all combinations of the items in the list:

```python
>>> import itertools
>>> lst = [0, 1, 2]
>>> comb = itertools.combinations(lst)
>>> print(per)
<itertools.combinations object at 0x1011dd5f0>
>>> print(list(comb))
[(0, 1), (0, 2), (1, 2)]

```

<br>

**See also:**

- [itertools module](https://docs.python.org/3/library/itertools.html#itertools.groupby) in Python documentation for more functions like in the above.
