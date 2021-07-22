---
Title: "math.pow()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Functions"
  - "Arithmetic"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

## Definition

Returns the `float` value of `x` raised to the power of `y`.

## Syntax

```py
math.pow(x, y)
```

This contrasts with the built-in `**` operator in that `math.pow()` converts both its arguments to type `float`.

## Example 1

Use `math.pow()` to return `5` to the power of `3`:

```python
import math

print(math.pow(5, 3))

# Output: 125.0
```

## Example 2

Use `math.pow()` to return `5.5` to the power of `3.3`:

```python
import math

print(math.pow(5.5, 3.3))

# Output: 277.457759723262
```