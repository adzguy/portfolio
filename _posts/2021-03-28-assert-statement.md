---
title: assert statement
tags: [python]
style: fill
color: primary
description: Another useful tool to test code in a quick manner..
---

<br>

**Assert statements** are used when debugging code. It has a condition which is supported to be always `True`. If the condition is `False` then assert halts the program and gives ad `AssertionError`.

Syntax for using Assert:

> `assert <condition>` <br> `assert <condition>`, `<error message>`

Error message is an optional in assert statement which can give custom error message along with `AssertionError`.

**For example:**<br>

Without Error Message

```python
def average(arg):
    assert len(arg) != 0
    return sum(arg)/len(arg)

lst = []
print(average(lst))
```

The output will be:

```python
AssertionError
```

With Error Message

```python
def average(arg):
    assert len(arg) != 0, 'List is empty.'
    return sum(arg)/len(arg)

lst = []
print(average(lst))
```

The output will be:

```python
AssertionError: List is empty
```

<br>

**See also:**

- [assert statement](https://docs.python.org/3/reference/simple_stmts.html#grammar-token-assert-stmt)
  official documentation to learn more.
