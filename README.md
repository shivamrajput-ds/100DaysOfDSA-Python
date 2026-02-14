# 100 Days of DSA in Python

## Overview
This repository is dedicated to providing a comprehensive guide to data structures and algorithms using Python. The materials and examples in this repository will help learners understand key concepts and apply problem-solving techniques effectively.

## Content Features
- Detailed explanations of essential data structures and algorithms.
- Code examples in Python illustrating each concept.
- Practical exercises to reinforce learning.

## Installation Instructions
To start working with this repository, follow these steps:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/shivamrajput-ds/100DaysOfDSA-Python.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd 100DaysOfDSA-Python
   ```
3. Ensure you have Python installed (Python 3.6+ recommended).
4. Install any required packages (if necessary) by invoking:
   ```bash
   pip install -r requirements.txt
   ```

## Usage Examples
Here are some quick usage examples for commonly used data structures:

### Example 1: Implementing a Stack
```python
class Stack:
    def __init__(self):
        self.items = []

    def is_empty(self):
        return len(self.items) == 0

    def push(self, item):
        self.items.append(item)

    def pop(self):
        return self.items.pop() if not self.is_empty() else None

# Usage of Stack
stack = Stack()
stack.push(1)
print(stack.pop())  # Output: 1
```

### Example 2: Implementing a Queue
```python
class Queue:
    def __init__(self):
        self.items = []

    def is_empty(self):
        return len(self.items) == 0

    def enqueue(self, item):
        self.items.insert(0, item)

    def dequeue(self):
        return self.items.pop() if not self.is_empty() else None

# Usage of Queue
queue = Queue()
queue.enqueue(1)
print(queue.dequeue())  # Output: 1
```

---
This README will continually evolve with additional content and examples to support learners in their journey through data structures and algorithms using Python.