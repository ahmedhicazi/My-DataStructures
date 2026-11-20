# 🚀 My-DataStructures

**A Personal C++ Project Featuring Custom Data Structures, Classes, and Utility Libraries.**

## 📖 About The Project

My-DataStructures is a personal project I started during my early journey in learning C++.

I created this project as a practical way to strengthen my programming skills, improve my problem-solving abilities, and apply the concepts I was learning.

Throughout my learning journey, I developed various custom classes and utility functions, gradually expanding the project with different implementations.

One of the main goals was to build data structures from scratch rather than simply using existing implementations. I wanted to understand how they work internally, how they manage memory, and how their operations are implemented.

**Everything in this project was developed by me as part of my learning journey and continuous effort to improve my programming skills.**

---

## 🏗️ Data Structures

A major part of this project focuses on implementing fundamental data structures from scratch using C++.

### 1. Dynamic Array
**File:** `DynamicArray.h`

A custom generic Dynamic Array implementation using C++ Templates and dynamic memory allocation.

The implementation provides operations for managing and manipulating array elements.

**Implemented Operations:**
- `SetItem()` – Update an element at a specific index.
- `GetItem()` – Retrieve an element.
- `Resize()` – Change the array size.
- `InsertAt()` – Insert an element at a specific position.
- `DeleteItemAt()` – Remove an element.
- `Find()` – Search for an element.
- `Reverse()` – Reverse the array.
- `Clear()` – Remove all elements.
- `Size()` – Get the array size.
- `IsEmpty()` – Check whether the array is empty.
- `Print()` – Display array elements.

### 2. Doubly Linked List
**File:** `DblLinkedList.h`

A generic Doubly Linked List implemented using C++ Templates.

Each node stores a value and two pointers:
- `next` – Points to the next node.
- `prev` – Points to the previous node.

**Implemented Operations:**
- Insert at the beginning.
- Insert at the end.
- Insert after a specific node.
- Delete a specific node.
- Delete the first node.
- Delete the last node.
- Find an element.
- Get a node by index.
- Get an item by index.
- Update an element.
- Reverse the list.
- Clear the list.
- Get the list size.
- Check whether the list is empty.
- Print the list.

### 3. Linked List-Based Stack
**File:** `LinkedList.h`

A custom Stack implementation built using linked nodes.

The implementation uses dynamically allocated nodes to store elements and maintain the Stack structure.

**Implemented Operations:**
- `Push()` – Add an element to the top.
- `Pop()` – Remove the top element.
- `Top()` – Retrieve the top element.
- `IsEmpty()` – Check whether the Stack is empty.

### 4. Queue
**File:** `MyQueue.h`

A generic Queue implementation built on top of the custom Doubly Linked List.

It follows the FIFO (First In, First Out) principle.

**Implemented Operations:**
- `push()` – Add an element to the queue.
- `pop()` – Remove an element.
- `front()` – Retrieve the first element.
- `back()` – Retrieve the last element.
- `IsEmpty()` – Check whether the queue is empty.
- `Size()` – Get the number of elements.

### 5. Array-Based Queue
**File:** `MyQueueArr.h`

An alternative Queue implementation that uses the custom Dynamic Array.

This implementation provides another approach to building the same data structure using a different underlying structure.

### 6. Stack
**File:** `MyStack.h`

A generic Stack implementation built on top of the custom Queue class.

It follows the LIFO (Last In, First Out) principle.

**Implemented Operations:**
- `push()` – Add an element to the top.
- `top()` – Retrieve the top element.
- `bottom()` – Retrieve the bottom element.

### 7. Array-Based Stack
**File:** `MyStackArr.h`

An alternative Stack implementation based on the custom Array-Based Queue.

It provides another implementation approach while reusing the project's own data structures.

### 8. Queue Line
**File:** `QueueLine.h`

A custom implementation for managing waiting lines using Queue concepts.

---

## 🧩 Custom Classes

In addition to data structures, this project contains several custom classes developed to practice Object-Oriented Programming and build reusable components.

### 1. MyString
**File:** `MyString.h`

A custom String class that implements Undo and Redo functionality.

It maintains two stacks to keep track of previous and undone string values.

**Implemented Operations:**
- `setValue()` – Update the current string while saving its previous value.
- `getValue()` – Retrieve the current string.
- `Undo()` – Restore a previous string value.
- `Redo()` – Restore an undone change.

This implementation demonstrates how Stack data structures can be used to manage operation history.

### 2. clsString
**File:** `clsString.h`

A custom String utility class containing a collection of string manipulation and processing operations.

It provides reusable functionality for working with text and performing different string-related tasks.

### 3. clsDate
**File:** `clsDate.h`

A custom Date class developed to handle date-related operations and calculations.

This is one of the larger classes in the project, containing an extensive implementation dedicated to working with dates.

### 4. clsInputValidate
**File:** `clsInputValidate.h`

A class dedicated to validating user input and ensuring that entered values meet specific conditions.

**Implemented Functionality:**
- Check whether numbers fall within a specific range.
- Validate dates.
- Check whether a date falls within a given date range.
- Read and validate integer input.
- Read and validate floating-point numbers.
- Read and validate double values.
- Read numbers within specified ranges.
- Read string input.
- Handle invalid numeric input and request valid input again.

### 5. clsInputValidate2
**File:** `clsInputValidate2.h`

An additional input validation implementation developed to work with different input validation scenarios.

### 6. clsUtil
**File:** `clsUtil.h`

A general-purpose utility class containing reusable helper functions.

Its functionality includes random number generation, random character generation, and other general utility operations.

---

## 🧰 Utility Library

### MyLib
**File:** `MyLib.h`

A collection of utility functions organized into namespaces.

It covers several areas of programming, including:

- String manipulation.
- Array operations.
- Mathematical functions.
- Random number generation.
- Recursion.
- Date operations.
- File handling.
- Input reading.

---

## 🧠 Concepts Practiced

Throughout developing this project, I practiced and improved my understanding of:

- C++ Programming Fundamentals.
- Object-Oriented Programming (OOP).
- Classes and Objects.
- Constructors and Destructors.
- Pointers and References.
- Dynamic Memory Allocation.
- C++ Templates.
- Generic Programming.
- Data Structures.
- Recursion.
- File Handling.
- Problem Solving.

---

## 💻 Technologies

- **Programming Language:** C++
- **Programming Concepts:** OOP, Templates, Pointers, and Dynamic Memory Allocation.
- **File Organization:** C++ Header Files (`.h`).

---

## 🎯 Project Purpose

This project was created as part of my journey in learning C++ and improving my software development skills.

My main objectives were:

- Build my own classes and utility functions instead of relying entirely on ready-made solutions.
- Implement data structures from scratch.
- Understand the internal logic behind data structures.
- Improve my understanding of memory management and pointers.
- Practice Object-Oriented Programming and Templates.
- Strengthen my logical thinking and problem-solving skills.
- Turn theoretical programming knowledge into practical implementations.

---

## 🔄 Project Status

This is a personal learning project that I continue to develop and improve as I gain more programming experience.

---

## 👨‍💻 Author

**Ahmed Hicazi**  
**Full Stack Desktop Developer**

🌐 Website: [ahmedhicazi.github.io](https://ahmedhicazi.github.io)

---

⭐ Thanks for visiting my repository!

*Built from scratch with C++ through continuous learning, experimentation, and practice.*
