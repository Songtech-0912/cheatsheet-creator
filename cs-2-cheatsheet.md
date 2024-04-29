# CS exam 2 cheatsheet

## Lists, tuples, and strings

### List methods

- `list()` creates new list
- `range(start, stop, step)` creates range
- `alist[idx]` index list
- `alist.append(val)` add item to list
- `alist.extend(anotherlist)` append another list to list
- `alist.index(val)` finds the index of first occurence of item in list
- `alist.insert(val)` inserts `val` into the list before the item at index 
- `alist.pop()` removes last item (and returns it too)
- `alist.reverse()` reverses order
- `alist.sort()` sort list in place (this doesn't return anything!)
- `alist.remove(val)` removes first item found that matches `val`
- `max(alist)` and `min(alist)` do what you'd think they do (return largest/smallest element)
- `alist + blist` concatenates two list
- `alist * n` a new list that returns `alist` n times

### String methods

- `astr.join(iter)` a new string by joining an iterable (e.g. list) of strings with `astr` between each item
- `astr.split(sep)` splits by whitespace (default) or by provided separator `sep`
- `astr.replace(a, b)` replace `a` with `b` in string
- `astr.startswith()`, `astr.endswith()`, `astr.title()`, `astr.upper()`, `astr.lower()` do as you'd expect
- `astr.isalpha()` is alphabetical, `astr.isdecimal()`, `astr.isnumeric()` and `astr.isdigit()` do as you'd expect
- `astr.find()` results in finding the index of the first occurence of a substring; -1 if the substring is not found
- `astr.strip()` this one works like this:
    - `x = "   Hellooo World!    "`
    - Output: `Hellooo World` - note how all the whitespace characters on the left and right are removed
    - When passed argument, it removes characters if they are present at the _start_ and _end_ of the string
    - Stripping on only the left or right of a string is also possible with `x.lstrip()` and `x.rstrip()`

## Sets & dictionaries

- `set <= other` tests that `set` is a subset of `other`
- `set < other` tests that `set` is a subset of `other` but `set != other`
- `set >= other` tests that `set` is a superset of `other`
- `set > other` tests that `set` is a superset of `other` but `set != other`
- `set | other` or `set.union(other)` combines all elements of `set` and `other`
- `set & other` or `set.intersection(other)` finds all elements both in `set` and `other`
- `set - other` or `set.difference(other)` finds elements in `set` that are not in `other`
- `set ^ other` or `set.symmetric_difference(other)` finds elements in `set` or `other` but not both
- `set.add(val)` and `set.remove(val)` do as you'd expect

## Quick snippets

Keys list and values list into dictionary:

```python
dict(zip(keys_list, vals_list))
```

Invert dictionary:

```python
inv_map = {v: k for k, v in my_map.items()}
```

Loop through dictionary:

```
for k, v in my_map.items():
    print(k, v)
```
