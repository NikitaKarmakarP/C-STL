# C++ STL Fundamentals 📘

Welcome to the **Cpp-STL-Fundamentals** repository! This collection is designed to provide a comprehensive understanding of the **Standard Template Library (STL)** in C++. It includes examples, detailed explanations, and time complexity insights for key STL components like containers, iterators, and algorithms.

## Introduction

The **Standard Template Library (STL)** in C++ is a powerful library that provides several generic classes and functions to work with data structures and algorithms efficiently. This repository is designed to help you get a solid understanding of STL in a simple and concise way, providing real-world examples and explanations.

## Overview

The **Standard Template Library (STL)** in C++ is a collection of powerful, pre-defined templates that allow you to efficiently handle data structures and algorithms. Whether you are new to C++ or looking to sharpen your skills, this repository is a great place to learn and experiment with the STL.

In this repository, you'll find:
- Clear explanations of each STL container, iterator, and algorithm
- Time complexity analysis of STL operations
- Practical examples demonstrating common use cases

## STL Components Covered

### 1. **Containers**
STL containers are used to store and organize data efficiently. Here's a quick look at some of the containers you'll encounter:
- `vector`: Dynamic array-like container
- `list`: Doubly linked list
- `map`: Sorted associative container (key-value pairs)
- `set`: Collection of unique, sorted elements
- `queue`: FIFO (First In, First Out) container
- `stack`: LIFO (Last In, First Out) container

### 2. **Iterators**
Iterators are used to traverse through containers. You’ll learn how to use:
- **Input Iterators** for reading elements
- **Output Iterators** for writing elements
- **Forward Iterators** for traversing in one direction
- **Bidirectional Iterators** for traversing in both directions

### 3. **Algorithms**
STL provides a wide variety of algorithms for manipulating data:
- `sort()`: Sorting elements
- `find()`: Searching for an element
- `reverse()`: Reversing elements
- `accumulate()`: Summing up values in a range

## Time Complexity of Common Operations

Understanding time complexity helps you write more efficient code. Here's a brief overview of time complexity for common STL operations:

- **Vector**:
  - Access: O(1)
  - Insertion at the end: O(1)
  - Insertion at the beginning or middle: O(n)
  - Deletion: O(n)

- **Map**:
  - Insertion, Search, Deletion: O(log n)

- **Set**:
  - Insertion, Search, Deletion: O(log n)

These complexities depend on the specific container and operation. In-depth analysis is provided in the code examples.

## Getting Started

To get started, simply clone this repository to your local machine:

## bash

git clone https://github.com/your-username/Cpp-STL-Fundamentals.git

## Prerequisites
- A C++ compiler (e.g., GCC, Clang, Visual Studio)
- Basic knowledge of C++ programming

## Building and Running Examples
**Navigate to the project folder:**

## cd Cpp-STL-Fundamentals
**Compile a sample program:**

- g++ -o example example.cpp

## Run the compiled program:

- ./example

## Examples
**This repository includes various examples showcasing the power of STL in real-world scenarios. Below are a couple of simple examples:**

**Example 1: Using a Vector**

#include <iostream>

#include <vector>

int main() {

    std::vector<int> v = {1, 2, 3, 4, 5};
    
    // Access and print elements
    
    for (auto i : v) {
    
        std::cout << i << " ";
    
    }
    
    return 0;

}

## Example 2: Using a Map

#include <iostream>

#include <map>

int main() {

    std::map<int, std::string> m;
    
    m[1] = "One";
    
    m[2] = "Two";
    
    m[3] = "Three";

    // Iterate and print key-value pairs
    
    for (const auto& pair : m) {
    
        std::cout << pair.first << ": " << pair.second << std::endl;
    
    }
    
    return 0;

}

## Contributing
**We encourage contributions to this repository! If you have suggestions for improvements, new examples, or fixes, feel free to contribute.**
**Here's how:**

## Fork this repository
- Create a new branch (git checkout -b feature-name).
- Commit your changes (git commit -am 'Add feature').
- Push to your forked repository (git push origin feature-name).
- Create a pull request with a description of your changes.

## License
This repository is licensed under the MIT License - see the LICENSE file for details.

## Contact
For questions or suggestions, feel free to reach out:

**Email:** nikitakarmakar831@gmail.com

**GitHub:** NikitaKarmakarP

**Thank you for visiting Cpp-STL-Fundamentals! We hope this repository helps you master STL in C++ and improve your programming skills. Happy coding! 🎉**
