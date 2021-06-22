---
Title: "callable()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Functions"
  - "Methods"
  - "Debugging"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
  - "https://www.codecademy.com/learn/paths/data-science"
---

## Definition

Returns `True` if an object is callable, and `False` if an object is not callable.

## Syntax

```py
callable(object)
```

## Example 1

Use `callable()` to determine if the function `Slogan` is callable:

```codebyte/python
def Slogan():
    return "Welcome to Codecademy!"

print(callable(Slogan))
```

## Example 2

Use `callable()` to determine if the string `"Welcome to Codecademy!"` is callable:

```codebyte/python
print(callable("Welcome to Codecademy!"))
```