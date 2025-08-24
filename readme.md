# Hello World Java Project

A simple Java program that demonstrates basic command-line argument handling.

## Description

This project contains a basic "Hello World" program in Java that takes a command-line argument and prints a greeting message.

## Files

- `Hello.java` - The main Java source file
- `Hello.class` - The compiled Java bytecode (generated after compilation)

## How to Run

### Prerequisites
- Java Development Kit (JDK) installed on your system
- Command line access

### Compilation
```bash
javac Hello.java
```

### Execution
```bash
java Hello [your_name]
```

### Example
```bash
java Hello World
```
Output: `Hello World`

## Code Overview

The program consists of:
- A `Hello` class with a `main` method
- Takes one command-line argument (`args[0]`)
- Prints "Hello " followed by the provided argument

## Notes

- Make sure to provide at least one command-line argument when running the program
- The program will throw an `ArrayIndexOutOfBoundsException` if no arguments are provided