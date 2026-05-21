# backend-agent-test

A Java project demonstrating a binary search algorithm.

## Overview

This project contains a `Main` class with a `binarySearch` method that searches for a target value in a sorted integer array and returns its index, or `-1` if not found.

## Requirements

- Java Development Kit (JDK) 8 or later

## Build

Compile the source file from the project root:

```bash
javac src/Main.java
```

## Usage

Run the program by passing a sorted list of integers followed by the target value to search for:

```bash
java -cp src Main <array elements> <target value>
```

**Example:**

```bash
java -cp src Main 1 2 3 4 5 3
```

The program prints the zero-based index of the target in the array, or `-1` if the target is not found.

Output for the example above (searching for `3` in `[1, 2, 3, 4, 5]`):

```
Result index: 2
```

## Project Structure

```
src/
└── Main.java   # Binary search implementation and entry point
```
