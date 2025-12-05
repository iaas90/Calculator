
# 🧮 Simple Java Calculator

<!-- badges: start -->
[![Java Version](https://img.shields.io/badge/Java-8%2B-blue.svg)](#)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#)  
<!-- badges: end -->

## 📖 Table of Contents  
- [Description](#description)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Compile and Run](#compile-and-run)  
- [Usage Example](#usage-example)  
- [Project Structure](#project-structure)  
- [Potential Improvements](#potential-improvements)  

---

## Description  
A simple command-line calculator written in Java. It prompts the user to enter two numbers and then to choose an operation (addition, subtraction, multiplication, or division). Based on the user’s choice, it performs the operation and prints the result. Division by zero is handled gracefully — displaying an error instead of crashing.  

## Features  
- ✅ Addition, subtraction, multiplication, and division of two numbers  
- ✅ Safe handling of division by zero  
- ✅ Text-based command-line interface — no external dependencies or GUI  

## Getting Started  

### Prerequisites  
- Java Development Kit (JDK) version 8 or higher  
- Terminal or command-line environment  

### Compile and Run  
```bash
# From the root directory containing the `day3` folder:
javac day3/Calculator.java
java day3.Calculator
````

Then follow the on-screen prompts to enter numbers and select an operation.

---

## Usage Example

```
Enter the first number  
> 5  
Enter the second number  
> 3  
Choose an operation  
1. Addition  
2. Subtraction  
3. Multiplication  
4. Division  
> 1  
Result: 8.0  
```

---

## Project Structure

```
day3/
  └─ Calculator.java    ← main program
```

---

## Potential Improvements

* Add more operations (e.g. modulo, exponentiation)
* Add input validation (e.g. check for non-numeric input)
* Implement a loop to allow multiple calculations in one run
* Optionally add a more user-friendly interface (menu loop, clearer prompts)

---

