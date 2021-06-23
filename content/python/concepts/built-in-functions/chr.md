---
Title: "chr()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Functions"
  - "Unicode"
  - "Integers"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

## Definition

Returns Unicode characters represented by integers ranging between:

* [0-1]
* [0-1141]
* [0-111]

## Syntax

```py
chr(integer)
```

## Example 1

Use `chr()` to return the Unicode character represented by the integer `5`:

```python
print(chr(5))
```

## Example 2

Use `chr()` to return the Unicode character represented by the list `[67, 111, 100, 101, 99, 97, 100, 101, 109, 121]`:

```codebyte/python
codecademy = [67, 111, 100, 101, 99, 97, 100, 101, 109, 121]

for number in codecademy:
  character = chr(number)
  print("Character for ASCII value", number, "= ", character)
```