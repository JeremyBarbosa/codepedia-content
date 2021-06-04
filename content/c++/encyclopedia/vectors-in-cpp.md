---
Title: "Vectors in C++"
Subjects:
  - "Computer Science"
  - "Game Development"
Tags: 
  - "Vectors"
  - "Arrays"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-c-plus-plus"
  - "https://www.codecademy.com/learn/paths/computer-science"
---

A vector is a dynamic list of items, that can shrink and grow in size. It can only store values of the same type.


## Creating a Vector

To use vectors, it is necessary to `#include` the `vector` library.

```cpp
#include <vector>
```

To create a vector, you need to give it a type and a name:

```cpp
std::vector<type> name;
```

To create a vector with n number of items:

```cpp
std::vector<type> name(n);
```

To create a vector and also give it values:

```cpp
std::vector<type> name = {value1, value2, value3...};
```


## Vector Type

During the creation of a C++ vector, the data type of its elements must be specified. Once the vector is created, the type cannot be changed.

## Index

An index refers to an element’s position within an ordered list, like a vector or an array. The first element has an index of 0.

A specific element in a vector or an array can be accessed using its index, like `name[index]`.

```cpp
std::vector<double> order = {3.99, 12.99, 2.49};
 
// What's the first element?
std::cout << order[0];
 
// What's the last element?
std::cout << order[2];
```

## Example

To create a vector named `grade` with 3 items:

```codebyte/cpp
#include <iostream>
#include <vector>
 
int main() {
  
  std::vector<int> grades(3);
  
  grades[0] = 90;
  grades[1] = 86;
  grades[2] = 98;
  
  std::cout << grades[0] << "\n";
  std::cout << grades[1] << "\n";
  std::cout << grades[2] << "\n";

}
```