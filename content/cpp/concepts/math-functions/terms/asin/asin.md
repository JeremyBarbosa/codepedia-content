---
Title: "asin()"
Subjects:
  - "Computer Science"
Tags:
  - "Functions"
  - "Arithmetic"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-c-plus-plus"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

## Definition

Returns the inverse sine of the argument in radians.

## Syntax

```py
asin(n)
```

## Example 1

Use `asin()` to return the inverse sine of `0.0`:

```cpp
#include <iostream>
#include <cmath>

int main() {
  double x = 0.0;
  double result;

  result = std::asin(x);

  std::cout << result << " radians" << "\n";
  // Output: 1.5708 radians
}
```