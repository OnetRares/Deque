# Deque

🚀 Dynamic Deque Implementation in C++

📌 Overview

This project implements a dynamic deque (double-ended queue) in C++ using a block-based memory allocation strategy. The deque supports operations such as insertion and deletion from both ends, indexed access, and resizing as needed.

It also includes a menu-driven console application that allows users to interact with the deque using standard input.

🔧 Features

Efficient memory management using blocks of fixed size.

Push and pop operations from both the front and back.

Access elements by index with bounds checking.

Insertion and deletion at any position.

Dynamically resizable to accommodate growing data.

Console-based menu for easy user interaction.

📂 Project Structure
📦 Deque-Implementation
├── 📜 main.cpp          # Main program with menu-driven user interface
├── 📜 README.md         # Project documentation (this file)

🛠️ Technologies Used

C++ Standard Library (STL): For dynamic memory handling (vector, array)

Object-Oriented Programming (OOP): Class-based design

Exception Handling: Ensures robustness against invalid operations

⚠️ Error Handling

Trying to pop from an empty deque results in an exception.

Accessing an out-of-range index throws an error.

Invalid positions for insert/delete operations are checked before execution.
