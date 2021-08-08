---
title: Build-in Dictionary Methods
tags: [Python]
style: fill
color: primary
description: These article is an overview of methods that apply to dictionaries..
comments: true
---

<br>
Through out the examples, **d** will be used as a dictionary variable to show how to use built-in python dictionary methods.

<br>

### d.keys()

This method returns the keys in a **d**. For example:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d.keys()
dict_keys(['name', 'age', 'school'])
```

<br>

### d.values()

This method returns the values in a **d**. For example:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d.values()
dict_values(['Jon', 23, 'UCLA'])
```

<br>

### d.items()

This built-in method returns a list of tuples containing the key-value pairs in **d**. Example:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d.items()
dict_items([('name', 'Jon'), ('age', 23), ('school', 'UCLA')])
```

Returned items are called view objects. For practicality, you can think of returning lists but you need to convert d.items() to list of keys and values. Example, let's get the age's value:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> list(d.items())
[('name', 'Jon'), ('age', 23), ('school', 'UCLA')]
>>> list(d.items())[1][1]
23
```

<br>

### d.get( key [, default])

This method returns the value for a given key. if the key is not found then it will return None. For example:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> print(d.get('age'))
23
>>> print(d.get('lastname'))
None
>>> print(d.get('lastname', 'd does not have lastname'))
'd does not have lastname'
```

As you see in last print, you are able to assign a default value if the key does not exist.

<br>

### d.clear()

This method empties dictionary **d** of all key-value pairs:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d
{'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d.clear()
{}
```

<br>

### d.pop( key [, default])

This method removes a key from a dictionary and returns its associated value:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d.pop('age')
23
>>> d
{'name': 'Jon', 'school': 'UCLA'}
```

If key is not in dictionary **d** then it raises a KeyError exception. You can give a default value as well if key is not in **d**:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d.pop('lastname')
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
KeyError: 'lastname'
>>> d.pop('lastname', 'no lastname')
'no lastname'
```

<br>

### d.popitem()

This method removes the last key-value from a dictionary and returns tuple:

```python
>>> d = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d.popitem()
('school', 'UCLA')
>>> d
{'name': 'Jon', 'age': 23}
```

If the dictionary has no item in it then it will raise a KeyError exception:

```python
>>> d = {}
>>> d.popitem()
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
KeyError: 'popitem(): dictionary is empty'
```

<br>
### d.update(obj)

This method merges values of a dictionary **d** from obj (if obj is a dictionary). Lets demonstrate this method with examples to understand better:

```python
>>> d1 = {'name': 'Jon', 'age': 23, 'school': 'UCLA'}
>>> d2 = {'name': 'Alp', 'lastname': 'Eren'}
>>> d1.update(d2)
>>> d1
{'name': 'Alp', 'age': 23, 'school': 'UCLA', 'lastname': 'Eren'}
```

<br>

**See also:**

- [Official doc about Python dictionary](https://docs.python.org/3/tutorial/datastructures.html#dictionaries)
