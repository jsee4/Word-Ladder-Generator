# C Word Ladder Generator

This repository contains a Word Ladder Generator implemented in C. The program finds the shortest word ladder between two words of the same length, serving as a practical exercise in C programming, memory management, and algorithm implementation.

## What is a Word Ladder?

A word ladder is a sequence of words where each word differs from the previous word by exactly one letter. For example:
cat -> cot -> dot -> dog

## Features

- Generates the shortest word ladder between two input words
- Implements efficient memory management techniques
- Utilizes a graph-based approach for finding the shortest path
- Handles dynamic memory allocation and deallocation

## Getting Started

### Prerequisites

- GCC compiler
- Make (optional, for using the provided Makefile)

### Compilation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/c-word-ladder-generator.git
   cd c-word-ladder-generator
   ```

### Usage

Run the program with two words of the same length as arguments:

```
./main.exe
```

## Implementation Details

- The program uses a graph-based approach to find the shortest word ladder
- A custom dictionary is used to validate words and generate neighbors
- Efficient memory management is implemented using dynamic allocation and proper freeing of resources
- Error handling is in place for invalid inputs and memory allocation failures

## Learning Objectives

This project serves as a practice ground for:
- C programming fundamentals
- Dynamic memory allocation and deallocation
- Pointer manipulation
- Data structures (graphs, queues) implementation in C
- Algorithm design and implementation (breadth-first search)
- Error handling and input validation

## Contributing

Contributions to improve the efficiency, readability, or functionality of the code are welcome. Please feel free to submit pull requests or open issues for discussion.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
