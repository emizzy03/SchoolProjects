# Computer Science School Projects Portfolio

Welcome to my portfolio of academic projects! This repository contains a collection of Python and Java programs developed during my Computer Science coursework. 

These projects showcase my skills in algorithmic thinking, game development, artificial intelligence, concurrent programming, and graph algorithms. All code has been reviewed, documented, and formatted to ensure high readability and adherence to industry best practices.

## 📂 Projects Overview

### 1. Connect 4 Game (Python)
An interactive command-line implementation of the classic Connect 4 game. Play against a custom AI opponent that uses the **Minimax algorithm** to determine optimal moves.
* **File:** `Connect 4 Game.py`
* **Features**: 
  * Turn-based game loop with input validation.
  * AI Opponent utilizing Minimax with defined search depths.
  * Board state evaluation using pattern scoring heuristics.
  * ANSI color-coded terminal interface for an enhanced player experience.
* **Core Concepts**: Artificial Intelligence, Game Trees, Minimax Search, Heuristic Evaluation.
* **Execution**: 
  ```bash
  python "Connect 4 Game.py"
  ```

### 2. AI Flood Fill / Connected Components (Python)
A classical implementation of the Flood Fill algorithm applied on a 2D matrix, often used in paint applications for the "bucket fill" feature.
* **File:** `AI Assignment 2 (1).py`
* **Features**: Traverses and replaces contiguous blocks of identically colored pixels in a simulated image grid using **Breadth-First Search (BFS)**.
* **Core Concepts**: Graph Theory, Graph Traversal, Breadth-First Search, Queue Data Structures.
* **Execution**: 
  ```bash
  python "AI Assignment 2 (1).py"
  ```

### 3. PrimeThreads (Java)
A high-performance multithreaded Java application that computes the sum of all prime numbers within a specified mathematical range using distributed worker threads.
* **File:** `PrimeThreads/Prime.java`
* **Features**: 
  * Robust command-line argument parsing and validation.
  * dynamic creation and management of separate worker threads.
  * Results partitioned, synchronized, and aggregated seamlessly.
* **Core Concepts**: Object-Oriented Programming (OOP), Concurrency, Multithreading, Runnable pattern.
* **Execution**:
  ```bash
  cd PrimeThreads
  javac Prime.java
  java Prime <start_1> <end_1> [start_2 end_2 ...]
  # Example: 1 thread for primes between 1-1000
  java Prime 1 1000
  ```
